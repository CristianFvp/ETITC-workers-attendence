# ETITC - Asistencia de Trabajadores en la U
---

**Introducción**:

En la actualidad, el control manual de la asistencia en la universidad resulta ineficiente. 
Este proyecto propone desarrollar un sistema automatizado basado en una base de datos para 
registrar con precisión las entradas y salidas de los trabajadores, utilizando tecnologías  
de reconocimiento. El objetivo es mejorar la productividad, reducir 
errores y facilitar la generación de reportes en tiempo real, optimizando los procesos 
administrativos y beneficiando a toda la institución.


**Planteamiento del Problema**:

   La correcta asistencia de los trabajadores de una universidad es muy importante para garantizar el control de horarios y
   productividad. Sin embargo, el uso de sistemas manuales o desactualizados puede generar errores en su registro, 
   resultando ineficiente en el seguimiento de la asistencia y la generación de reportes claros, afectando varias áreas 
   como, por ejemplo, recursos humanos, el pago de los trabajadores y retrasos en los procesos administrativos.

**Planteamiento de la solución**:

  Se propone desarrollar un sistema automatizado de control de asistencia basado en la captura de huellas dactilares de los trabajadores. 
  Este sistema permitirá registrar de manera precisa la entrada y salida de cada empleado, proporcionando una verificación  segura y evitando el fraude o el mal uso del sistema. 
   
  
**Justificación**:

  Este proyecto es importante porque actualmente en la universidad, el control de la asistencia de los trabajadores se hace de
  manera manual. Esto puede causar problemas. Al crear un sistema de base de datos para registrar la asistencia, se podrá llevar un
  control más claro y eficiente de quién está cumpliendo con sus horarios. Además, será más fácil generar reportes y mantener
  todo en orden sin perder tiempo o cometer errores. Esto no solo ayudará a los trabajadores, sino también a la administración
  de la universidad haciendo que todo funcione de manera más rápida y organizada.

**Requerimientos de la solución al problema**

   - Requerimientos Funcionales:
     - Registro de Trabajadores
     - Control de Entradas y Salidas
     - Generación de Reportes
     - Consulta de Asistencia
     - Seguridad de Acceso

   - Requerimientos No Funcionales:
     - Escalabilidad
     - Facilidad de Uso
     - Compatibilidad}
     - Alertas y Notificaciones
    
- **Objetivos**
    - **Objetivo General**: Desarrollar un sistema automatizado de control de asistencia para los trabajadores de la universidad,
      utilizando tecnología de huella dactilar, que permita registrar de manera precisa las entradas y salidas del personal,
      proporcionando consultas en tiempo real y generando reportes automáticos que optimicen los procesos de seguimiento y control,
      mejorando la eficiencia y confiabilidad de la administración del recurso humano.
      
    - **Objetivos Especificos**:
      - Registrar y almacenar la informacion de los trabajadores de forma organizada.
      - Implementar un sistema de regsitro de entrada y salida, que permita el control en tiempo real.
      - Poder generar consultas y reportes para verificar el cumplimiento de los trabajadores.
      - Facilitar la creacion de informes para el departamento que lo requiera.
      - Evitar errores manuales en el registro de asistencia.
      - Proveer información en tiempo real para mejorar la toma de decisiones administrativas.
        
 Funcionalidades principales:
- Uso de tarjetas RFID, sistemas biométricos o reconocimiento facial para registrar la entrada y salida.
- Generación de reportes de asistencia diaria, semanal o mensual.
- Consulta en tiempo real: Permitir que los administradores y empleados revisen el estado de su asistencia.
  
Beneficios esperados:
- Reducción de errores humanos, El uso de un sistema automatizado evitará los errores que surgen de los métodos manuales.
- Ahorro de tiempo, Los reportes automatizados y el control de asistencia agilizarán los procesos administrativos.
- Mejora de la productividad, Al tener un control preciso del horario de los empleados, será más fácil identificar patrones y tomar decisiones.
- Mayor transparencia, Los empleados tendrán acceso a sus datos de asistencia, promoviendo la confianza y claridad.

 Tecnologías sugeridas:
   - Base de datos relacional, MySQL, PostgreSQL o SQL Server para el manejo de los datos de asistencia.
   - Interfaz de usuario, Un portal web o aplicación móvil donde los empleados puedan consultar su asistencia y los administradores 
     generen reportes.
   - Sistemas de control de asistencia, Uso de hardware como lectores de tarjetas RFID, sistemas biométricos o cámaras de 
     reconocimiento facial.

- **Posible división de tareas entre los miembros del equipo**
  
     - Diseño de base de datos:
        Encargados (Cristian vargas, Yeison Ruano).
     - Pruebas y documentacion:
        Encargados (Sofia Cobaleda).

- 


Referencias:
   - https://aws.amazon.com/es/what-is/database/
   - https://controllaboral.es/control-entrada-salida-personal/
   - https://hikvision.lat/productos/lector-biometrico-facial-hikvision-ds-k1t341amf.html
   - https://www.youtube.com/watch?v=MXpeVSPU_S0
   - (S/f-a). Researchgate.net. Recuperado el 12 de septiembre de 2024, de 
     https://www.researchgate.net/publication/358178607_Automated_
   - attendance_management_systems_systematic_literature_review
     ChatGPT. (s/f). Chatgpt.com. Recuperado el 13-14 de septiembre de 2024, de https://chatgpt.com/
     

- Datos Iniciales
Tabla de dato

| id | nombre   | apellido  | materia     | horario     | cargo                         | edad | nivel_de_educacion | número_de_documento | género | dirección_de_vivienda    | sigue_estudiando | años_experiencia | estado_civil | fecha_ingreso | salario | tipo_de_contrato | departamento          | teléfono   | correo_electronico       | especialidad              |
|----|----------|-----------|-------------|-------------|-------------------------------|------|--------------------|---------------------|--------|--------------------------|------------------|------------------|--------------|---------------|---------|------------------|-----------------------|------------|--------------------------|---------------------------|
| 1  | Juan     | Pérez     | Matemáticas | 08:00-10:00 | Profesor                      | 45   | Doctorado          | 12345678            | Masc   | Av. Libertador 101       | No               | 20               | Casado       | 15/2/2005     | $5,000  | Tiempo completo  | Ciencias Exactas      | 1234567890 | juan.perez@uni.edu       | Matemáticas Avanzadas     |
| 2  | Ana      | Gómez     | Física      | 10:00-12:00 | Profesor                      | 38   | Maestría           | 23456789            | Fem    | Calle 2 #34              | No               | 12               | Soltera      | 12/5/2011     | $4,200  | Medio tiempo     | Ciencias Exactas      | 2345678901 | ana.gomez@uni.edu        | Física Cuántica           |
| 3  | Luis     | Rodríguez | Química     | 12:00-14:00 | Profesor                      | 50   | Doctorado          | 34567890            | Masc   | Av. Los Olivos 76        | No               | 25               | Casado       | 3/9/1998      | $5,500  | Tiempo completo  | Ciencias Exactas      | 3456789012 | luis.rodriguez@uni.edu   | Química Orgánica          |
| 4  | Marta    | Martínez  | Historia    | 14:00-16:00 | Profesor                      | 42   | Licenciatura       | 45678901            | Fem    | Calle de la Luna 11      | No               | 18               | Divorciada   | 1/8/2002      | $3,800  | Medio tiempo     | Humanidades           | 4567890123 | marta.martinez@uni.edu   | Historia Medieval         |
| 5  | Carlos   | Lopez     | Literatura  | 16:00-18:00 | Profesor                      | 35   | Maestría           | 56789012            | Masc   | Av. San Martín 33        | No               | 10               | Soltero      | 14/4/2013     | $4,000  | Tiempo completo  | Humanidades           | 5678901234 | carlos.lopez@uni.edu     | Literatura Contemporánea  |
| 6  | Sofía    | Jiménez   | Biología    | 08:00-10:00 | Profesor                      | 40   | Doctorado          | 67890123            | Fem    | Calle del Sol 21         | Sí               | 15               | Casada       | 7/6/2008      | $5,200  | Medio tiempo     | Ciencias Naturales    | 6789012345 | sofia.jimenez@uni.edu    | Genética Molecular        |
| 7  | Pedro    | Castro    | Geografía   | 10:00-12:00 | Profesor                      | 48   | Licenciatura       | 78901234            | Masc   | Av. de la Paz 88         | No               | 22               | Casado       | 25/10/1999    | $4,800  | Tiempo completo  | Ciencias Sociales     | 7890123456 | pedro.castro@uni.edu     | Geografía Política        |
| 8  | Laura    | Suárez    | Arte        | 12:00-14:00 | Profesor                      | 29   | Maestría           | 89012345            | Fem    | Calle Real 45            | Sí               | 5                | Soltera      | 17/9/2017     | $3,600  | Medio tiempo     | Humanidades           | 8901234567 | laura.suarez@uni.edu     | Arte Moderno              |
| 9  | Jorge    | Salazar   | Inglés      | 14:00-16:00 | Profesor                      | 54   | Doctorado          | 90123456            | Masc   | Av. de la República 56   | No               | 28               | Casado       | 3/3/1995      | $5,700  | Tiempo completo  | Lenguas Extranjeras   | 9012345678 | jorge.salazar@uni.edu    | Literatura Inglesa        |
| 10 | Isabel   | Reyes     | Matemáticas | 16:00-18:00 | Profesor                      | 37   | Licenciatura       | 1234567             | Fem    | Calle del Mar 78         | Sí               | 9                | Soltera      | 21/7/2014     | $4,100  | Tiempo parcial   | Ciencias Exactas      | 123456789  | isabel.reyes@uni.edu     | Álgebra Lineal            |
| 11 | Antonio  | Herrera   | Física      | 08:00-10:00 | Profesor                      | 49   | Doctorado          | 12345679            | Masc   | Av. de la Libertad 90    | No               | 24               | Casado       | 10/6/1998     | $5,500  | Tiempo completo  | Ciencias Exactas      | 1123456789 | antonio.herrera@uni.edu  | Física de Partículas      |
| 12 | Elena    | Rivera    | Química     | 10:00-12:00 | Profesor                      | 43   | Maestría           | 23456780            | Fem    | Calle Nueva 34           | No               | 19               | Soltera      | 1/3/2003      | $4,300  | Medio tiempo     | Ciencias Exactas      | 2234567890 | elena.rivera@uni.edu     | Bioquímica                |
| 13 | Manuel   | Ortiz     | Historia    | 12:00-14:00 | Profesor                      | 52   | Licenciatura       | 34567891            | Masc   | Av. del Norte 76         | Sí               | 27               | Casado       | 7/9/1994      | $4,900  | Tiempo completo  | Humanidades           | 3345678901 | manuel.ortiz@uni.edu     | Historia Latinoamericana  |
| 14 | Claudia  | Mendoza   | Literatura  | 14:00-16:00 | Profesor                      | 33   | Maestría           | 45678902            | Fem    | Calle del Centro 12      | No               | 8                | Soltera      | 21/5/2014     | $4,100  | Medio tiempo     | Humanidades           | 4456789012 | claudia.mendoza@uni.edu  | Poesía Contemporánea      |
| 15 | Fernando | Romero    | Biología    | 16:00-18:00 | Profesor                      | 46   | Doctorado          | 56789013            | Masc   | Av. del Sur 89           | Sí               | 21               | Casado       | 17/11/1999    | $5,400  | Tiempo completo  | Ciencias Naturales    | 5567890123 | fernando.romero@uni.edu  | Biología Celular          |
| 16 | Valeria  | Vargas    | Geografía   | 08:00-10:00 | Profesor                      | 31   | Licenciatura       | 67890124            | Fem    | Calle de la Primavera 67 | No               | 6                | Soltera      | 12/4/2017     | $3,900  | Medio tiempo     | Ciencias Sociales     | 6678901234 | valeria.vargas@uni.edu   | Geografía Urbana          |
| 17 | Rafael   | Castro    | Arte        | 10:00-12:00 | Profesor                      | 39   | Maestría           | 78901235            | Masc   | Av. de la Cultura 23     | Sí               | 13               | Casado       | 1/2/2010      | $4,300  | Tiempo completo  | Humanidades           | 7789012345 | rafael.castro@uni.edu    | Escultura Moderna         |
| 18 | Gabriela | Muñoz     | Inglés      | 12:00-14:00 | Profesor                      | 44   | Doctorado          | 89012346            | Fem    | Calle del Río 45         | No               | 19               | Soltera      | 17/9/2003     | $4,800  | Medio tiempo     | Lenguas Extranjeras   | 8890123456 | gabriela.muñoz@uni.edu   | Lingüística Aplicada      |
| 19 | Oscar    | Navarro   | Matemáticas | 14:00-16:00 | Profesor                      | 51   | Licenciatura       | 90123457            | Masc   | Av. del Sol 90           | Sí               | 25               | Casado       | 20/11/1997    | $5,000  | Tiempo completo  | Ciencias Exactas      | 9012345679 | oscar.navarro@uni.edu    | Matemáticas Discretas     |
| 20 | Nora     | Salinas   | Física      | 16:00-18:00 | Profesor                      | 32   | Maestría           | 1234568             | Fem    | Calle del Lago 11        | No               | 8                | Soltera      | 17/8/2015     | $4,200  | Medio tiempo     | Ciencias Exactas      | 1234567899 | nora.salinas@uni.edu     | Física Nuclear            |
| 21 | Javier   | Alvarez   | Química     | 08:00-10:00 | Profesor                      | 47   | Doctorado          | 12345680            | Masc   | Calle de la Estación 77  | Sí               | 22               | Casado       | 5/3/2000      | $5,300  | Tiempo completo  | Ciencias Exactas      | 1345678901 | javier.alvarez@uni.edu   | Química Analítica         |
| 22 | Mario    | González  | -           | 09:00-17:00 | Secretario Académico          | 41   | Licenciatura       | 34567892            | Masc   | Calle Mayor 12           | No               | 16               | Casado       | 9/7/2006      | $3,800  | Tiempo completo  | Administración        | 2456789012 | mario.gonzalez@uni.edu   | Administración            |
| 23 | Lucía    | Torres    | -           | 08:00-16:00 | Recepcionista                 | 29   | Bachillerato       | 45678903            | Fem    | Av. Central 56           | Sí               | 5                | Soltera      | 21/10/2017    | $2,600  | Medio tiempo     | Administración        | 3567890123 | lucia.torres@uni.edu     | Atención al Público       |
| 24 | José     | Ramos     | -           | 07:00-15:00 | Personal de Limpieza          | 36   | Secundaria         | 56789014            | Masc   | Calle del Bosque 78      | No               | 10               | Casado       | 12/6/2012     | $2,200  | Tiempo completo  | Servicios Generales   | 4678901234 | jose.ramos@uni.edu       | Mantenimiento             |
| 25 | Carla    | Fernández | -           | 10:00-18:00 | Coordinadora de Eventos       | 43   | Maestría           | 67890125            | Fem    | Av. de las Flores 89     | No               | 12               | Soltera      | 4/5/2010      | $4,500  | Tiempo completo  | Relaciones Públicas   | 5789012345 | carla.fernandez@uni.edu  | Organización de Eventos   |
| 26 | Andrés   | Morales   | -           | 09:00-17:00 | Técnico Informático           | 34   | Ingeniería         | 78901236            | Masc   | Calle 7 #45              | Sí               | 9                | Soltero      | 8/9/2015      | $4,200  | Tiempo completo  | Soporte Técnico       | 6789012346 | andres.morales@uni.edu   | Redes y Sistemas          |
| 27 | Felipe   | Morales   | -           | 08:00-16:00 | Contador                      | 45   | Licenciatura       | 89012347            | Masc   | Av. Libertador 22        | No               | 15               | Casado       | 12/3/2008     | $3,900  | Tiempo completo  | Finanzas              | 7890123457 | felipe.morales@uni.edu   | Contabilidad General      |
| 28 | Patricia | Romero    | -           | 07:00-15:00 | Jefe de Recursos Humanos      | 50   | Maestría           | 90123458            | Fem    | Calle Jardines 89        | No               | 22               | Casada       | 1/5/2000      | $5,600  | Tiempo completo  | Recursos Humanos      | 8901234568 | patricia.romero@uni.edu  | Gestión de Personal       |
| 29 | Hugo     | Cabrera   | -           | 06:00-14:00 | Personal de Seguridad         | 38   | Secundaria         | 12345681            | Masc   | Calle de los Álamos 23   | No               | 12               | Soltero      | 3/4/2010      | $2,500  | Tiempo completo  | Seguridad             | 9012345679 | hugo.cabrera@uni.edu     | Vigilancia                |
| 30 | Daniela  | Ruiz      | -           | 09:00-17:00 | Asistente Administrativa      | 27   | Bachillerato       | 23456781            | Fem    | Av. de los Robles 45     | Sí               | 4                | Soltera      | 11/6/2019     | $2,800  | Medio tiempo     | Administración        | 1123456789 | daniela.ruiz@uni.edu     | Administración            |
| 31 | Diego    | Paredes   | -           | 08:00-16:00 | Técnico de Mantenimiento      | 42   | Secundaria         | 34567893            | Masc   | Calle del Arco 67        | No               | 18               | Casado       | 15/3/2005     | $3,200  | Tiempo completo  | Mantenimiento         | 2234567890 | diego.paredes@uni.edu    | Electricidad              |
| 32 | Elena    | Gutierrez | -           | 07:00-15:00 | Coordinadora Académica        | 39   | Licenciatura       | 45678904            | Fem    | Av. del Norte 45         | No               | 13               | Casada       | 18/7/2008     | $4,600  | Tiempo completo  | Administración        | 3345678901 | elena.gutierrez@uni.edu  | Gestión Académica         |
| 33 | Sergio   | Peña      | -           | 08:00-16:00 | Bibliotecario                 | 46   | Maestría           | 56789015            | Masc   | Calle de la Montaña 101  | No               | 15               | Casado       | 22/5/2009     | $3,900  | Tiempo completo  | Bibliotecas           | 4456789012 | sergio.pena@uni.edu      | Archivística              |
| 34 | Laura    | Aguilar   | -           | 09:00-17:00 | Coordinadora de Bienestar     | 35   | Maestría           | 67890126            | Fem    | Av. de la Juventud 76    | No               | 8                | Soltera      | 7/10/2015     | $4,300  | Tiempo completo  | Bienestar Estudiantil | 5567890123 | laura.aguilar@uni.edu    | Psicología Educativa      |
| 35 | Pablo    | Vargas    | -           | 10:00-18:00 | Supervisor de Mantenimiento   | 52   | Licenciatura       | 78901237            | Masc   | Calle de la Estrella 89  | No               | 25               | Casado       | 11/11/1996    | $4,600  | Tiempo completo  | Mantenimiento         | 6678901234 | pablo.vargas@uni.edu     | Gestión de Instalaciones  |
| 36 | Susana   | Castro    | -           | 09:00-17:00 | Secretaria Administrativa     | 31   | Bachillerato       | 89012348            | Fem    | Av. del Sol 22           | Sí               | 4                | Soltera      | 14/4/2018     | $2,700  | Medio tiempo     | Administración        | 7789012345 | susana.castro@uni.edu    | Administración            |
| 37 | Roberto  | Pérez     | -           | 07:00-15:00 | Conserje                      | 40   | Secundaria         | 99012349            | Masc   | Calle Los Álamos 56      | No               | 10               | Casado       | 12/5/2013     | $2,200  | Tiempo completo  | Servicios Generales   | 8890123456 | roberto.perez@uni.edu    | Mantenimiento             |
| 38 | Teresa   | Fernández | -           | 08:00-16:00 | Asistente de Laboratorio      | 32   | Licenciatura       | 10123450            | Fem    | Av. de los Pinos 12      | Sí               | 7                | Soltera      | 1/9/2016      | $3,000  | Tiempo completo  | Ciencias              | 9012345679 | teresa.fernandez@uni.edu | Bioquímica                |
| 39 | Ricardo  | Salinas   | -           | 09:00-17:00 | Técnico de Audiovisuales      | 35   | Ingeniería         | 11234551            | Masc   | Av. Central 34           | No               | 12               | Casado       | 5/6/2011      | $4,000  | Tiempo completo  | Audiovisuales         | 1012345679 | ricardo.salinas@uni.edu  | Tecnologías Audiovisuales |
| 40 | Beatriz  | Gómez     | -           | 07:00-15:00 | Secretaria de Decanato        | 45   | Bachillerato       | 22345652            | Fem    | Calle Nueva 78           | No               | 18               | Casada       | 15/3/2005     | $3,500  | Tiempo completo  | Administración        | 2234567890 | beatriz.gomez@uni.edu    | Gestión Administrativa    |
| 41 | Andrés   | Lozano    | -           | 09:00-17:00 | Ingeniero de Sistemas         | 38   | Ingeniería         | 33456753            | Masc   | Av. del Norte 12         | No               | 14               | Casado       | 8/7/2009      | $5,000  | Tiempo completo  | Sistemas              | 3345678901 | andres.lozano@uni.edu    | Desarrollo de Software    |
| 42 | Julia    | Vargas    | -           | 07:00-15:00 | Auxiliar de Biblioteca        | 28   | Licenciatura       | 44567854            | Fem    | Calle del Sol 34         | Sí               | 3                | Soltera      | 10/2/2021     | $2,900  | Medio tiempo     | Bibliotecas           | 4456789012 | julia.vargas@uni.edu     | Gestión Bibliotecaria     |
| 43 | Gonzalo  | Ramírez   | -           | 08:00-16:00 | Técnico de Mantenimiento      | 39   | Secundaria         | 55678955            | Masc   | Av. del Este 22          | No               | 13               | Casado       | 5/8/2010      | $3,200  | Tiempo completo  | Mantenimiento         | 5567890123 | gonzalo.ramirez@uni.edu  | Electricidad              |
| 44 | Marta    | Herrera   | -           | 09:00-17:00 | Jefa de Finanzas              | 52   | Maestría           | 66789056            | Fem    | Calle del Norte 45       | No               | 25               | Casada       | 17/11/1998    | $5,500  | Tiempo completo  | Finanzas              | 6678901234 | marta.herrera@uni.edu    | Contabilidad              |
| 45 | Jorge    | Castillo  | -           | 06:00-14:00 | Personal de Seguridad         | 37   | Secundaria         | 77890157            | Masc   | Av. de los Robles 23     | No               | 11               | Casado       | 10/4/2012     | $2,500  | Tiempo completo  | Seguridad             | 7789012345 | jorge.castillo@uni.edu   | Vigilancia                |
| 46 | Elena    | Ortega    | -           | 08:00-16:00 | Técnico de Laboratorio        | 34   | Ingeniería         | 88901258            | Fem    | Calle de la Estrella 89  | Sí               | 8                | Soltera      | 15/9/2015     | $4,000  | Tiempo completo  | Ciencias              | 8890123456 | elena.ortega@uni.edu     | Química Analítica         |
| 47 | Marcos   | Ruiz      | -           | 07:00-15:00 | Conserje                      | 42   | Secundaria         | 99012359            | Masc   | Av. de las Flores 12     | No               | 17               | Casado       | 5/2/2006      | $2,300  | Tiempo completo  | Servicios Generales   | 9901234567 | marcos.ruiz@uni.edu      | Mantenimiento             |
| 48 | Ana      | Morales   | -           | 08:00-16:00 | Secretaria Académica          | 36   | Licenciatura       | 10123460            | Fem    | Calle Real 45            | No               | 12               | Soltera      | 1/4/2011      | $3,800  | Tiempo completo  | Administración        | 1012345679 | ana.morales@uni.edu      | Gestión Administrativa    |
| 49 | Ricardo  | Suárez    | -           | 07:00-15:00 | Técnico de Audiovisuales      | 29   | Ingeniería         | 11234561            | Masc   | Av. del Norte 22         | Sí               | 6                | Soltero      | 7/3/2017      | $3,500  | Tiempo completo  | Audiovisuales         | 1123456789 | ricardo.suarez@uni.edu   | Tecnología Audiovisual    |
| 50 | Silvia   | López     | -           | 09:00-17:00 | Asistente de Recursos Humanos | 30   | Licenciatura       | 22345662            | Fem    | Calle de la Luna 56      | Sí               | 4                | Soltera      | 12/8/2019     | $3,200  | Medio tiempo     | Recursos Humanos      | 2234567890 | silvia.lopez@uni.edu     | Gestión de Personal       |

---
**Normalizacion**:

La primera tabla de datos la generamos pidiéndole a ChatGPT que la creara con ciertas condiciones que nosotros le indicamos. Con esta tabla como base, llevamos a cabo el proceso de normalización, que nos ayudó a organizar y estructurar mejor los datos. La idea principal de esta es reflejar información sobre algunos integrantes de la universidad y diseñar una base de datos que permitiera registrar y almacenar de forma clara el registro de entrada y salida de cada persona. 

**Primera Forma de Normalizacion**:

Nos enfocamos en eliminar aquellos datos que no eran atómicos, es decir aquellos que contenían más de un valor en una misma celda. También eliminamos la redundancia, asegurándonos de que cada dato tuviera su propio atributo o columna, sin duplicaciones innecesarias. Esto permitió que la tabla fuera más eficiente y fácil de entender, ya que cada valor estaba correctamente separado y no se perdía ninguna información.Nos aseguramos de que la tabla mantuviera la misma estructura y fuera igual de comprensible, para que la información siguiera siendo accesible y clara para su consulta.
( La tabla generada anteriormente ya contaba con la normalizacion)



**Segunda Forma de Normalizacion**:

Lo que hicimos fue separar la información que no estaba completamente relacionada con la clave primaria. En una tabla, organizamos todos los datos personales y aquellos directamente relacionados con los trabajadores, como su nombre, dirección y demás detalles. En otra tabla, dividimos la información relacionada con las materias y, además, establecimos una separación clara de los roles que tiene cada trabajador. 

| ID_Empleado |  nombre  |  apellido | edad | género |    dirección_de_vivienda   | estado_civil | número_de_documento | nivel_de_educacion | sigue_estudiando | años_experiencia |  teléfono  |    correo_electronico    |   horario   |   |
|:-----------:|:--------:|:---------:|:----:|:------:|:--------------------------:|:------------:|:-------------------:|:------------------:|:----------------:|:----------------:|:----------:|:------------------------:|:-----------:|---|
|     Emp1    |   Juan   |   Pérez   |  45  |  Masc  |    Av.   Libertador 101    |    Casado    |       12345678      |      Doctorado     |        No        |        20        | 1234567890 |    juan.perez@uni.edu    | 08:00-10:00 |   |
|     Emp2    |    Ana   |   Gómez   |  38  |   Fem  |        Calle   2 #34       |    Soltera   |       23456789      |      Maestría      |        No        |        12        | 2345678901 |     ana.gomez@uni.edu    | 10:00-12:00 |   |
|     Emp3    |   Luis   | Rodríguez |  50  |  Masc  |     Av.   Los Olivos 76    |    Casado    |       34567890      |      Doctorado     |        No        |        25        | 3456789012 |  luis.rodriguez@uni.edu  | 12:00-14:00 |   |
|     Emp4    |   Marta  |  Martínez |  42  |   Fem  |    Calle   de la Luna 11   |  Divorciada  |       45678901      |    Licenciatura    |        No        |        18        | 4567890123 |  marta.martinez@uni.edu  | 14:00-16:00 |   |
|     Emp5    |  Carlos  |   Lopez   |  35  |  Masc  |     Av.   San Martín 33    |    Soltero   |       56789012      |      Maestría      |        No        |        10        | 5678901234 |   carlos.lopez@uni.edu   | 16:00-18:00 |   |
|     Emp6    |   Sofía  |  Jiménez  |  40  |   Fem  |     Calle   del Sol 21     |    Casada    |       67890123      |      Doctorado     |        Sí        |        15        | 6789012345 |   sofia.jimenez@uni.edu  | 08:00-10:00 |   |
|     Emp7    |   Pedro  |   Castro  |  48  |  Masc  |     Av.   de la Paz 88     |    Casado    |       78901234      |    Licenciatura    |        No        |        22        | 7890123456 |   pedro.castro@uni.edu   | 10:00-12:00 |   |
|     Emp8    |   Laura  |   Suárez  |  29  |   Fem  |       Calle   Real 45      |    Soltera   |       89012345      |      Maestría      |        Sí        |         5        | 8901234567 |   laura.suarez@uni.edu   | 12:00-14:00 |   |
|     Emp9    |   Jorge  |  Salazar  |  54  |  Masc  |  Av.   de la República 56  |    Casado    |       90123456      |      Doctorado     |        No        |        28        | 9012345678 |   jorge.salazar@uni.edu  | 14:00-16:00 |   |
|    Emp10    |  Isabel  |   Reyes   |  37  |   Fem  |     Calle   del Mar 78     |    Soltera   |       1234567       |    Licenciatura    |        Sí        |         9        |  123456789 |   isabel.reyes@uni.edu   | 16:00-18:00 |   |
|    Emp11    |  Antonio |  Herrera  |  49  |  Masc  |   Av.   de la Libertad 90  |    Casado    |       12345679      |      Doctorado     |        No        |        24        | 1123456789 |  antonio.herrera@uni.edu | 08:00-10:00 |   |
|    Emp12    |   Elena  |   Rivera  |  43  |   Fem  |      Calle   Nueva 34      |    Soltera   |       23456780      |      Maestría      |        No        |        19        | 2234567890 |   elena.rivera@uni.edu   | 10:00-12:00 |   |
|    Emp13    |  Manuel  |   Ortiz   |  52  |  Masc  |     Av.   del Norte 76     |    Casado    |       34567891      |    Licenciatura    |        Sí        |        27        | 3345678901 |   manuel.ortiz@uni.edu   | 12:00-14:00 |   |
|    Emp14    |  Claudia |  Mendoza  |  33  |   Fem  |    Calle   del Centro 12   |    Soltera   |       45678902      |      Maestría      |        No        |         8        | 4456789012 |  claudia.mendoza@uni.edu | 14:00-16:00 |   |
|    Emp15    | Fernando |   Romero  |  46  |  Masc  |      Av.   del Sur 89      |    Casado    |       56789013      |      Doctorado     |        Sí        |        21        | 5567890123 |  fernando.romero@uni.edu | 16:00-18:00 |   |
|    Emp16    |  Valeria |   Vargas  |  31  |   Fem  | Calle   de la Primavera 67 |    Soltera   |       67890124      |    Licenciatura    |        No        |         6        | 6678901234 |  valeria.vargas@uni.edu  | 08:00-10:00 |   |
|    Emp17    |  Rafael  |   Castro  |  39  |  Masc  |   Av.   de la Cultura 23   |    Casado    |       78901235      |      Maestría      |        Sí        |        13        | 7789012345 |   rafael.castro@uni.edu  | 10:00-12:00 |   |
|    Emp18    | Gabriela |   Muñoz   |  44  |   Fem  |     Calle   del Río 45     |    Soltera   |       89012346      |      Doctorado     |        No        |        19        | 8890123456 |  gabriela.muñoz@uni.edu  | 12:00-14:00 |   |
|    Emp19    |   Oscar  |  Navarro  |  51  |  Masc  |      Av.   del Sol 90      |    Casado    |       90123457      |    Licenciatura    |        Sí        |        25        | 9012345679 |   oscar.navarro@uni.edu  | 14:00-16:00 |   |
|    Emp20    |   Nora   |  Salinas  |  32  |   Fem  |     Calle   del Lago 11    |    Soltera   |       1234568       |      Maestría      |        No        |         8        | 1234567899 |   nora.salinas@uni.edu   | 16:00-18:00 |   |
|    Emp21    |  Javier  |  Alvarez  |  47  |  Masc  |  Calle   de la Estación 77 |    Casado    |       12345680      |      Doctorado     |        Sí        |        22        | 1345678901 |  javier.alvarez@uni.edu  | 08:00-10:00 |   |
|    Emp22    |   Mario  |  González |  41  |  Masc  |      Calle   Mayor 12      |    Casado    |       34567892      |    Licenciatura    |        No        |        16        | 2456789012 |  mario.gonzalez@uni.edu  | 09:00-17:00 |   |
|    Emp23    |   Lucía  |   Torres  |  29  |   Fem  |      Av.   Central 56      |    Soltera   |       45678903      |    Bachillerato    |        Sí        |         5        | 3567890123 |   lucia.torres@uni.edu   | 08:00-16:00 |   |
|    Emp24    |   José   |   Ramos   |  36  |  Masc  |    Calle   del Bosque 78   |    Casado    |       56789014      |     Secundaria     |        No        |        10        | 4678901234 |    jose.ramos@uni.edu    | 07:00-15:00 |   |
|    Emp25    |   Carla  | Fernández |  43  |   Fem  |   Av.   de las Flores 89   |    Soltera   |       67890125      |      Maestría      |        No        |        12        | 5789012345 |  carla.fernandez@uni.edu | 10:00-18:00 |   |
|    Emp26    |  Andrés  |  Morales  |  34  |  Masc  |        Calle   7 #45       |    Soltero   |       78901236      |     Ingeniería     |        Sí        |         9        | 6789012346 |  andres.morales@uni.edu  | 09:00-17:00 |   |
|    Emp27    |  Felipe  |  Morales  |  45  |  Masc  |     Av.   Libertador 22    |    Casado    |       89012347      |    Licenciatura    |        No        |        15        | 7890123457 |  felipe.morales@uni.edu  | 08:00-16:00 |   |
|    Emp28    | Patricia |   Romero  |  50  |   Fem  |     Calle   Jardines 89    |    Casada    |       90123458      |      Maestría      |        No        |        22        | 8901234568 |  patricia.romero@uni.edu | 07:00-15:00 |   |
|    Emp29    |   Hugo   |  Cabrera  |  38  |  Masc  |  Calle   de los Álamos 23  |    Soltero   |       12345681      |     Secundaria     |        No        |        12        | 9012345679 |   hugo.cabrera@uni.edu   | 06:00-14:00 |   |
|    Emp30    |  Daniela |    Ruiz   |  27  |   Fem  |   Av.   de los Robles 45   |    Soltera   |       23456781      |    Bachillerato    |        Sí        |         4        | 1123456789 |   daniela.ruiz@uni.edu   | 09:00-17:00 |   |
|    Emp31    |   Diego  |  Paredes  |  42  |  Masc  |     Calle   del Arco 67    |    Casado    |       34567893      |     Secundaria     |        No        |        18        | 2234567890 |   diego.paredes@uni.edu  | 08:00-16:00 |   |
|    Emp32    |   Elena  | Gutierrez |  39  |   Fem  |     Av.   del Norte 45     |    Casada    |       45678904      |    Licenciatura    |        No        |        13        | 3345678901 |  elena.gutierrez@uni.edu | 07:00-15:00 |   |
|    Emp33    |  Sergio  |    Peña   |  46  |  Masc  |  Calle   de la Montaña 101 |    Casado    |       56789015      |      Maestría      |        No        |        15        | 4456789012 |    sergio.pena@uni.edu   | 08:00-16:00 |   |
|    Emp34    |   Laura  |  Aguilar  |  35  |   Fem  |   Av.   de la Juventud 76  |    Soltera   |       67890126      |      Maestría      |        No        |         8        | 5567890123 |   laura.aguilar@uni.edu  | 09:00-17:00 |   |
|    Emp35    |   Pablo  |   Vargas  |  52  |  Masc  |  Calle   de la Estrella 89 |    Casado    |       78901237      |    Licenciatura    |        No        |        25        | 6678901234 |   pablo.vargas@uni.edu   | 10:00-18:00 |   |
|    Emp36    |  Susana  |   Castro  |  31  |   Fem  |      Av.   del Sol 22      |    Soltera   |       89012348      |    Bachillerato    |        Sí        |         4        | 7789012345 |   susana.castro@uni.edu  | 09:00-17:00 |   |
|    Emp37    |  Roberto |   Pérez   |  40  |  Masc  |    Calle   Los Álamos 56   |    Casado    |       99012349      |     Secundaria     |        No        |        10        | 8890123456 |   roberto.perez@uni.edu  | 07:00-15:00 |   |
|    Emp38    |  Teresa  | Fernández |  32  |   Fem  |    Av.   de los Pinos 12   |    Soltera   |       10123450      |    Licenciatura    |        Sí        |         7        | 9012345679 | teresa.fernandez@uni.edu | 08:00-16:00 |   |
|    Emp39    |  Ricardo |  Salinas  |  35  |  Masc  |      Av.   Central 34      |    Casado    |       11234551      |     Ingeniería     |        No        |        12        | 1012345679 |  ricardo.salinas@uni.edu | 09:00-17:00 |   |
|    Emp40    |  Beatriz |   Gómez   |  45  |   Fem  |      Calle   Nueva 78      |    Casada    |       22345652      |    Bachillerato    |        No        |        18        | 2234567890 |   beatriz.gomez@uni.edu  | 07:00-15:00 |   |
|    Emp41    |  Andrés  |   Lozano  |  38  |  Masc  |     Av.   del Norte 12     |    Casado    |       33456753      |     Ingeniería     |        No        |        14        | 3345678901 |   andres.lozano@uni.edu  | 09:00-17:00 |   |
|    Emp42    |   Julia  |   Vargas  |  28  |   Fem  |     Calle   del Sol 34     |    Soltera   |       44567854      |    Licenciatura    |        Sí        |         3        | 4456789012 |   julia.vargas@uni.edu   | 07:00-15:00 |   |
|    Emp43    |  Gonzalo |  Ramírez  |  39  |  Masc  |      Av.   del Este 22     |    Casado    |       55678955      |     Secundaria     |        No        |        13        | 5567890123 |  gonzalo.ramirez@uni.edu | 08:00-16:00 |   |
|    Emp44    |   Marta  |  Herrera  |  52  |   Fem  |    Calle   del Norte 45    |    Casada    |       66789056      |      Maestría      |        No        |        25        | 6678901234 |   marta.herrera@uni.edu  | 09:00-17:00 |   |
|    Emp45    |   Jorge  |  Castillo |  37  |  Masc  |   Av.   de los Robles 23   |    Casado    |       77890157      |     Secundaria     |        No        |        11        | 7789012345 |  jorge.castillo@uni.edu  | 06:00-14:00 |   |
|    Emp46    |   Elena  |   Ortega  |  34  |   Fem  |  Calle   de la Estrella 89 |    Soltera   |       88901258      |     Ingeniería     |        Sí        |         8        | 8890123456 |   elena.ortega@uni.edu   | 08:00-16:00 |   |
|    Emp47    |  Marcos  |    Ruiz   |  42  |  Masc  |   Av.   de las Flores 12   |    Casado    |       99012359      |     Secundaria     |        No        |        17        | 9901234567 |    marcos.ruiz@uni.edu   | 07:00-15:00 |   |
|    Emp48    |    Ana   |  Morales  |  36  |   Fem  |       Calle   Real 45      |    Soltera   |       10123460      |    Licenciatura    |        No        |        12        | 1012345679 |    ana.morales@uni.edu   | 08:00-16:00 |   |
|    Emp49    |  Ricardo |   Suárez  |  29  |  Masc  |     Av.   del Norte 22     |    Soltero   |       11234561      |     Ingeniería     |        Sí        |         6        | 1123456789 |  ricardo.suarez@uni.edu  | 07:00-15:00 |   |
|    Emp50    |  Silvia  |   López   |  30  |   Fem  |    Calle   de la Luna 56   |    Soltera   |       22345662      |    Licenciatura    |        Sí        |         4        | 2234567890 |   silvia.lopez@uni.edu   | 09:00-17:00 |   |

| ID_Materia |   materia   |   horario   |        especialidad        |
|:----------:|:-----------:|:-----------:|:--------------------------:|
| Asig1      | Matemáticas | 08:00-10:00 |   Matemáticas   Avanzadas  |
| Asig2      |    Física   | 10:00-12:00 |      Física   Cuántica     |
| Asig3      |   Química   | 12:00-14:00 |     Química   Orgánica     |
| Asig4      |   Historia  | 14:00-16:00 |     Historia   Medieval    |
| Asig5      |  Literatura | 16:00-18:00 | Literatura   Contemporánea |
| Asig6      |   Biología  | 08:00-10:00 |    Genética   Molecular    |
| Asig7      |  Geografía  | 10:00-12:00 |    Geografía   Política    |
| Asig8      |     Arte    | 12:00-14:00 |       Arte   Moderno       |
| Asig9      |    Inglés   | 14:00-16:00 |    Literatura   Inglesa    |
| Asig10     | Matemáticas | 16:00-18:00 |      Álgebra   Lineal      |
| Asig11     |    Física   | 08:00-10:00 |   Física   de Partículas   |
| Asig12     |   Química   | 10:00-12:00 |         Bioquímica         |
| Asig13     |   Historia  | 12:00-14:00 | Historia   Latinoamericana |
| Asig14     |  Literatura | 14:00-16:00 |   Poesía   Contemporánea   |
| Asig15     |   Biología  | 16:00-18:00 |     Biología   Celular     |
| Asig16     |  Geografía  | 08:00-10:00 |     Geografía   Urbana     |
| Asig17     |     Arte    | 10:00-12:00 |     Escultura   Moderna    |
| Asig18     |    Inglés   | 12:00-14:00 |   Lingüística   Aplicada   |
| Asig19     | Matemáticas | 14:00-16:00 |   Matemáticas   Discretas  |
| Asig20     |    Física   | 16:00-18:00 |      Física   Nuclear      |
| Asig21     |   Química   | 08:00-10:00 |     Química   Analítica    |

**Tercera Forma de Normalizacion**:

El objetivo fue eliminar cualquier dependencia transitiva, es decir, asegurarnos de que no hubiera atributos que dependieran de otros atributos no clave. Para lograr esto, se crearon tres tablas principales. La primera tabla incluye los roles de los trabajadores, como profesores, administradores y personal de aseo general, lo cual permite una gestión más clara y separada de los diferentes tipos de personal. La segunda tabla contiene la información específica de cada trabajador, como sus datos personales (nombre, dirección, etc.), y la tercera tabla organiza la información relacionada con las materias, asignando a cada una su respectiva clave primaria. Estas tablas están correctamente relacionadas entre sí mediante claves foráneas, lo que asegura una estructura más eficiente y libre de redundancias. Con este paso, conseguimos una base de datos más normalizada, organizada y fácil de mantener.

**Informacion Empleados**
| ID_Empleado |  nombre  |  apellido | edad | género |    dirección_de_vivienda   | estado_civil | número_de_documento |  teléfono  |    correo_electronico    |
|:-----------:|:--------:|:---------:|:----:|:------:|:--------------------------:|:------------:|:-------------------:|:----------:|:------------------------:|
|     Emp1    |   Juan   |   Pérez   |  45  |  Masc  |    Av.   Libertador 101    |    Casado    |       12345678      | 1234567890 |    juan.perez@uni.edu    |
|     Emp2    |    Ana   |   Gómez   |  38  |   Fem  |        Calle   2 #34       |    Soltera   |       23456789      | 2345678901 |     ana.gomez@uni.edu    |
|     Emp3    |   Luis   | Rodríguez |  50  |  Masc  |     Av.   Los Olivos 76    |    Casado    |       34567890      | 3456789012 |  luis.rodriguez@uni.edu  |
|     Emp4    |   Marta  |  Martínez |  42  |   Fem  |    Calle   de la Luna 11   |  Divorciada  |       45678901      | 4567890123 |  marta.martinez@uni.edu  |
|     Emp5    |  Carlos  |   Lopez   |  35  |  Masc  |     Av.   San Martín 33    |    Soltero   |       56789012      | 5678901234 |   carlos.lopez@uni.edu   |
|     Emp6    |   Sofía  |  Jiménez  |  40  |   Fem  |     Calle   del Sol 21     |    Casada    |       67890123      | 6789012345 |   sofia.jimenez@uni.edu  |
|     Emp7    |   Pedro  |   Castro  |  48  |  Masc  |     Av.   de la Paz 88     |    Casado    |       78901234      | 7890123456 |   pedro.castro@uni.edu   |
|     Emp8    |   Laura  |   Suárez  |  29  |   Fem  |       Calle   Real 45      |    Soltera   |       89012345      | 8901234567 |   laura.suarez@uni.edu   |
|     Emp9    |   Jorge  |  Salazar  |  54  |  Masc  |  Av.   de la República 56  |    Casado    |       90123456      | 9012345678 |   jorge.salazar@uni.edu  |
|    Emp10    |  Isabel  |   Reyes   |  37  |   Fem  |     Calle   del Mar 78     |    Soltera   |       1234567       |  123456789 |   isabel.reyes@uni.edu   |
|    Emp11    |  Antonio |  Herrera  |  49  |  Masc  |   Av.   de la Libertad 90  |    Casado    |       12345679      | 1123456789 |  antonio.herrera@uni.edu |
|    Emp12    |   Elena  |   Rivera  |  43  |   Fem  |      Calle   Nueva 34      |    Soltera   |       23456780      | 2234567890 |   elena.rivera@uni.edu   |
|    Emp13    |  Manuel  |   Ortiz   |  52  |  Masc  |     Av.   del Norte 76     |    Casado    |       34567891      | 3345678901 |   manuel.ortiz@uni.edu   |
|    Emp14    |  Claudia |  Mendoza  |  33  |   Fem  |    Calle   del Centro 12   |    Soltera   |       45678902      | 4456789012 |  claudia.mendoza@uni.edu |
|    Emp15    | Fernando |   Romero  |  46  |  Masc  |      Av.   del Sur 89      |    Casado    |       56789013      | 5567890123 |  fernando.romero@uni.edu |
|    Emp16    |  Valeria |   Vargas  |  31  |   Fem  | Calle   de la Primavera 67 |    Soltera   |       67890124      | 6678901234 |  valeria.vargas@uni.edu  |
|    Emp17    |  Rafael  |   Castro  |  39  |  Masc  |   Av.   de la Cultura 23   |    Casado    |       78901235      | 7789012345 |   rafael.castro@uni.edu  |
|    Emp18    | Gabriela |   Muñoz   |  44  |   Fem  |     Calle   del Río 45     |    Soltera   |       89012346      | 8890123456 |  gabriela.muñoz@uni.edu  |
|    Emp19    |   Oscar  |  Navarro  |  51  |  Masc  |      Av.   del Sol 90      |    Casado    |       90123457      | 9012345679 |   oscar.navarro@uni.edu  |
|    Emp20    |   Nora   |  Salinas  |  32  |   Fem  |     Calle   del Lago 11    |    Soltera   |       1234568       | 1234567899 |   nora.salinas@uni.edu   |
|    Emp21    |  Javier  |  Alvarez  |  47  |  Masc  |  Calle   de la Estación 77 |    Casado    |       12345680      | 1345678901 |  javier.alvarez@uni.edu  |
|    Emp22    |   Mario  |  González |  41  |  Masc  |      Calle   Mayor 12      |    Casado    |       34567892      | 2456789012 |  mario.gonzalez@uni.edu  |
|    Emp23    |   Lucía  |   Torres  |  29  |   Fem  |      Av.   Central 56      |    Soltera   |       45678903      | 3567890123 |   lucia.torres@uni.edu   |
|    Emp24    |   José   |   Ramos   |  36  |  Masc  |    Calle   del Bosque 78   |    Casado    |       56789014      | 4678901234 |    jose.ramos@uni.edu    |
|    Emp25    |   Carla  | Fernández |  43  |   Fem  |   Av.   de las Flores 89   |    Soltera   |       67890125      | 5789012345 |  carla.fernandez@uni.edu |
|    Emp26    |  Andrés  |  Morales  |  34  |  Masc  |        Calle   7 #45       |    Soltero   |       78901236      | 6789012346 |  andres.morales@uni.edu  |
|    Emp27    |  Felipe  |  Morales  |  45  |  Masc  |     Av.   Libertador 22    |    Casado    |       89012347      | 7890123457 |  felipe.morales@uni.edu  |
|    Emp28    | Patricia |   Romero  |  50  |   Fem  |     Calle   Jardines 89    |    Casada    |       90123458      | 8901234568 |  patricia.romero@uni.edu |
|    Emp29    |   Hugo   |  Cabrera  |  38  |  Masc  |  Calle   de los Álamos 23  |    Soltero   |       12345681      | 9012345679 |   hugo.cabrera@uni.edu   |
|    Emp30    |  Daniela |    Ruiz   |  27  |   Fem  |   Av.   de los Robles 45   |    Soltera   |       23456781      | 1123456789 |   daniela.ruiz@uni.edu   |
|    Emp31    |   Diego  |  Paredes  |  42  |  Masc  |     Calle   del Arco 67    |    Casado    |       34567893      | 2234567890 |   diego.paredes@uni.edu  |
|    Emp32    |   Elena  | Gutierrez |  39  |   Fem  |     Av.   del Norte 45     |    Casada    |       45678904      | 3345678901 |  elena.gutierrez@uni.edu |
|    Emp33    |  Sergio  |    Peña   |  46  |  Masc  |  Calle   de la Montaña 101 |    Casado    |       56789015      | 4456789012 |    sergio.pena@uni.edu   |
|    Emp34    |   Laura  |  Aguilar  |  35  |   Fem  |   Av.   de la Juventud 76  |    Soltera   |       67890126      | 5567890123 |   laura.aguilar@uni.edu  |
|    Emp35    |   Pablo  |   Vargas  |  52  |  Masc  |  Calle   de la Estrella 89 |    Casado    |       78901237      | 6678901234 |   pablo.vargas@uni.edu   |
|    Emp36    |  Susana  |   Castro  |  31  |   Fem  |      Av.   del Sol 22      |    Soltera   |       89012348      | 7789012345 |   susana.castro@uni.edu  |
|    Emp37    |  Roberto |   Pérez   |  40  |  Masc  |    Calle   Los Álamos 56   |    Casado    |       99012349      | 8890123456 |   roberto.perez@uni.edu  |
|    Emp38    |  Teresa  | Fernández |  32  |   Fem  |    Av.   de los Pinos 12   |    Soltera   |       10123450      | 9012345679 | teresa.fernandez@uni.edu |
|    Emp39    |  Ricardo |  Salinas  |  35  |  Masc  |      Av.   Central 34      |    Casado    |       11234551      | 1012345679 |  ricardo.salinas@uni.edu |
|    Emp40    |  Beatriz |   Gómez   |  45  |   Fem  |      Calle   Nueva 78      |    Casada    |       22345652      | 2234567890 |   beatriz.gomez@uni.edu  |
|    Emp41    |  Andrés  |   Lozano  |  38  |  Masc  |     Av.   del Norte 12     |    Casado    |       33456753      | 3345678901 |   andres.lozano@uni.edu  |
|    Emp42    |   Julia  |   Vargas  |  28  |   Fem  |     Calle   del Sol 34     |    Soltera   |       44567854      | 4456789012 |   julia.vargas@uni.edu   |
|    Emp43    |  Gonzalo |  Ramírez  |  39  |  Masc  |      Av.   del Este 22     |    Casado    |       55678955      | 5567890123 |  gonzalo.ramirez@uni.edu |
|    Emp44    |   Marta  |  Herrera  |  52  |   Fem  |    Calle   del Norte 45    |    Casada    |       66789056      | 6678901234 |   marta.herrera@uni.edu  |
|    Emp45    |   Jorge  |  Castillo |  37  |  Masc  |   Av.   de los Robles 23   |    Casado    |       77890157      | 7789012345 |  jorge.castillo@uni.edu  |
|    Emp46    |   Elena  |   Ortega  |  34  |   Fem  |  Calle   de la Estrella 89 |    Soltera   |       88901258      | 8890123456 |   elena.ortega@uni.edu   |
|    Emp47    |  Marcos  |    Ruiz   |  42  |  Masc  |   Av.   de las Flores 12   |    Casado    |       99012359      | 9901234567 |    marcos.ruiz@uni.edu   |
|    Emp48    |    Ana   |  Morales  |  36  |   Fem  |       Calle   Real 45      |    Soltera   |       10123460      | 1012345679 |    ana.morales@uni.edu   |
|    Emp49    |  Ricardo |   Suárez  |  29  |  Masc  |     Av.   del Norte 22     |    Soltero   |       11234561      | 1123456789 |  ricardo.suarez@uni.edu  |
|    Emp50    |  Silvia  |   López   |  30  |   Fem  |    Calle   de la Luna 56   |    Soltera   |       22345662      | 2234567890 |   silvia.lopez@uni.edu   |

**Datos Profesores**

| ID_Profesores | ID_Empleado |   materia   |   horario   |   cargo  | nivel_de_educacion | sigue_estudiando | años_experiencia | fecha_ingreso |  salario |  tipo_de_contrato |      departamento     |  teléfono  |    correo_electronico   |        especialidad        |
|:-------------:|:-----------:|:-----------:|:-----------:|:--------:|:------------------:|:----------------:|:----------------:|:-------------:|:--------:|:-----------------:|:---------------------:|:----------:|:-----------------------:|:--------------------------:|
|     Prof1     |     Emp1    | Matemáticas | 08:00-10:00 | Profesor |      Doctorado     |        No        |        20        |   15/02/2005  | $   5,00 | Tiempo   completo |   Ciencias   Exactas  | 1234567890 |    juan.perez@uni.edu   |   Matemáticas   Avanzadas  |
|     Prof2     |     Emp2    |    Física   | 10:00-12:00 | Profesor |      Maestría      |        No        |        12        |   12/05/2011  | $   4,20 |   Medio   tiempo  |   Ciencias   Exactas  | 2345678901 |    ana.gomez@uni.edu    |      Física   Cuántica     |
|     Prof3     |     Emp3    |   Química   | 12:00-14:00 | Profesor |      Doctorado     |        No        |        25        |   3/09/1998   | $   5,50 | Tiempo   completo |   Ciencias   Exactas  | 3456789012 |  luis.rodriguez@uni.edu |     Química   Orgánica     |
|     Prof4     |     Emp4    |   Historia  | 14:00-16:00 | Profesor |    Licenciatura    |        No        |        18        |   1/08/2002   | $   3,80 |   Medio   tiempo  |      Humanidades      | 4567890123 |  marta.martinez@uni.edu |     Historia   Medieval    |
|     Prof5     |     Emp5    |  Literatura | 16:00-18:00 | Profesor |      Maestría      |        No        |        10        |   14/04/2013  | $   4,00 | Tiempo   completo |      Humanidades      | 5678901234 |   carlos.lopez@uni.edu  | Literatura   Contemporánea |
|     Prof6     |     Emp6    |   Biología  | 08:00-10:00 | Profesor |      Doctorado     |        Sí        |        15        |   7/06/2008   | $   5,20 |   Medio   tiempo  |  Ciencias   Naturales | 6789012345 |  sofia.jimenez@uni.edu  |    Genética   Molecular    |
|     Prof7     |     Emp7    |  Geografía  | 10:00-12:00 | Profesor |    Licenciatura    |        No        |        22        |   25/10/1999  | $   4,80 | Tiempo   completo |  Ciencias   Sociales  | 7890123456 |   pedro.castro@uni.edu  |    Geografía   Política    |
|     Prof8     |     Emp8    |     Arte    | 12:00-14:00 | Profesor |      Maestría      |        Sí        |         5        |   17/09/2017  | $   3,60 |   Medio   tiempo  |      Humanidades      | 8901234567 |   laura.suarez@uni.edu  |       Arte   Moderno       |
|     Prof9     |     Emp9    |    Inglés   | 14:00-16:00 | Profesor |      Doctorado     |        No        |        28        |   3/03/1995   | $   5,70 | Tiempo   completo | Lenguas   Extranjeras | 9012345678 |  jorge.salazar@uni.edu  |    Literatura   Inglesa    |
|     Prof10    |    Emp10    | Matemáticas | 16:00-18:00 | Profesor |    Licenciatura    |        Sí        |         9        |   21/07/2014  | $   4,10 |  Tiempo   parcial |   Ciencias   Exactas  |  123456789 |   isabel.reyes@uni.edu  |      Álgebra   Lineal      |
|     Prof11    |    Emp11    |    Física   | 08:00-10:00 | Profesor |      Doctorado     |        No        |        24        |   10/06/1998  | $   5,50 | Tiempo   completo |   Ciencias   Exactas  | 1123456789 | antonio.herrera@uni.edu |   Física   de Partículas   |
|     Prof12    |    Emp12    |   Química   | 10:00-12:00 | Profesor |      Maestría      |        No        |        19        |   1/03/2003   | $   4,30 |   Medio   tiempo  |   Ciencias   Exactas  | 2234567890 |   elena.rivera@uni.edu  |         Bioquímica         |
|     Prof13    |    Emp13    |   Historia  | 12:00-14:00 | Profesor |    Licenciatura    |        Sí        |        27        |   7/09/1994   | $   4,90 | Tiempo   completo |      Humanidades      | 3345678901 |   manuel.ortiz@uni.edu  | Historia   Latinoamericana |
|     Prof14    |    Emp14    |  Literatura | 14:00-16:00 | Profesor |      Maestría      |        No        |         8        |   21/05/2014  | $   4,10 |   Medio   tiempo  |      Humanidades      | 4456789012 | claudia.mendoza@uni.edu |   Poesía   Contemporánea   |
|     Prof15    |    Emp15    |   Biología  | 16:00-18:00 | Profesor |      Doctorado     |        Sí        |        21        |   17/11/1999  | $   5,40 | Tiempo   completo |  Ciencias   Naturales | 5567890123 | fernando.romero@uni.edu |     Biología   Celular     |
|     Prof16    |    Emp16    |  Geografía  | 08:00-10:00 | Profesor |    Licenciatura    |        No        |         6        |   12/04/2017  | $   3,90 |   Medio   tiempo  |  Ciencias   Sociales  | 6678901234 |  valeria.vargas@uni.edu |     Geografía   Urbana     |
|     Prof17    |    Emp17    |     Arte    | 10:00-12:00 | Profesor |      Maestría      |        Sí        |        13        |   1/02/2010   | $   4,30 | Tiempo   completo |      Humanidades      | 7789012345 |  rafael.castro@uni.edu  |     Escultura   Moderna    |
|     Prof18    |    Emp18    |    Inglés   | 12:00-14:00 | Profesor |      Doctorado     |        No        |        19        |   17/09/2003  | $   4,80 |   Medio   tiempo  | Lenguas   Extranjeras | 8890123456 |  gabriela.muñoz@uni.edu |   Lingüística   Aplicada   |
|     Prof19    |    Emp19    | Matemáticas | 14:00-16:00 | Profesor |    Licenciatura    |        Sí        |        25        |   20/11/1997  | $   5,00 | Tiempo   completo |   Ciencias   Exactas  | 9012345679 |  oscar.navarro@uni.edu  |   Matemáticas   Discretas  |
|     Prof20    |    Emp20    |    Física   | 16:00-18:00 | Profesor |      Maestría      |        No        |         8        |   17/08/2015  | $   4,20 |   Medio   tiempo  |   Ciencias   Exactas  | 1234567899 |   nora.salinas@uni.edu  |      Física   Nuclear      |
|     Prof21    |    Emp21    |   Química   | 08:00-10:00 | Profesor |      Doctorado     |        Sí        |        22        |   5/03/2000   | $   5,30 | Tiempo   completo |   Ciencias   Exactas  | 1345678901 |  javier.alvarez@uni.edu |     Química   Analítica    |

**Datos Administrativos**
| ID_Administrativo | ID_Empleado |   horario   |              cargo              | nivel_de_educacion | sigue_estudiando | años_experiencia | estado_civil | fecha_ingreso |  salario |  tipo_de_contrato |       departamento      |  teléfono  |    correo_electronico    |         especialidad        |
|:-----------------:|:-----------:|:-----------:|:-------------------------------:|:------------------:|:----------------:|:----------------:|:------------:|:-------------:|:--------:|:-----------------:|:-----------------------:|:----------:|:------------------------:|:---------------------------:|
|       Admin1      |    Emp22    | 09:00-17:00 |      Secretario   Académico     |    Licenciatura    |        No        |        16        |    Casado    |   9/07/2006   | $   3,80 | Tiempo   completo |      Administración     | 2456789012 |  mario.gonzalez@uni.edu  |        Administración       |
|       Admin2      |    Emp23    | 08:00-16:00 |          Recepcionista          |    Bachillerato    |        Sí        |         5        |    Soltera   |   21/10/2017  | $   2,60 |   Medio   tiempo  |      Administración     | 3567890123 |   lucia.torres@uni.edu   |    Atención   al Público    |
|       Admin3      |    Emp25    | 10:00-18:00 |    Coordinadora   de Eventos    |      Maestría      |        No        |        12        |    Soltera   |   4/05/2010   | $   4,50 | Tiempo   completo |  Relaciones   Públicas  | 5789012345 |  carla.fernandez@uni.edu |  Organización   de Eventos  |
|       Admin4      |    Emp26    | 09:00-17:00 |      Técnico   Informático      |     Ingeniería     |        Sí        |         9        |    Soltero   |   8/09/2015   | $   4,20 | Tiempo   completo |    Soporte   Técnico    | 6789012346 |  andres.morales@uni.edu  |      Redes   y Sistemas     |
|       Admin5      |    Emp27    | 08:00-16:00 |             Contador            |    Licenciatura    |        No        |        15        |    Casado    |   12/03/2008  | $   3,90 | Tiempo   completo |         Finanzas        | 7890123457 |  felipe.morales@uni.edu  |    Contabilidad   General   |
|       Admin6      |    Emp28    | 07:00-15:00 |    Jefe   de Recursos Humanos   |      Maestría      |        No        |        22        |    Casada    |   1/05/2000   | $   5,60 | Tiempo   completo |    Recursos   Humanos   | 8901234568 |  patricia.romero@uni.edu |    Gestión   de Personal    |
|       Admin7      |    Emp29    | 06:00-14:00 |     Personal   de Seguridad     |     Secundaria     |        No        |        12        |    Soltero   |   3/04/2010   | $   2,50 | Tiempo   completo |        Seguridad        | 9012345679 |   hugo.cabrera@uni.edu   |          Vigilancia         |
|       Admin8      |    Emp30    | 09:00-17:00 |    Asistente   Administrativa   |    Bachillerato    |        Sí        |         4        |    Soltera   |   11/06/2019  | $   2,80 |   Medio   tiempo  |      Administración     | 1123456789 |   daniela.ruiz@uni.edu   |        Administración       |
|       Admin9      |    Emp31    | 08:00-16:00 |    Técnico   de Mantenimiento   |     Secundaria     |        No        |        18        |    Casado    |   15/03/2005  | $   3,20 | Tiempo   completo |      Mantenimiento      | 2234567890 |   diego.paredes@uni.edu  |         Electricidad        |
|      Admin10      |    Emp32    | 07:00-15:00 |     Coordinadora   Académica    |    Licenciatura    |        No        |        13        |    Casada    |   18/07/2008  | $   4,60 | Tiempo   completo |      Administración     | 3345678901 |  elena.gutierrez@uni.edu |     Gestión   Académica     |
|      Admin11      |    Emp33    | 08:00-16:00 |          Bibliotecario          |      Maestría      |        No        |        15        |    Casado    |   22/05/2009  | $   3,90 | Tiempo   completo |       Bibliotecas       | 4456789012 |    sergio.pena@uni.edu   |         Archivística        |
|      Admin12      |    Emp34    | 09:00-17:00 |   Coordinadora   de Bienestar   |      Maestría      |        No        |         8        |    Soltera   |   7/10/2015   | $   4,30 | Tiempo   completo | Bienestar   Estudiantil | 5567890123 |   laura.aguilar@uni.edu  |    Psicología   Educativa   |
|      Admin13      |    Emp35    | 10:00-18:00 |  Supervisor   de Mantenimiento  |    Licenciatura    |        No        |        25        |    Casado    |   11/11/1996  | $   4,60 | Tiempo   completo |      Mantenimiento      | 6678901234 |   pablo.vargas@uni.edu   |  Gestión   de Instalaciones |
|      Admin14      |    Emp36    | 09:00-17:00 |   Secretaria   Administrativa   |    Bachillerato    |        Sí        |         4        |    Soltera   |   14/04/2018  | $   2,70 |   Medio   tiempo  |      Administración     | 7789012345 |   susana.castro@uni.edu  |        Administración       |
|      Admin15      |    Emp38    | 08:00-16:00 |    Asistente   de Laboratorio   |    Licenciatura    |        Sí        |         7        |    Soltera   |   1/09/2016   | $   3,00 | Tiempo   completo |         Ciencias        | 9012345679 | teresa.fernandez@uni.edu |          Bioquímica         |
|      Admin16      |    Emp39    | 09:00-17:00 |    Técnico   de Audiovisuales   |     Ingeniería     |        No        |        12        |    Casado    |   5/06/2011   | $   4,00 | Tiempo   completo |      Audiovisuales      | 1012345679 |  ricardo.salinas@uni.edu | Tecnologías   Audiovisuales |
|      Admin17      |    Emp40    | 07:00-15:00 |     Secretaria   de Decanato    |    Bachillerato    |        No        |        18        |    Casada    |   15/03/2005  | $   3,50 | Tiempo   completo |      Administración     | 2234567890 |   beatriz.gomez@uni.edu  |   Gestión   Administrativa  |
|      Admin18      |    Emp41    | 09:00-17:00 |     Ingeniero   de Sistemas     |     Ingeniería     |        No        |        14        |    Casado    |   8/07/2009   | $   5,00 | Tiempo   completo |         Sistemas        | 3345678901 |   andres.lozano@uni.edu  |   Desarrollo   de Software  |
|      Admin19      |    Emp42    | 07:00-15:00 |     Auxiliar   de Biblioteca    |    Licenciatura    |        Sí        |         3        |    Soltera   |   10/02/2021  | $   2,90 |   Medio   tiempo  |       Bibliotecas       | 4456789012 |   julia.vargas@uni.edu   |   Gestión   Bibliotecaria   |
|      Admin20      |    Emp43    | 08:00-16:00 |    Técnico   de Mantenimiento   |     Secundaria     |        No        |        13        |    Casado    |   5/08/2010   | $   3,20 | Tiempo   completo |      Mantenimiento      | 5567890123 |  gonzalo.ramirez@uni.edu |         Electricidad        |
|      Admin21      |    Emp44    | 09:00-17:00 |        Jefa   de Finanzas       |      Maestría      |        No        |        25        |    Casada    |   17/11/1998  | $   5,50 | Tiempo   completo |         Finanzas        | 6678901234 |   marta.herrera@uni.edu  |         Contabilidad        |
|      Admin22      |    Emp45    | 06:00-14:00 |     Personal   de Seguridad     |     Secundaria     |        No        |        11        |    Casado    |   10/04/2012  | $   2,50 | Tiempo   completo |        Seguridad        | 7789012345 |  jorge.castillo@uni.edu  |          Vigilancia         |
|      Admin23      |    Emp46    | 08:00-16:00 |     Técnico   de Laboratorio    |     Ingeniería     |        Sí        |         8        |    Soltera   |   15/09/2015  | $   4,00 | Tiempo   completo |         Ciencias        | 8890123456 |   elena.ortega@uni.edu   |     Química   Analítica     |
|      Admin24      |    Emp48    | 08:00-16:00 |      Secretaria   Académica     |    Licenciatura    |        No        |        12        |    Soltera   |   1/04/2011   | $   3,80 | Tiempo   completo |      Administración     | 1012345679 |    ana.morales@uni.edu   |   Gestión   Administrativa  |
|      Admin25      |    Emp49    | 07:00-15:00 |    Técnico   de Audiovisuales   |     Ingeniería     |        Sí        |         6        |    Soltero   |   7/03/2017   | $   3,50 | Tiempo   completo |      Audiovisuales      | 1123456789 |  ricardo.suarez@uni.edu  |   Tecnología   Audiovisual  |
|      Admin26      |    Emp50    | 09:00-17:00 | Asistente   de Recursos Humanos |    Licenciatura    |        Sí        |         4        |    Soltera   |   12/08/2019  | $   3,20 |   Medio   tiempo  |    Recursos   Humanos   | 2234567890 |   silvia.lopez@uni.edu   |    Gestión   de Personal    |

**Datos Aseo Generales**
| ID_Aseo | ID_Empleado | horario     | cargo                  | nivel_de_educacion | sigue_estudiando | años_experiencia | estado_civil | fecha_ingreso | salario  | tipo_de_contrato  | departamento          | teléfono   | correo_electronico    | especialidad  |
|---------|-------------|-------------|------------------------|--------------------|------------------|------------------|--------------|---------------|----------|-------------------|-----------------------|------------|-----------------------|---------------|
| SG1     | Emple13     | 07:00-15:00 | Personal   de Limpieza | Secundaria         | No               | 10               | Casado       | 12/06/2012    | $   2,20 | Tiempo   completo | Servicios   Generales | 4678901234 | jose.ramos@uni.edu    | Mantenimiento |
| SG2     | Emp37       | 07:00-15:00 | Conserje               | Secundaria         | No               | 10               | Casado       | 12/05/2013    | $   2,20 | Tiempo   completo | Servicios   Generales | 8890123456 | roberto.perez@uni.edu | Mantenimiento |
| SG3     | Emp47       | 07:00-15:00 | Conserje               | Secundaria         | No               | 17               | Casado       | 5/02/2006     | $   2,30 | Tiempo   completo | Servicios   Generales | 9901234567 | marcos.ruiz@uni.edu   | Mantenimiento |
