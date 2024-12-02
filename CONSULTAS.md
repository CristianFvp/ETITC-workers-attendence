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

3. 
