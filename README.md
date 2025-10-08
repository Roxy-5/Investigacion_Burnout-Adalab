![](https://github.com/Roxy-5/Evaluacion1-Adalab/blob/main/image.jpg?raw=true)

🛸 Informe1  
Análisis de datos de la tabla.

🌍 Cómo usar  
Clona este repositorio.  
Instala las dependencias necesarias:  
- seaborn  
- matplotlib  
- pandas  
- numpy  
- scipy  
Ejecuta el proyecto.

🪐 Autor  
Rocío Ramírez

🌌 Proceso llevado a cabo para la limpieza y corrección:

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

🚀 Respuestas a las preguntas del cliente:

1. **¿Qué proporción de empleados trabaja en remoto?**
   
   <img width="515" height="415" alt="image" src="https://github.com/user-attachments/assets/4d63b17e-c512-4d5a-8cab-19cdbd5db2d7" />
   <img width="698" height="494" alt="image" src="https://github.com/user-attachments/assets/519b2705-461b-4d46-96ca-4c126cffb386" />
   Aproximadamente la mitad de los empleados trabaja en remoto, mostrando una distribución equilibrada entre ambas modalidades.

2. **¿El balance vida-trabajo influye en la retención?**
   <img width="737" height="458" alt="image" src="https://github.com/user-attachments/assets/cfd6c097-c4b5-4c6a-bea3-e83322909fd3" />
   Un mejor balance vida-trabajo se asocia claramente con una menor tasa de abandono.
   
2.1. **¿Son las personas que acuden presencial al trabajo los que más a gusto están con su vida/trabajo y su entorno?**
    <img width="667" height="461" alt="image" src="https://github.com/user-attachments/assets/adc51a2d-79a7-4265-8c5b-05db3a1be6b2" />
    <img width="699" height="598" alt="image" src="https://github.com/user-attachments/assets/4b473200-365d-4239-9e27-7f4bd0a63580" />
    <img width="517" height="400" alt="image" src="https://github.com/user-attachments/assets/24421c3a-ec1b-459a-9dd0-98854789ca1f" />
    No necesariamente; tanto en remoto como presencial hay empleados satisfechos, aunque los de remoto tienden a valorar más su entorno.
   
3. **¿Qué patrón sigue la relación edad vs salario según si trabajan en remoto?**
    <img width="657" height="461" alt="image" src="https://github.com/user-attachments/assets/bb3b43b3-37e7-4b9b-94df-f1cc7320e89b" />
    <img width="682" height="549" alt="image" src="https://github.com/user-attachments/assets/490d935a-585f-48c1-88e9-0975cbaa7605" />
    Los empleados en remoto suelen ser mayores y percibir salarios más altos que los presenciales.

4. **¿Qué diferencias hay en la satisfacción entre quienes se han ido y quienes siguen?**
    <img width="1184" height="659" alt="image" src="https://github.com/user-attachments/assets/c3298199-2814-4545-93ac-8f828eb39b2d" />
    Quienes permanecen en la empresa muestran mayores niveles de satisfacción laboral y con el entorno.
   
4.1. **¿Qué perfil de estudios o puesto de trabajo tienen mayor satisfacción?**
      <img width="1011" height="659" alt="image" src="https://github.com/user-attachments/assets/003ab749-9a0e-44fb-8feb-c7a3437bca04" />
      Los puestos técnicos y de mayor responsabilidad presentan los niveles más altos de satisfacción, independientemente del campo de estudios.

5. **¿Qué niveles de satisfacción son más frecuentes?**
   
    <img width="628" height="266" alt="image" src="https://github.com/user-attachments/assets/0d3d2695-094c-4f64-8a59-940be44d9a1a" />
    La mayoría de empleados reporta niveles medios o altos de satisfacción, especialmente entre quienes permanecen en la empresa.
   
6. **¿Qué variables están más correlacionadas con la satisfacción laboral?**
    <img width="733" height="461" alt="image" src="https://github.com/user-attachments/assets/d0c38021-d39c-4c2c-aff3-82486ffdb6d5" />
    La satisfacción con el entorno laboral y las relaciones interpersonales son las variables más correlacionadas con la satisfacción general.
   
7. **¿Existe relación entre años sin promoción y satisfacción, según el rendimiento?**
    <img width="879" height="484" alt="image" src="https://github.com/user-attachments/assets/79bbc3e5-e4f8-4ac6-95a8-85b6af4607a7" />
    A mayor tiempo sin promoción, la satisfacción tiende a disminuir, especialmente en empleados con bajo rendimiento.
   
8. **¿Qué campo educativo predomina entre los empleados?**
    <img width="854" height="639" alt="image" src="https://github.com/user-attachments/assets/2eca0ddf-4141-4ad6-88cd-dd865124417b" />
    El campo de Life Sciences es el más representado entre los empleados.
    
9. **¿Qué campo de estudio tiene mayor satisfacción?**
    <img width="1006" height="684" alt="image" src="https://github.com/user-attachments/assets/52958694-7d2c-4751-b980-0ef556a08ddb" />
    Los empleados de campos técnicos y de ingeniería suelen mostrar mayor satisfacción laboral.
    
10. **¿Cómo se distribuye el salario entre empleados que se han ido y los que se han quedado?**
    <img width="1009" height="554" alt="image" src="https://github.com/user-attachments/assets/f681fa70-7608-4655-9977-b41394a094e7" />
    Los empleados que permanecen en la empresa tienden a tener salarios ligeramente superiores a los que se han ido.
    
11. **¿Qué roles tienen mayor tasa de abandono?**
    <img width="623" height="464" alt="image" src="https://github.com/user-attachments/assets/0c737c1b-f268-4c58-9568-1b21d9276632" />
    Los roles comerciales y de soporte presentan las tasas de abandono más elevadas.
  
12. **¿Cómo varía el número de empleados que se fueron o se quedaron según los años que llevaban en la empresa?**
    <img width="979" height="547" alt="image" src="https://github.com/user-attachments/assets/3f8c81ba-e7fb-473b-a65d-6b9da6467c93" />
    Los empleados con menos años en la empresa presentan una mayor tasa de abandono que aquellos con mayor antigüedad.
    
13. **¿Cómo se agrupan `yearssincelastpromotion` y `yearswithcurrmanager` según el estado de `attrition`?**
    <img width="1013" height="550" alt="image" src="https://github.com/user-attachments/assets/f0a5955a-979f-4be8-89a9-bd3e498a2926" />
    Quienes abandonan la empresa suelen haber pasado menos tiempo sin promoción y menos tiempo con su manager.
    
14. **¿Qué relación hay entre el salario y la antigüedad de los empleados que se quedaron, según si trabajan en remoto o no?**
    <img width="621" height="464" alt="image" src="https://github.com/user-attachments/assets/0f0cfc29-52f8-425c-862a-f856df5e6524" />
    Los empleados que trabajan en remoto y permanecen en la empresa tienden a tener mayor antigüedad y salario.
    
15. **¿Qué forma tiene la distribución de monthlyincome y cómo varía según el joblevel?**
    <img width="784" height="484" alt="image" src="https://github.com/user-attachments/assets/b7e3dada-1137-484b-8c91-ab2ea176a115" />
    A mayor nivel de puesto, mayor es el ingreso mensual promedio.
    
16. **¿Quién tiene mayor salario, hombres o mujeres?**
    <img width="684" height="484" alt="image" src="https://github.com/user-attachments/assets/c4ff6c06-0988-49d6-8172-1db6a20393d6" />
    No se aprecian diferencias salariales significativas entre hombres y mujeres.
    
17. **¿Viajar afecta la satisfacción o la rotación?**
    <img width="984" height="584" alt="image" src="https://github.com/user-attachments/assets/5924b848-3331-4453-940b-f11d99156fb5" />
    Los empleados que viajan más tienden a mostrar menor satisfacción laboral y mayor rotación.

18. **¿Cómo se relacionan distancefromhome y salary?**
    <img width="784" height="484" alt="image" src="https://github.com/user-attachments/assets/5b26ac22-9258-469b-aacc-c6c4aedefe58" />
    No existe una relación clara entre la distancia al trabajo y el salario.
    
19. **¿Impacto en clima laboral y productividad?**
    <img width="902" height="554" alt="image" src="https://github.com/user-attachments/assets/e0263708-883c-48e9-8751-693ebf4e580a" />
    <img width="1484" height="492" alt="image" src="https://github.com/user-attachments/assets/39e9fc68-f645-4e53-882b-2626254ad600" />
    Los empleados que abandonan la empresa tienden a mostrar menor satisfacción con el entorno, menor involucramiento y peores evaluaciones de desempeño.

🌋 Hallazgos

- La proporción de empleados en remoto es relevante, pero la rotación afecta tanto a quienes trabajan en remoto como a quienes no.
- Un mejor balance vida-trabajo se asocia con menor rotación.
- Los empleados que permanecen muestran mayores niveles de satisfacción laboral y con el entorno.
- No se observan diferencias salariales significativas entre hombres y mujeres.
- Los empleados con menos años en la empresa presentan mayor tasa de abandono.
- Algunos departamentos y roles presentan tasas de abandono más altas.
- El campo educativo predominante es Life Sciences, pero la satisfacción varía más por puesto que por estudios.
- Los empleados que viajan más tienden a mostrar menor satisfacción y mayor rotación.
- No existe una relación clara entre la distancia al trabajo y el salario.
- Los empleados que abandonan la empresa muestran menor satisfacción con el entorno, menor involucramiento y peores evaluaciones de desempeño.

🧭 Recomendaciones estratégicas

- Fomentar el balance vida-trabajo con políticas de flexibilidad y conciliación.
- Realizar encuestas periódicas y planes de acción en departamentos con mayor rotación.
- Facilitar oportunidades de promoción interna y desarrollo profesional.
- Implementar programas de onboarding y mentoring para nuevos empleados.
- Revisar la política de viajes para minimizar el impacto negativo en la satisfacción.
- Mantener la equidad salarial y monitorizar posibles brechas.
- Potenciar el trabajo en remoto, ya que no afecta negativamente al clima laboral.
- Capacitar a los managers en liderazgo y gestión de equipos.
