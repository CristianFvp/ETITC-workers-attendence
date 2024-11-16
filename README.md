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
**Normalizacion**
La primera tabla de datos la generamos pidiéndole a ChatGPT que la creara con ciertas condiciones que nosotros le indicamos. Con esta tabla como base, llevamos a cabo el proceso de normalización, que nos ayudó a organizar y estructurar mejor los datos. La idea principal de esta es reflejar información sobre algunos integrantes de la universidad y diseñar una base de datos que permitiera registrar y almacenar de forma clara el registro de entrada y salida de cada persona. 
