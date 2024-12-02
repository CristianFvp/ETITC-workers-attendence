# Consultas.

1. Listar a los trabajadores que tienen mas de 15 años o mas de experiencia
   
```sql
SELECT Emple1, nombre, apellido, cargo, años_experiencia
From Empleados
Where años_experiencia >= 15;
```

2. Cuantos trabajadores hay por departamento
   
```sql
SELECT departamento, COUNT (*) AS total_empleados
From trabajadores
Group BY departamento;
```

3. Listar los trabajadores con asistencia incompleta en el mes de diciembre

```sql
SELECT ID_Empleados, nombre, apellido, numero_de_documento, fecha_ingreso, fecha_salida
From Empleados
Inner join asistencia a ON ID:Eempleados = ID_Empleados
Where a.fecha between "2024-12-01" AND "2024-12-31" AND fecha_salida IS NULL;
```

4. Encontrar los trabajadores con asistencia registrada todo los dias habiles de una semana especifica

```sql   
SELECT ID_Empleados, nombre, apellido, CONT (a. fecha) AS dias_asistidos
From Empleados
Inner join asistencia a ON ID_Empleados = ID_Empleados
Where a.fecha between '2024-06-01' AND '2024-06-05'
Group BY ID_Empleados, nombre, apellido 
Having dias_asistidos = 5;
```
5. Mostrar los correos de todos los trabajadores que trabajan medio tiempo
   
```sql
SELECT ID_Empleados, nombre, apellido, correo_electronico
From Empleados
Where tipo_de_contrato = 'medio tiempo';
