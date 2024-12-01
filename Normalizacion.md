# Normalizacion 2N

##Tabla Empleados

| ID_Empleados |  nombre  |  apellido | número_de_documento | género | edad | estado_civil |    dirección_de_vivienda   |  teléfono  |    correo_electronico    | nivel_de_educacion | sigue_estudiando |
|:------------:|:--------:|:---------:|:-------------------:|:------:|:----:|:------------:|:--------------------------:|:----------:|:------------------------:|:------------------:|:----------------:|
|    Emple1    |   Juan   |   Pérez   |       12345678      |  Masc  |  45  |    Casado    |    Av.   Libertador 101    | 1234567890 |    juan.perez@uni.edu    |      Doctorado     |        No        |
|    Emple2    |    Ana   |   Gómez   |       23456789      |   Fem  |  38  |    Soltera   |        Calle   2 #34       | 2345678901 |     ana.gomez@uni.edu    |      Maestría      |        No        |
|    Emple3    |   Luis   | Rodríguez |       34567890      |  Masc  |  50  |    Casado    |     Av.   Los Olivos 76    | 3456789012 |  luis.rodriguez@uni.edu  |      Doctorado     |        No        |
|    Emple4    |   Marta  |  Martínez |       45678901      |   Fem  |  42  |  Divorciada  |    Calle   de la Luna 11   | 4567890123 |  marta.martinez@uni.edu  |    Licenciatura    |        No        |
|    Emple5    |  Carlos  |   Lopez   |       56789012      |  Masc  |  35  |    Soltero   |     Av.   San Martín 33    | 5678901234 |   carlos.lopez@uni.edu   |      Maestría      |        No        |
|    Emple6    |   Sofía  |  Jiménez  |       67890123      |   Fem  |  40  |    Casada    |     Calle   del Sol 21     | 6789012345 |   sofia.jimenez@uni.edu  |      Doctorado     |        Sí        |
|    Emple7    |   Pedro  |   Castro  |       78901234      |  Masc  |  48  |    Casado    |     Av.   de la Paz 88     | 7890123456 |   pedro.castro@uni.edu   |    Licenciatura    |        No        |
|    Emple8    |   Laura  |   Suárez  |       89012345      |   Fem  |  29  |    Soltera   |       Calle   Real 45      | 8901234567 |   laura.suarez@uni.edu   |      Maestría      |        Sí        |
|    Emple9    |   Jorge  |  Salazar  |       90123456      |  Masc  |  54  |    Casado    |  Av.   de la República 56  | 9012345678 |   jorge.salazar@uni.edu  |      Doctorado     |        No        |
|    Emple10   |  Isabel  |   Reyes   |       1234567       |   Fem  |  37  |    Soltera   |     Calle   del Mar 78     |  123456789 |   isabel.reyes@uni.edu   |    Licenciatura    |        Sí        |
|    Emple11   |  Antonio |  Herrera  |       12345679      |  Masc  |  49  |    Casado    |   Av.   de la Libertad 90  | 1123456789 |  antonio.herrera@uni.edu |      Doctorado     |        No        |
|    Emple12   |   Elena  |   Rivera  |       23456780      |   Fem  |  43  |    Soltera   |      Calle   Nueva 34      | 2234567890 |   elena.rivera@uni.edu   |      Maestría      |        No        |
|    Emple13   |  Manuel  |   Ortiz   |       34567891      |  Masc  |  52  |    Casado    |     Av.   del Norte 76     | 3345678901 |   manuel.ortiz@uni.edu   |    Licenciatura    |        Sí        |
|    Emple14   |  Claudia |  Mendoza  |       45678902      |   Fem  |  33  |    Soltera   |    Calle   del Centro 12   | 4456789012 |  claudia.mendoza@uni.edu |      Maestría      |        No        |
|    Emple15   | Fernando |   Romero  |       56789013      |  Masc  |  46  |    Casado    |      Av.   del Sur 89      | 5567890123 |  fernando.romero@uni.edu |      Doctorado     |        Sí        |
|    Emple16   |  Valeria |   Vargas  |       67890124      |   Fem  |  31  |    Soltera   | Calle   de la Primavera 67 | 6678901234 |  valeria.vargas@uni.edu  |    Licenciatura    |        No        |
|    Emple17   |  Rafael  |   Castro  |       78901235      |  Masc  |  39  |    Casado    |   Av.   de la Cultura 23   | 7789012345 |   rafael.castro@uni.edu  |      Maestría      |        Sí        |
|    Emple18   | Gabriela |   Muñoz   |       89012346      |   Fem  |  44  |    Soltera   |     Calle   del Río 45     | 8890123456 |  gabriela.muñoz@uni.edu  |      Doctorado     |        No        |
|    Emple19   |   Oscar  |  Navarro  |       90123457      |  Masc  |  51  |    Casado    |      Av.   del Sol 90      | 9012345679 |   oscar.navarro@uni.edu  |    Licenciatura    |        Sí        |
|    Emple20   |   Nora   |  Salinas  |       1234568       |   Fem  |  32  |    Soltera   |     Calle   del Lago 11    | 1234567899 |   nora.salinas@uni.edu   |      Maestría      |        No        |
|    Emple21   |  Javier  |  Alvarez  |       12345680      |  Masc  |  47  |    Casado    |  Calle   de la Estación 77 | 1345678901 |  javier.alvarez@uni.edu  |      Doctorado     |        Sí        |
|    Emple22   |   Mario  |  González |       34567892      |  Masc  |  41  |    Casado    |      Calle   Mayor 12      | 2456789012 |  mario.gonzalez@uni.edu  |    Licenciatura    |        No        |
|    Emple23   |   Lucía  |   Torres  |       45678903      |   Fem  |  29  |    Soltera   |      Av.   Central 56      | 3567890123 |   lucia.torres@uni.edu   |    Bachillerato    |        Sí        |
|    Emple24   |   José   |   Ramos   |       56789014      |  Masc  |  36  |    Casado    |    Calle   del Bosque 78   | 4678901234 |    jose.ramos@uni.edu    |     Secundaria     |        No        |
|    Emple25   |   Carla  | Fernández |       67890125      |   Fem  |  43  |    Soltera   |   Av.   de las Flores 89   | 5789012345 |  carla.fernandez@uni.edu |      Maestría      |        No        |
|    Emple26   |  Andrés  |  Morales  |       78901236      |  Masc  |  34  |    Soltero   |        Calle   7 #45       | 6789012346 |  andres.morales@uni.edu  |     Ingeniería     |        Sí        |
|    Emple27   |  Felipe  |  Morales  |       89012347      |  Masc  |  45  |    Casado    |     Av.   Libertador 22    | 7890123457 |  felipe.morales@uni.edu  |    Licenciatura    |        No        |
|    Emple28   | Patricia |   Romero  |       90123458      |   Fem  |  50  |    Casada    |     Calle   Jardines 89    | 8901234568 |  patricia.romero@uni.edu |      Maestría      |        No        |
|    Emple29   |   Hugo   |  Cabrera  |       12345681      |  Masc  |  38  |    Soltero   |  Calle   de los Álamos 23  | 9012345679 |   hugo.cabrera@uni.edu   |     Secundaria     |        No        |
|    Emple30   |  Daniela |    Ruiz   |       23456781      |   Fem  |  27  |    Soltera   |   Av.   de los Robles 45   | 1123456789 |   daniela.ruiz@uni.edu   |    Bachillerato    |        Sí        |
|    Emple31   |   Diego  |  Paredes  |       34567893      |  Masc  |  42  |    Casado    |     Calle   del Arco 67    | 2234567890 |   diego.paredes@uni.edu  |     Secundaria     |        No        |
|    Emple32   |   Elena  | Gutierrez |       45678904      |   Fem  |  39  |    Casada    |     Av.   del Norte 45     | 3345678901 |  elena.gutierrez@uni.edu |    Licenciatura    |        No        |
|    Emple33   |  Sergio  |    Peña   |       56789015      |  Masc  |  46  |    Casado    |  Calle   de la Montaña 101 | 4456789012 |    sergio.pena@uni.edu   |      Maestría      |        No        |
|    Emple34   |   Laura  |  Aguilar  |       67890126      |   Fem  |  35  |    Soltera   |   Av.   de la Juventud 76  | 5567890123 |   laura.aguilar@uni.edu  |      Maestría      |        No        |
|    Emple35   |   Pablo  |   Vargas  |       78901237      |  Masc  |  52  |    Casado    |  Calle   de la Estrella 89 | 6678901234 |   pablo.vargas@uni.edu   |    Licenciatura    |        No        |
|    Emple36   |  Susana  |   Castro  |       89012348      |   Fem  |  31  |    Soltera   |      Av.   del Sol 22      | 7789012345 |   susana.castro@uni.edu  |    Bachillerato    |        Sí        |
|    Emple37   |  Roberto |   Pérez   |       99012349      |  Masc  |  40  |    Casado    |    Calle   Los Álamos 56   | 8890123456 |   roberto.perez@uni.edu  |     Secundaria     |        No        |
|    Emple38   |  Teresa  | Fernández |       10123450      |   Fem  |  32  |    Soltera   |    Av.   de los Pinos 12   | 9012345679 | teresa.fernandez@uni.edu |    Licenciatura    |        Sí        |
|    Emple39   |  Ricardo |  Salinas  |       11234551      |  Masc  |  35  |    Casado    |      Av.   Central 34      | 1012345679 |  ricardo.salinas@uni.edu |     Ingeniería     |        No        |
|    Emple40   |  Beatriz |   Gómez   |       22345652      |   Fem  |  45  |    Casada    |      Calle   Nueva 78      | 2234567890 |   beatriz.gomez@uni.edu  |    Bachillerato    |        No        |
|    Emple41   |  Andrés  |   Lozano  |       33456753      |  Masc  |  38  |    Casado    |     Av.   del Norte 12     | 3345678901 |   andres.lozano@uni.edu  |     Ingeniería     |        No        |
|    Emple42   |   Julia  |   Vargas  |       44567854      |   Fem  |  28  |    Soltera   |     Calle   del Sol 34     | 4456789012 |   julia.vargas@uni.edu   |    Licenciatura    |        Sí        |
|    Emple43   |  Gonzalo |  Ramírez  |       55678955      |  Masc  |  39  |    Casado    |      Av.   del Este 22     | 5567890123 |  gonzalo.ramirez@uni.edu |     Secundaria     |        No        |
|    Emple44   |   Marta  |  Herrera  |       66789056      |   Fem  |  52  |    Casada    |    Calle   del Norte 45    | 6678901234 |   marta.herrera@uni.edu  |      Maestría      |        No        |
|    Emple45   |   Jorge  |  Castillo |       77890157      |  Masc  |  37  |    Casado    |   Av.   de los Robles 23   | 7789012345 |  jorge.castillo@uni.edu  |     Secundaria     |        No        |
|    Emple46   |   Elena  |   Ortega  |       88901258      |   Fem  |  34  |    Soltera   |  Calle   de la Estrella 89 | 8890123456 |   elena.ortega@uni.edu   |     Ingeniería     |        Sí        |
|    Emple47   |  Marcos  |    Ruiz   |       99012359      |  Masc  |  42  |    Casado    |   Av.   de las Flores 12   | 9901234567 |    marcos.ruiz@uni.edu   |     Secundaria     |        No        |
|    Emple48   |    Ana   |  Morales  |       10123460      |   Fem  |  36  |    Soltera   |       Calle   Real 45      | 1012345679 |    ana.morales@uni.edu   |    Licenciatura    |        No        |
|    Emple49   |  Ricardo |   Suárez  |       11234561      |  Masc  |  29  |    Soltero   |     Av.   del Norte 22     | 1123456789 |  ricardo.suarez@uni.edu  |     Ingeniería     |        Sí        |
|    Emple50   |  Silvia  |   López   |       22345662      |   Fem  |  30  |    Soltera   |    Calle   de la Luna 56   | 2234567890 |   silvia.lopez@uni.edu   |    Licenciatura    |        Sí        |


##Tabla InFormacion de Contrato 

| ID_Contrato |              cargo              |       departamento      |   horario   |  salario |  tipo_de_contrato | años_experiencia | fecha_ingreso |
|:-----------:|:-------------------------------:|:-----------------------:|:-----------:|:--------:|:-----------------:|:----------------:|:-------------:|
|    Cont1    |             Profesor            |    Ciencias   Exactas   | 08:00-10:00 | $   5,00 | Tiempo   completo |        20        |   15/02/2005  |
|    Cont2    |             Profesor            |    Ciencias   Exactas   | 10:00-12:00 | $   4,20 |   Medio   tiempo  |        12        |   12/05/2011  |
|    Cont3    |             Profesor            |    Ciencias   Exactas   | 12:00-14:00 | $   5,50 | Tiempo   completo |        25        |   3/09/1998   |
|    Cont4    |             Profesor            |       Humanidades       | 14:00-16:00 | $   3,80 |   Medio   tiempo  |        18        |   1/08/2002   |
|    Cont5    |             Profesor            |       Humanidades       | 16:00-18:00 | $   4,00 | Tiempo   completo |        10        |   14/04/2013  |
|    Cont6    |             Profesor            |   Ciencias   Naturales  | 08:00-10:00 | $   5,20 |   Medio   tiempo  |        15        |   7/06/2008   |
|    Cont7    |             Profesor            |   Ciencias   Sociales   | 10:00-12:00 | $   4,80 | Tiempo   completo |        22        |   25/10/1999  |
|    Cont8    |             Profesor            |       Humanidades       | 12:00-14:00 | $   3,60 |   Medio   tiempo  |         5        |   17/09/2017  |
|    Cont9    |             Profesor            |  Lenguas   Extranjeras  | 14:00-16:00 | $   5,70 | Tiempo   completo |        28        |   3/03/1995   |
|    Cont10   |             Profesor            |    Ciencias   Exactas   | 16:00-18:00 | $   4,10 |  Tiempo   parcial |         9        |   21/07/2014  |
|    Cont11   |             Profesor            |    Ciencias   Exactas   | 08:00-10:00 | $   5,50 | Tiempo   completo |        24        |   10/06/1998  |
|    Cont12   |             Profesor            |    Ciencias   Exactas   | 10:00-12:00 | $   4,30 |   Medio   tiempo  |        19        |   1/03/2003   |
|    Cont13   |             Profesor            |       Humanidades       | 12:00-14:00 | $   4,90 | Tiempo   completo |        27        |   7/09/1994   |
|    Cont14   |             Profesor            |       Humanidades       | 14:00-16:00 | $   4,10 |   Medio   tiempo  |         8        |   21/05/2014  |
|    Cont15   |             Profesor            |   Ciencias   Naturales  | 16:00-18:00 | $   5,40 | Tiempo   completo |        21        |   17/11/1999  |
|    Cont16   |             Profesor            |   Ciencias   Sociales   | 08:00-10:00 | $   3,90 |   Medio   tiempo  |         6        |   12/04/2017  |
|    Cont17   |             Profesor            |       Humanidades       | 10:00-12:00 | $   4,30 | Tiempo   completo |        13        |   1/02/2010   |
|    Cont18   |             Profesor            |  Lenguas   Extranjeras  | 12:00-14:00 | $   4,80 |   Medio   tiempo  |        19        |   17/09/2003  |
|    Cont19   |             Profesor            |    Ciencias   Exactas   | 14:00-16:00 | $   5,00 | Tiempo   completo |        25        |   20/11/1997  |
|    Cont20   |             Profesor            |    Ciencias   Exactas   | 16:00-18:00 | $   4,20 |   Medio   tiempo  |         8        |   17/08/2015  |
|    Cont21   |             Profesor            |    Ciencias   Exactas   | 08:00-10:00 | $   5,30 | Tiempo   completo |        22        |   5/03/2000   |
|    Cont22   |      Secretario   Académico     |      Administración     | 09:00-17:00 | $   3,80 | Tiempo   completo |        16        |   9/07/2006   |
|    Cont23   |          Recepcionista          |      Administración     | 08:00-16:00 | $   2,60 |   Medio   tiempo  |         5        |   21/10/2017  |
|    Cont24   |      Personal   de Limpieza     |  Servicios   Generales  | 07:00-15:00 | $   2,20 | Tiempo   completo |        10        |   12/06/2012  |
|    Cont25   |    Coordinadora   de Eventos    |  Relaciones   Públicas  | 10:00-18:00 | $   4,50 | Tiempo   completo |        12        |   4/05/2010   |
|    Cont26   |      Técnico   Informático      |    Soporte   Técnico    | 09:00-17:00 | $   4,20 | Tiempo   completo |         9        |   8/09/2015   |
|    Cont27   |             Contador            |         Finanzas        | 08:00-16:00 | $   3,90 | Tiempo   completo |        15        |   12/03/2008  |
|    Cont28   |    Jefe   de Recursos Humanos   |    Recursos   Humanos   | 07:00-15:00 | $   5,60 | Tiempo   completo |        22        |   1/05/2000   |
|    Cont29   |     Personal   de Seguridad     |        Seguridad        | 06:00-14:00 | $   2,50 | Tiempo   completo |        12        |   3/04/2010   |
|    Cont30   |    Asistente   Administrativa   |      Administración     | 09:00-17:00 | $   2,80 |   Medio   tiempo  |         4        |   11/06/2019  |
|    Cont31   |    Técnico   de Mantenimiento   |      Mantenimiento      | 08:00-16:00 | $   3,20 | Tiempo   completo |        18        |   15/03/2005  |
|    Cont32   |     Coordinadora   Académica    |      Administración     | 07:00-15:00 | $   4,60 | Tiempo   completo |        13        |   18/07/2008  |
|    Cont33   |          Bibliotecario          |       Bibliotecas       | 08:00-16:00 | $   3,90 | Tiempo   completo |        15        |   22/05/2009  |
|    Cont34   |   Coordinadora   de Bienestar   | Bienestar   Estudiantil | 09:00-17:00 | $   4,30 | Tiempo   completo |         8        |   7/10/2015   |
|    Cont35   |  Supervisor   de Mantenimiento  |      Mantenimiento      | 10:00-18:00 | $   4,60 | Tiempo   completo |        25        |   11/11/1996  |
|    Cont36   |   Secretaria   Administrativa   |      Administración     | 09:00-17:00 | $   2,70 |   Medio   tiempo  |         4        |   14/04/2018  |
|    Cont37   |             Conserje            |  Servicios   Generales  | 07:00-15:00 | $   2,20 | Tiempo   completo |        10        |   12/05/2013  |
|    Cont38   |    Asistente   de Laboratorio   |         Ciencias        | 08:00-16:00 | $   3,00 | Tiempo   completo |         7        |   1/09/2016   |
|    Cont39   |    Técnico   de Audiovisuales   |      Audiovisuales      | 09:00-17:00 | $   4,00 | Tiempo   completo |        12        |   5/06/2011   |
|    Cont40   |     Secretaria   de Decanato    |      Administración     | 07:00-15:00 | $   3,50 | Tiempo   completo |        18        |   15/03/2005  |
|    Cont41   |     Ingeniero   de Sistemas     |         Sistemas        | 09:00-17:00 | $   5,00 | Tiempo   completo |        14        |   8/07/2009   |
|    Cont42   |     Auxiliar   de Biblioteca    |       Bibliotecas       | 07:00-15:00 | $   2,90 |   Medio   tiempo  |         3        |   10/02/2021  |
|    Cont43   |    Técnico   de Mantenimiento   |      Mantenimiento      | 08:00-16:00 | $   3,20 | Tiempo   completo |        13        |   5/08/2010   |
|    Cont44   |        Jefa   de Finanzas       |         Finanzas        | 09:00-17:00 | $   5,50 | Tiempo   completo |        25        |   17/11/1998  |
|    Cont45   |     Personal   de Seguridad     |        Seguridad        | 06:00-14:00 | $   2,50 | Tiempo   completo |        11        |   10/04/2012  |
|    Cont46   |     Técnico   de Laboratorio    |         Ciencias        | 08:00-16:00 | $   4,00 | Tiempo   completo |         8        |   15/09/2015  |
|    Cont47   |             Conserje            |  Servicios   Generales  | 07:00-15:00 | $   2,30 | Tiempo   completo |        17        |   5/02/2006   |
|    Cont48   |      Secretaria   Académica     |      Administración     | 08:00-16:00 | $   3,80 | Tiempo   completo |        12        |   1/04/2011   |
|    Cont49   |    Técnico   de Audiovisuales   |      Audiovisuales      | 07:00-15:00 | $   3,50 | Tiempo   completo |         6        |   7/03/2017   |
|    Cont50   | Asistente   de Recursos Humanos |    Recursos   Humanos   | 09:00-17:00 | $   3,20 |   Medio   tiempo  |         4        |   12/08/2019  |


##Tabla Materias 

| ID_Materia |   materia   |
|:----------:|:-----------:|
|    Mat1    | Matemáticas |
|    Mat2    |    Física   |
|    Mat3    |   Química   |
|    Mat4    |   Historia  |
|    Mat5    |  Literatura |
|    Mat6    |   Biología  |
|    Mat7    |  Geografía  |
|    Mat8    |     Arte    |
|    Mat9    |    Inglés   |
