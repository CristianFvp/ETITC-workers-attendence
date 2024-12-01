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


---
**Normalizacion**:

La primera tabla de datos la generamos pidiéndole a ChatGPT que la creara con ciertas condiciones que nosotros le indicamos. Con esta tabla como base, llevamos a cabo el proceso de normalización, que nos ayudó a organizar y estructurar mejor los datos. La idea principal de esta es reflejar información sobre algunos integrantes de la universidad y diseñar una base de datos que permitiera registrar y almacenar de forma clara el registro de entrada y salida de cada persona. 

**Primera Forma de Normalizacion**:

Nos enfocamos en eliminar aquellos datos que no eran atómicos, es decir aquellos que contenían más de un valor en una misma celda. También eliminamos la redundancia, asegurándonos de que cada dato tuviera su propio atributo o columna, sin duplicaciones innecesarias. Esto permitió que la tabla fuera más eficiente y fácil de entender, ya que cada valor estaba correctamente separado y no se perdía ninguna información.Nos aseguramos de que la tabla mantuviera la misma estructura y fuera igual de comprensible, para que la información siguiera siendo accesible y clara para su consulta.
( La tabla generada anteriormente ya contaba con la normalizacion)



**Segunda Forma de Normalizacion**:

Lo que hicimos fue separar la información que no estaba completamente relacionada con la clave primaria. En una tabla, organizamos todos los datos personales y aquellos directamente relacionados con los trabajadores, como su nombre, dirección y demás detalles. En otra tabla, dividimos la información relacionada con las materias y, además, establecimos una separación clara de los roles que tiene cada trabajador. 

**Tercera Forma de Normalizacion**:

El objetivo fue eliminar cualquier dependencia transitiva, es decir, asegurarnos de que no hubiera atributos que dependieran de otros atributos no clave. Para lograr esto, se crearon tres tablas principales. La primera tabla incluye los roles de los trabajadores, como profesores, administradores y personal de aseo general, lo cual permite una gestión más clara y separada de los diferentes tipos de personal. La segunda tabla contiene la información específica de cada trabajador, como sus datos personales (nombre, dirección, etc.), y la tercera tabla organiza la información relacionada con las materias, asignando a cada una su respectiva clave primaria. Estas tablas están correctamente relacionadas entre sí mediante claves foráneas, lo que asegura una estructura más eficiente y libre de redundancias. Con este paso, conseguimos una base de datos más normalizada, organizada y fácil de mantener.





Referencias:
   - https://aws.amazon.com/es/what-is/database/
   - https://controllaboral.es/control-entrada-salida-personal/
   - https://hikvision.lat/productos/lector-biometrico-facial-hikvision-ds-k1t341amf.html
   - https://www.youtube.com/watch?v=MXpeVSPU_S0
   - (S/f-a). Researchgate.net. Recuperado el 12 de septiembre de 2024, de 
     https://www.researchgate.net/publication/358178607_Automated_
   - attendance_management_systems_systematic_literature_review
     ChatGPT. (s/f). Chatgpt.com. Recuperado el 13-14 de septiembre de 2024, de https://chatgpt.com/
