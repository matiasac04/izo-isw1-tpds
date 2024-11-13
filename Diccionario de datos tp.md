**Diccionario de datos**

Cámara:  id + desc + ubi + IP + modelo

Registro: Fecha + id + patente + velocidad

Ubi: Coor X + Coor Y

|Nombre|Descripción|Tipo|Longitud|Dominio|
| :-: | :-: | :-: | :-: | :-: |
|id|Identificador de la cámara|Int|50|continuo|
|desc|describe la camara|String|200|a-z|
|ubi|donde se encuentra la cámara|String|100|Continuo|
|IP|dirección IP de la cámara|`  `String|20|Continuo|
|modelo|modelo de la cámara|String|200|a-z|
|Fecha|fecha en la que pasó el vehículo|Date|-|-|
|Patente|patente del auto|String|7|Continuo|
|Velocidad|velocidad a la que va el vehículo|Float|10|Continuo|
|Coor Y|coordenadas Y de la cámara|String|50|Continuo|
|Coor X|coordenadas X de la cámara|String|50|Continuo|


