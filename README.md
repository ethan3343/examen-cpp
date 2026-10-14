# examen-cpp

Nombre : Ethan Isaac Rojas Chinchilla

|   LÍNEA   |                              JUSTIFICACION                                       |                CORRECCION                        |
|-----------|----------------------------------------------------------------------------------|--------------------------------------------------|
|    8      | da error porque no tiene el ; despues de cerrar la llave                         |        añadirle un ; despues del }               |
|    10     |pasa el struct como copia, entonces la modificacion no afecta al jugador original |               usar &: Jugador& j                 | 
|    22     |      char no funciona con comillas dobles, deben ser simples                     | cambiar las comillas dobles por simples en la 'A'|
|    25     |se crea un alias que hacia que el valor viejo se perdiera                         |       quitar el & para que sea independiente     |
|    29     | usar solamente > no avisaba cuando el puntaje era 100                            |                   usar >= 100                    |
