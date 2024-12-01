# Normalizacion 2N

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
