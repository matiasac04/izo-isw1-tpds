## <a name="_hijswru831i"></a>**Caso de uso: Cámaras**
## <a name="_7xcjn8ijnw2n"></a>**Actores primarios:** Cámara, sistema
### <a name="_ood0mm4x8ejf"></a>**Actores Secundarios:** API, impresora, correo electrónico
## <a name="_r3c2hn98dvox"></a>**Precondiciones:** El sistema y las cámaras deben funcionar 24/7
## <a name="_3x2k0wxbax3"></a>**Camino básico:**
1. La cámara envía al sistema la fecha y hora, id de la cámara, patente y velocidad
1. El sistema registra el paso de cada vehículo 
1. El sistema mide la velocidad del vehículo 
1. El sistema realiza distintas acciones según la velocidad
## <a name="_ge16qy95354k"></a>**Caminos Alternativos:**
4\.a) El vehículo supera la velocidad de 70 km/h

4\.a.1) El sistema envía los datos a una API y envía un correo con los datos que envió la cámara a la cuenta "avisos@ciudad”

4\.b) El vehículo supera la velocidad de 100km/h

4\.b.1) El sistema envía los datos a una API, el sistema envía un correo con los datos que envió la cámara a la cuenta "alertas@ciudad" y el sistema envía 3 veces los datos a una impresora para que sean impresos.

**Escenario de éxito:** El sistema recibe los datos y realiza distintas acciones según la velocidad

**Escenario de fracaso: -**
