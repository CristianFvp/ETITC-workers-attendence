# ETITC - Asistencia de Trabajadores U
---
- **Objetivos**
    - **Objetivo General**: Crear un sistema de base de datos para el control y registro de la asistencia de los trabjadores
      de una universidad, permitiendo gestionar de manera eficiente la informacion y generar reportes precisos.
      
    - **Objetivos Especificos**:
      - Almacenar la informacion de los trabajadores
      - Sistema de regsitro de entrada y salida, que permita el control en tiempo real
      - Poder generar consultas y reportes para verificar el cumplimiento
      - Facilitar la creacion de informes para el departamento que lo requiera
     

- **Planteamiento del Problema**:
   La asistencia de los trabajadores de una universidad es muy importante para garantizar el control de horarios y 
   productividad. Sin embargo, el uso de sistemas manuales o desactualizados puede generar errores en su registro, 
   resultando ineficiente en el seguimiento de la asistencia y la generación de reportes claros, afectando varias áreas 
   como, por ejemplo, recursos humanos, el pago de los trabajadores y retrasos en los procesos administrativos.
  
- Justificación
- Referencias
 


- Datos Iniciales
Tabla de dato


20x50

| id | nombre   | apellido  | materia     | horario     | cargo                       | edad | nivel_de_educacion | número_de_documento | género | dirección_de_vivienda    | sigue_estudiando |
|----|----------|-----------|-------------|-------------|-----------------------------|------|--------------------|---------------------|--------|--------------------------|------------------|
| 1  | Juan     | Pérez     | Matemáticas | 08:00-10:00 | Profesor                    | 45   | Doctorado          | 12345678            | Masc   | Av. Libertador 101       | No               |
| 2  | Ana      | Gómez     | Física      | 10:00-12:00 | Profesor                    | 38   | Maestría           | 23456789            | Fem    | Calle 2 #34              | No               |
| 3  | Luis     | Rodríguez | Química     | 12:00-14:00 | Profesor                    | 50   | Doctorado          | 34567890            | Masc   | Av. Los Olivos 76        | No               |
| 4  | Marta    | Martínez  | Historia    | 14:00-16:00 | Profesor                    | 42   | Licenciatura       | 45678901            | Fem    | Calle de la Luna 11      | No               |
| 5  | Carlos   | Lopez     | Literatura  | 16:00-18:00 | Profesor                    | 35   | Maestría           | 56789012            | Masc   | Av. San Martín 33        | No               |
| 6  | Sofía    | Jiménez   | Biología    | 08:00-10:00 | Profesor                    | 40   | Doctorado          | 67890123            | Fem    | Calle del Sol 21         | Sí               |
| 7  | Pedro    | Castro    | Geografía   | 10:00-12:00 | Profesor                    | 48   | Licenciatura       | 78901234            | Masc   | Av. de la Paz 88         | No               |
| 8  | Laura    | Suárez    | Arte        | 12:00-14:00 | Profesor                    | 29   | Maestría           | 89012345            | Fem    | Calle Real 45            | Sí               |
| 9  | Jorge    | Salazar   | Inglés      | 14:00-16:00 | Profesor                    | 54   | Doctorado          | 90123456            | Masc   | Av. de la República 56   | No               |
| 10 | Isabel   | Reyes     | Matemáticas | 16:00-18:00 | Profesor                    | 37   | Licenciatura       | 1234567             | Fem    | Calle del Mar 78         | Sí               |
| 11 | Antonio  | Herrera   | Física      | 08:00-10:00 | Profesor                    | 49   | Doctorado          | 12345679            | Masc   | Av. de la Libertad 90    | No               |
| 12 | Elena    | Rivera    | Química     | 10:00-12:00 | Profesor                    | 43   | Maestría           | 23456780            | Fem    | Calle Nueva 34           | No               |
| 13 | Manuel   | Ortiz     | Historia    | 12:00-14:00 | Profesor                    | 52   | Licenciatura       | 34567891            | Masc   | Av. del Norte 76         | Sí               |
| 14 | Claudia  | Mendoza   | Literatura  | 14:00-16:00 | Profesor                    | 33   | Maestría           | 45678902            | Fem    | Calle del Centro 12      | No               |
| 15 | Fernando | Romero    | Biología    | 16:00-18:00 | Profesor                    | 46   | Doctorado          | 56789013            | Masc   | Av. del Sur 89           | Sí               |
| 16 | Valeria  | Vargas    | Geografía   | 08:00-10:00 | Profesor                    | 31   | Licenciatura       | 67890124            | Fem    | Calle de la Primavera 67 | No               |
| 17 | Rafael   | Castro    | Arte        | 10:00-12:00 | Profesor                    | 39   | Maestría           | 78901235            | Masc   | Av. de la Cultura 23     | Sí               |
| 18 | Gabriela | Muñoz     | Inglés      | 12:00-14:00 | Profesor                    | 44   | Doctorado          | 89012346            | Fem    | Calle del Río 45         | No               |
| 19 | Oscar    | Navarro   | Matemáticas | 14:00-16:00 | Profesor                    | 51   | Licenciatura       | 90123457            | Masc   | Av. del Sol 90           | Sí               |
| 20 | Nora     | Salinas   | Física      | 16:00-18:00 | Profesor                    | 32   | Maestría           | 1234568             | Fem    | Calle del Lago 11        | No               |
| 21 | Javier   | Alvarez   | Química     | 08:00-10:00 | Profesor                    | 47   | Doctorado          | 12345680            | Masc   | Calle de la Estación 77  | Sí               |
| 22 | Mario    | González  | -           | 09:00-17:00 | Secretario Académico        | 41   | Licenciatura       | 34567892            | Masc   | Calle Mayor 12           | No               |
| 23 | Lucía    | Torres    | -           | 08:00-16:00 | Recepcionista               | 29   | Bachillerato       | 45678903            | Fem    | Av. Central 56           | Sí               |
| 24 | José     | Ramos     | -           | 07:00-15:00 | Personal de Limpieza        | 36   | Secundaria         | 56789014            | Masc   | Calle del Bosque 78      | No               |
| 25 | Carla    | Fernández | -           | 10:00-18:00 | Coordinadora de Eventos     | 43   | Maestría           | 67890125            | Fem    | Av. de las Flores 89     | No               |
| 26 | Andrés   | Morales   | -           | 09:00-17:00 | Técnico Informático         | 34   | Ingeniería         | 78901236            | Masc   | Calle 7 #45              | Sí               |
| 27 | Felipe   | Morales   | -           | 08:00-16:00 | Contador                    | 45   | Licenciatura       | 89012347            | Masc   | Av. Libertador 22        | No               |
| 28 | Patricia | Romero    | -           | 07:00-15:00 | Jefe de Recursos Humanos    | 50   | Maestría           | 90123458            | Fem    | Calle Jardines 89        | No               |
| 29 | Hugo     | Cabrera   | -           | 06:00-14:00 | Personal de Seguridad       | 38   | Secundaria         | 12345681            | Masc   | Calle de los Álamos 23   | No               |
| 30 | Daniela  | Ruiz      | -           | 09:00-17:00 | Asistente Administrativa    | 27   | Bachillerato       | 23456781            | Fem    | Av. de los Robles 45     | Sí               |
| 31 | Diego    | Paredes   | -           | 08:00-16:00 | Técnico de Mantenimiento    | 42   | Secundaria         | 34567893            | Masc   | Calle del Arco 67        | No               |
| 32 | Elena    | Gutierrez | -           | 07:00-15:00 | Coordinadora Académica      | 39   | Licenciatura       | 45678904            | Fem    | Av. del Norte 45         | No               |
| 33 | Sergio   | Peña      | -           | 08:00-16:00 | Bibliotecario               | 46   | Maestría           | 56789015            | Masc   | Calle de la Montaña 101  | No               |
| 34 | Laura    | Aguilar   | -           | 09:00-17:00 | Coordinadora de Bienestar   | 35   | Maestría           | 67890126            | Fem    | Av. de la Juventud 76    | No               |
| 35 | Pablo    | Vargas    | -           | 10:00-18:00 | Supervisor de Mantenimiento | 52   | Licenciatura       | 78901237            | Masc   | Calle de la Estrella 89  | No               |
| 36 | Susana   | Castro    | -           | 09:00-17:00 | Secretaria Administrativa   | 31   | Bachillerato       | 89012348            | Fem    | Av. del Sol 22           | Sí               |


