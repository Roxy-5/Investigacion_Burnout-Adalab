![](https://github.com/Roxy-5/Evaluacion1-Adalab/blob/main/image.jpg?raw=true)

### 🔍 Investigación Burnout
Analizamos los datos de Toasted Minds Inc. 🍞 para descubrir las verdaderas causas detrás de la rotación de empleados y proponer estrategias que impulsen la retención del talento y el bienestar laboral.

### 🎬 Storytelling
En una noche lluviosa de 1950, la agencia de detectives LadySpies 🕵️‍♀️ recibe una llamada urgente. Un misterio inquietante recorre los pasillos de la empresa:

*“Las ganas de quedarse han muerto… y nadie sabe por qué”.*

Nuestra misión: resolver el caso.
Como detectives de datos, analizaremos a fondo el perfil de los empleados, examinaremos cada variable para generar relaciones y seguiremos las pistas hasta encontrar al verdadero culpable.

¿Serán las condiciones de trabajo? ¿El salario? ¿El ambiente?
¡Acompáñanos en esta investigación y descubre el desenlace de este enigma empresarial! 

### 🌍 Cómo usar  
Clona este repositorio.    
Instala las dependencias necesarias:  
- seaborn  
- matplotlib  
- pandas  
- numpy  
- scipy  

Ejecuta el proyecto.  
Ejecuta la presentación.

🪐 Autores  
Rocío Ramírez, Irina, Elena y Ángela

### 🌌 Proceso llevado a cabo para la limpieza y corrección

- **Exploración inicial:**    
  - Análisis de estructura, tipos de datos, valores nulos y duplicados.
  - Uso de métodos como `.info()`, `.sample()`, `.dtypes`, `.describe()`, `.isnull()`, `.duplicated()`, `.unique()`.

- **Transformaciones aplicadas:**  
  - Normalización de variables (edad, género, salario, etc.).
  - Conversión de tipos de datos y corrección de formatos.
  - Eliminación de columnas irrelevantes o duplicadas.
  - Corrección de valores erróneos y unificación de categorías.

- **Gestión de valores nulos:**  
  - Imputación de nulos en variables categóricas con "Unknown" o la moda según el caso.
  - Imputación de nulos en variables numéricas con la mediana o técnicas avanzadas (KNNImputer).
  - Eliminación de columnas con demasiados nulos si no aportan valor.

- **Reordenamiento y exportación:**  
  - Reordenamiento de columnas para mayor claridad.
  - Exportación del dataset limpio a CSV y a base de datos MySQL.

### 🚀 Respuestas a las preguntas del cliente:

1. **¿El balance vida-trabajo influye en la retención?**  
   <img width="737" height="458" alt="image" src="https://github.com/user-attachments/assets/cfd6c097-c4b5-4c6a-bea3-e83322909fd3" />
   Un mejor balance vida-trabajo se asocia claramente con una menor tasa de abandono.
   
2. **¿Son las personas que acuden presencial al trabajo los que más a gusto están con su vida/trabajo y su entorno?**     
    <img width="667" height="461" alt="image" src="https://github.com/user-attachments/assets/adc51a2d-79a7-4265-8c5b-05db3a1be6b2" />
    <img width="517" height="400" alt="image" src="https://github.com/user-attachments/assets/24421c3a-ec1b-459a-9dd0-98854789ca1f" />
    Las personas que trabajan en remoto tienden a mostrar mayor satisfacción con el entorno laboral.
   
3. **¿Qué patrón sigue la relación edad vs salario según si trabajan en remoto?**  
    <img width="657" height="461" alt="image" src="https://github.com/user-attachments/assets/bb3b43b3-37e7-4b9b-94df-f1cc7320e89b" />
    <img width="682" height="549" alt="image" src="https://github.com/user-attachments/assets/490d935a-585f-48c1-88e9-0975cbaa7605" />
    Los empleados en remoto suelen ser mayores y percibir salarios más altos que los presenciales.

4. **¿Qué diferencias hay en la satisfacción entre quienes se han ido y quienes siguen?**  
    <img width="1184" height="659" alt="image" src="https://github.com/user-attachments/assets/c3298199-2814-4545-93ac-8f828eb39b2d" />
    Quienes permanecen en la empresa muestran mayores niveles de satisfacción laboral y con el entorno.
   
5. **¿Qué perfil de puesto de trabajo tiene mayor satisfacción, según el género?**    
      <img width="1011" height="659" alt="image" src="https://github.com/user-attachments/assets/003ab749-9a0e-44fb-8feb-c7a3437bca04" />
      Los puestos de mayor responsabilidad presentan niveles más altos de satisfacción, destacando los técnicos y de ventas en hombres y Recursos Humanos en mujeres.

6. **¿Qué niveles de satisfacción son más frecuentes?**     
    <img width="628" height="266" alt="image" src="https://github.com/user-attachments/assets/0d3d2695-094c-4f64-8a59-940be44d9a1a" />
    La mayoría de empleados reporta niveles medios o altos de satisfacción, especialmente entre quienes permanecen en la empresa.
   
7. **¿Qué variables están más correlacionadas con la satisfacción laboral?**  
    <img width="733" height="461" alt="image" src="https://github.com/user-attachments/assets/d0c38021-d39c-4c2c-aff3-82486ffdb6d5" />
    La satisfacción con el entorno laboral y las relaciones interpersonales son las variables más correlacionadas con la satisfacción general.
   
8. **¿Existe relación entre años sin promoción y satisfacción, según el rendimiento?**  
    <img width="879" height="484" alt="image" src="https://github.com/user-attachments/assets/79bbc3e5-e4f8-4ac6-95a8-85b6af4607a7" />
    A mayor tiempo sin promoción, la satisfacción tiende a disminuir, especialmente en empleados con bajo rendimiento.
   
9. **¿Qué relación hay entre el trabajo en remoto y el abandono, según el género?** 
    <img width="1075" height="463" alt="image" src="https://github.com/user-attachments/assets/75b17c79-0c21-448e-a009-32bc5d325ec4" />
    El trabajo en remoto reduce la tasa de abandono en ambos géneros, pero el efecto es especialmente notable en las mujeres.
        
10. **¿Influye el número de empresas previas en la satisfacción laboral o en la rotación?**
    <img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/209ce61d-ed1e-44d7-806b-3185f17696e2" />
    A mayor número de empresas previas, la satisfacción laboral tiende a ser menor y la rotación aumenta.
    
11. **¿Cómo se distribuye el salario entre empleados que se han ido y los que se han quedado?**  
    <img width="1009" height="554" alt="image" src="https://github.com/user-attachments/assets/f681fa70-7608-4655-9977-b41394a094e7" />
    Los empleados que permanecen en la empresa tienden a tener salarios ligeramente superiores a los que se han ido.
    
12. **¿Qué roles tienen mayor tasa de abandono?**  
    <img width="623" height="464" alt="image" src="https://github.com/user-attachments/assets/0c737c1b-f268-4c58-9568-1b21d9276632" />
    Los roles comerciales y de soporte presentan las tasas de abandono más elevadas.
  
13. **¿Cómo varía el número de empleados que se fueron o se quedaron según los años que llevaban en la empresa?**  
    <img width="979" height="547" alt="image" src="https://github.com/user-attachments/assets/3f8c81ba-e7fb-473b-a65d-6b9da6467c93" />
    Los empleados con menos años en la empresa presentan una mayor tasa de abandono que aquellos con mayor antigüedad.
    
14. ** 17.- ¿Cómo se agrupan los años desde la última promoción y los años con el manager actual según el estado de abandono?**
    <img width="1013" height="550" alt="image" src="https://github.com/user-attachments/assets/f0a5955a-979f-4be8-89a9-bd3e498a2926" />
    Quienes abandonan la empresa suelen haber pasado menos tiempo sin promoción y menos tiempo con su manager.
    
15. **¿Qué relación hay entre el salario y la antigüedad de los empleados que se quedaron, según si trabajan en remoto o no?**  
    <img width="621" height="464" alt="image" src="https://github.com/user-attachments/assets/0f0cfc29-52f8-425c-862a-f856df5e6524" />
    Los empleados que trabajan en remoto y permanecen en la empresa tienden a tener mayor antigüedad y salario.
    
16. **Qué forma tiene la distribución de ingresos mensuales y cómo varía según el nivel de puesto de trabajo?** 
    <img width="784" height="484" alt="image" src="https://github.com/user-attachments/assets/b7e3dada-1137-484b-8c91-ab2ea176a115" />
    A mayor nivel de puesto, mayor es el ingreso mensual promedio.
    
17. **¿Quién tiene mayor salario, hombres o mujeres?**  
    <img width="684" height="484" alt="image" src="https://github.com/user-attachments/assets/c4ff6c06-0988-49d6-8172-1db6a20393d6" />
    No se aprecian diferencias salariales significativas entre hombres y mujeres.
    
18. **¿Viajar afecta la satisfacción o la rotación?**  
    <img width="984" height="584" alt="image" src="https://github.com/user-attachments/assets/5924b848-3331-4453-940b-f11d99156fb5" />
    Los empleados que viajan más tienden a mostrar menor satisfacción laboral y mayor rotación.

19. **¿Cómo se relacionan distancefromhome y salary?**  
    <img width="784" height="484" alt="image" src="https://github.com/user-attachments/assets/5b26ac22-9258-469b-aacc-c6c4aedefe58" />
    No existe una relación clara entre la distancia al trabajo y el salario.
    
20. **¿Impacta el clima laboral en la productividad?**  
    <img width="902" height="554" alt="image" src="https://github.com/user-attachments/assets/e0263708-883c-48e9-8751-693ebf4e580a" />
    <img width="1484" height="492" alt="image" src="https://github.com/user-attachments/assets/39e9fc68-f645-4e53-882b-2626254ad600" />
    Los empleados que abandonan la empresa tienden a mostrar menor satisfacción con el entorno, menor involucramiento y peores evaluaciones de desempeño.

### 🌋 Hallazgos

- **Rotación y satisfacción:** Los empleados que abandonan la empresa muestran menores niveles de satisfacción laboral y con el entorno respecto a quienes permanecen.
- **Género y abandono:** No existen diferencias salariales significativas entre hombres y mujeres, pero sí diferencias en la satisfacción y en los motivos de abandono según el departamento.
- **Trabajo en remoto:** El teletrabajo se asocia a mayor antigüedad y salarios más altos, así como reduce la tasa de abandono, especialmente en mujeres.
- **Balance vida-trabajo:** Un mejor equilibrio vida-trabajo disminuye claramente la rotación.
- **Viajes y rotación:** Los empleados que viajan más por trabajo tienden a estar menos satisfechos y a abandonar más.
- **Antigüedad:** Los empleados con menos años en la empresa presentan mayor tasa de abandono.
- **Promociones:** A mayor tiempo sin promoción, menor satisfacción, sobre todo en empleados con bajo rendimiento.
- **Satisfacción y relaciones interpersonales:** La satisfacción con el entorno y las relaciones interpersonales son las variables más correlacionadas con la satisfacción general.
- **Departamentos críticos:** Algunos departamentos y roles presentan tasas de abandono significativamente superiores.
- **Experiencia previa:** A mayor número de empresas previas, la satisfacción laboral tiende a ser menor y la rotación aumenta.
- 
### 🧭 Recomendaciones estratégicas

- **Mejorar el entorno laboral:** Implementar acciones para aumentar la satisfacción con el entorno y las relaciones interpersonales, especialmente en los departamentos con mayor rotación.
- **Fomentar el teletrabajo:** Potenciar el trabajo en remoto, sobre todo para perfiles con mayor riesgo de abandono y para mujeres.
- **Revisar políticas de promoción:** Establecer planes de carrera y promoción más transparentes y frecuentes para reducir la insatisfacción y la fuga de talento.
- **Equilibrio vida-trabajo:** Promover medidas de conciliación y flexibilidad horaria para mejorar el balance vida-trabajo.
- **Atención a los nuevos empleados:** Desarrollar programas de onboarding y seguimiento para empleados con poca antigüedad, ya que son los que más abandonan.
- **Gestión de viajes:** Revisar la política de viajes laborales para minimizar su impacto negativo en la satisfacción y la retención.
- **Monitorizar roles críticos:** Identificar y actuar sobre los puestos y departamentos con mayor rotación mediante encuestas y entrevistas internas.
- **Valorar la experiencia:** Identificar candidatos con alta rotación previa y ofrecerles programas de integración y seguimiento para mejorar su satisfacción y retención.
- **Seguimiento personalizado:** Realizar análisis periódicos segmentados por género, modalidad de trabajo y antigüedad para detectar riesgos y oportunidades de mejora.

### 🎞️ Presentación
https://www.canva.com/design/DAG0n5W6AYA/rAZtzRmvKAmXKUTSdWdfPw/edit?utm_content=DAG0n5W6AYA&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
