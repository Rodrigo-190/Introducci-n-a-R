# Introducci-n-a-R
Tarea 1. TIPOS DE DATOS
#### Datos Personales
- Nombre : Arnoldd Rodrigo Hernandez Hurtado
- Edad: 22 años
- Correro institucional : arnoldd.hernandez@est.ikiam.edu.ec
- Correo personal: rodrigohurtado190@outlook.com

#### Librerias utilizadas
```{javascript}
tidyverse
dplyr
```
#### Data utilizada
DNasa : ensayo Elisa de DNasa
- ##### Descripción
El `DNase` es un marco de datos tiene 176 filas y 3 columnas de datos obtenidos durante el desarrollo de un ensayo ELISA para la proteína DNasa recombinante en suero de rata.
- ##### Formato
Un objeto de clase `c("nfnGroupedData", "nfGroupedData", "groupedData", "data.frame")` que contiene las siguientes columnas:

`run`
un factor ordenado con niveles 10< … < 3 que indica la ejecución del ensayo.

`conc`
un vector numérico que da la concentración conocida de la proteína.

`densidad`
un vector numérico que proporciona la densidad óptica medida (adimensional) en el ensayo. Se obtuvieron mediciones de densidad óptica por duplicado.