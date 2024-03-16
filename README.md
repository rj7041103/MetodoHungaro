Corridas del programa con el algoritmo de Munkres. Cabe destacar que este programa puede dar incoherencias en los resultados por errores humanos.
Quieres usar el programa (S/N): s
El problema es de maximización o minimización (Max/Min): min
Ingrese los nombres de las columnas separados por comas: Camión 1,Camión 2,Camión 3,Camión 4
Ingrese los nombres de las filas separados por comas: Conductor A,Conductor B,Conductor C

Ingrese el valor para la fila Conductor A, columna Camión 1: 180
Ingrese el valor para la fila Conductor A, columna Camión 2: 150
Ingrese el valor para la fila Conductor A, columna Camión 3: 200
Ingrese el valor para la fila Conductor A, columna Camión 4: 200
Ingrese el valor para la fila Conductor B, columna Camión 1: 250
Ingrese el valor para la fila Conductor B, columna Camión 2: 305
Ingrese el valor para la fila Conductor B, columna Camión 3: 450
Ingrese el valor para la fila Conductor B, columna Camión 4: 500
Ingrese el valor para la fila Conductor C, columna Camión 1: 200
Ingrese el valor para la fila Conductor C, columna Camión 2: 208
Ingrese el valor para la fila Conductor C, columna Camión 3: 320
Ingrese el valor para la fila Conductor C, columna Camión 4: 100
-----------------------Data Original----------------------
            Camión 1 Camión 2 Camión 3 Camión 4  Min
Conductor A      180      150      200      200  150
Conductor B      250      305      450      500  250
Conductor C      200      208      320      100  100
Ficticia           1        1        1        1    1

-----------------------Primera Iteración por Filas----------------------
             Camión 1  Camión 2  Camión 3  Camión 4  Min
Conductor A        30         0        50        50    0
Conductor B         0        55       200       250    0
Conductor C       100       108       220         0    0
Ficticia            0         0         0         0    0

DataFrame con filas y columnas tachadas:

             Camión 1  Camión 2  Camión 3  Camión 4
Conductor A        30         0        50        50
Conductor B         0        55       200       250
Conductor C       100       108       220         0
X                   0         0         0         0

¿Cuántas intersecciones hay en la matriz? : 0

             Camión 1  Camión 2  Camión 3  Camión 4
Conductor A        30         0        50        50
Conductor B         0        55       200       250
Conductor C       100       108       220         0
Ficticia            0         0         0         0

Asignación óptima encontrada por el algoritmo de Munkres:

Fila Conductor A, Columna Camión 2: 0.0
Fila Conductor B, Columna Camión 1: 0.0
Fila Conductor C, Columna Camión 4: 0.0
Fila Ficticia, Columna Camión 3: 0.0
El costo mínimo de asignación es:  501
Quieres usar el programa (S/N): s
El problema es de maximización o minimización (Max/Min): min
Ingrese los nombres de las columnas separados por comas: Servidor 1,Servidor 2,Servidor 3
Ingrese los nombres de las filas separados por comas: Empresa A,Empresa B, Empresa C

Ingrese el valor para la fila Empresa A, columna Servidor 1: 3
Ingrese el valor para la fila Empresa A, columna Servidor 2: 4
Ingrese el valor para la fila Empresa A, columna Servidor 3: 0
Ingrese el valor para la fila Empresa B, columna Servidor 1: 4
Ingrese el valor para la fila Empresa B, columna Servidor 2: 5
Ingrese el valor para la fila Empresa B, columna Servidor 3: 0
Ingrese el valor para la fila  Empresa C, columna Servidor 1: 0
Ingrese el valor para la fila  Empresa C, columna Servidor 2: 0
Ingrese el valor para la fila  Empresa C, columna Servidor 3: 3
-----------------------Data Original----------------------
           Servidor 1 Servidor 2 Servidor 3 Min
Empresa A           3          4          0   0
Empresa B           4          5          0   0
 Empresa C          0          0          3   0

-----------------------Primera Iteración por Filas----------------------
            Servidor 1  Servidor 2  Servidor 3  Min
Empresa A            3           4           0    0
Empresa B            4           5           0    0
 Empresa C           0           0           3    0

            Servidor 1  Servidor 2  Servidor 3  Min
Empresa A            3           4           0    0
Empresa B            4           5           0    0
 Empresa C           0           0           3    0
Min_Col              0           0           0    0

-----------------------Segunda Iteración por Columnas----------------------
            Servidor 1  Servidor 2  Servidor 3  Min
Empresa A            3           4           0    0
Empresa B            4           5           0    0
 Empresa C           0           0           3    0
Min_Col              0           0           0    0
DataFrame con filas y columnas tachadas:

           Servidor 1  Servidor 2  X
Empresa A           3           4  0
Empresa B           4           5  0
X                   0           0  3

¿Cuántas intersecciones hay en la matriz? : 1
el menor valor es:3 en la fila:Empresa A y columna:Servidor 1
Ingresa el nombre de la fila en la que hay una intersección: X
Ingresa el nombre de la columna en la que hay una intersección: X
---------------------Resultado Final-----------------------

           Servidor 1  Servidor 2  X
Empresa A           0           1  0
Empresa B           1           2  0
X                   0           0  6

            Servidor 1  Servidor 2  Servidor 3
Empresa A            0           1           0
Empresa B            1           2           0
 Empresa C           0           0           6

Asignación óptima encontrada por el algoritmo de Munkres:

Fila Empresa A, Columna Servidor 1: 0.0
Fila Empresa B, Columna Servidor 3: 0.0
Fila  Empresa C, Columna Servidor 2: 0.0
El costo mínimo de asignación es:  3
Quieres usar el programa (S/N): s
El problema es de maximización o minimización (Max/Min): min
Ingrese los nombres de las columnas separados por comas: Tarea 1,Tarea 2,Tarea 3
Ingrese los nombres de las filas separados por comas: Programador 1,Programador 2,Programador 3

Ingrese el valor para la fila Programador 1, columna Tarea 1: 15
Ingrese el valor para la fila Programador 1, columna Tarea 2: 10
Ingrese el valor para la fila Programador 1, columna Tarea 3: 9
Ingrese el valor para la fila Programador 2, columna Tarea 1: 9
Ingrese el valor para la fila Programador 2, columna Tarea 2: 15
Ingrese el valor para la fila Programador 2, columna Tarea 3: 10
Ingrese el valor para la fila Programador 3, columna Tarea 1: 10
Ingrese el valor para la fila Programador 3, columna Tarea 2: 12
Ingrese el valor para la fila Programador 3, columna Tarea 3: 8
-----------------------Data Original----------------------
              Tarea 1 Tarea 2 Tarea 3 Min
Programador 1      15      10       9   9
Programador 2       9      15      10   9
Programador 3      10      12       8   8

-----------------------Primera Iteración por Filas----------------------
               Tarea 1  Tarea 2  Tarea 3  Min
Programador 1        6        1        0    0
Programador 2        0        6        1    0
Programador 3        2        4        0    0

               Tarea 1  Tarea 2  Tarea 3  Min
Programador 1        6        1        0    0
Programador 2        0        6        1    0
Programador 3        2        4        0    0
Min_Col              0        1        0    0

-----------------------Segunda Iteración por Columnas----------------------
               Tarea 1  Tarea 2  Tarea 3  Min
Programador 1        6        0        0    0
Programador 2        0        5        1    0
Programador 3        2        3        0    0
Min_Col              0        0        0    0
DataFrame con filas y columnas tachadas:

               Tarea 1  Tarea 2  X
X                    6        0  0
Programador 2        0        5  1
Programador 3        2        3  0

¿Cuántas intersecciones hay en la matriz? : 0

               Tarea 1  Tarea 2  Tarea 3
Programador 1        6        0        0
Programador 2        0        5        1
Programador 3        2        3        0

Asignación óptima encontrada por el algoritmo de Munkres:

Fila Programador 1, Columna Tarea 2: 0.0
Fila Programador 2, Columna Tarea 1: 0.0
Fila Programador 3, Columna Tarea 3: 0.0
El costo mínimo de asignación es:  27
Quieres usar el programa (S/N): n

Video Explicativo del Algoritmo de Munkres: https://youtu.be/QUHMvYc1azI
