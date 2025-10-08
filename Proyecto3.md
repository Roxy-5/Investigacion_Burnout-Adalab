# Documentacón proyecto módulo 3

## Columnas

- **Age**: Edad del empleado.
- **Attrition**: Indica si el empleado dejó la empresa (Yes/No).
- **BusinessTravel**: Frecuencia de viajes laborales (e.g., travel_rarely).
- **DailyRate**: Tarifa diaria estimada para clientes, calculada en base al salario.
- **Department**: Departamento en el que trabaja el empleado.
- **DistanceFromHome**: Distancia en kilómetros desde el hogar al trabajo.
- **Education**: Nivel educativo del empleado en escala numérica.
- **EducationField**: Campo de estudio académico del empleado.
- **employeecount**: Valor constante de "1", indicando un solo empleado por registro.
- **employeenumber**: Número de identificación del empleado.
- **EnvironmentSatisfaction**: Nivel de satisfacción con el ambiente laboral.
- **Gender**: Género del empleado.
- **HourlyRate**: Tarifa por hora calculada.
- **JobInvolvement**: Nivel de compromiso del empleado en el trabajo.
- **JobLevel**: Nivel jerárquico del puesto del empleado.
- **JobRole**: Función o rol específico del empleado.
- **JobSatisfaction**: Satisfacción general en el puesto.
- **MaritalStatus**: Estado civil (e.g., Single, Married).
- **MonthlyIncome**: Ingreso mensual estimado en base al salario anual.
- **MonthlyRate**: Tarifa mensual estimada en función de la tarifa diaria.
- **NUMCOMPANIESWORKED**: Número de empresas previas en las que ha trabajado.
- **OverTime**: Indica si el empleado trabaja horas extras (Yes/No).
- **PercentSalaryHike**: Incremento porcentual en el salario.
- **PerformanceRating**: Evaluación de desempeño en una escala numérica.
- **RelationshipSatisfaction**: Satisfacción con relaciones interpersonales en el trabajo.
- **StandardHours**: Clasificación de jornada (Full Time/Part Time).
- **StockOptionLevel**: Nivel de opciones sobre acciones asignadas.
- **TOTALWORKINGYEARS**: Años totales de experiencia laboral.
- **TrainingTimesLastYear**: Número de sesiones de entrenamiento en el último año.
- **WORKLIFEBALANCE**: Nivel de balance entre vida personal y laboral.
- **YearsAtCompany**: Años en la empresa actual.
- **YearsInCurrentRole**: Años en el rol actual.
- **YearsSinceLastPromotion**: Años desde la última promoción recibida.
- **YEARSWITHCURRMANAGER**: Años trabajando con el mismo gerente.
- **DateBirth**: Año de nacimiento del empleado.
- **Salary**: Salario anual calculado para el empleado.
- **RoleDepartament**: Combinación de rol y departamento.
- **NUMBERCHILDREN**: Número de hijos del empleado (si está disponible).
- **RemoteWork**: Indica si el empleado trabaja de forma remota (Yes/No).

## Información añadida de las columnas:

- **Age**: Tiene valores de tipo: "twenty-six" entre los datos.
- **BusinessTravel**: Los valores nulos pertenecen todos a "non-travel", antes no se incluía esta dato y ahora hay que corregirlo.
- **DailyRate**: Calculado cómo el coste de externalización por día del empleado. 
- **DistanceFromHome**: Puede que nos hayamos equivocado e introducido algún valor negativo.
- **employeenumber**: id de identificación de los empleados. 
- **EnvironmentSatisfaction**: Según la documentación es una métrica que va de 1 a 4. Si el número es de más de un dígito, el valor correcto es el primero. Por ejemplo, si encontráis 41, el valor correcto es 4.
- **Gender**: 1 es female y 0 male
- **HourlyRate**: Esta columna es el coste de externalización del empleado por hora, está calculado según el dailyrate: dailyrate/8.
- **StandardHours**: los nulos corresponden a la categoría de "Full Time". 
- **Salary**: salario anual
