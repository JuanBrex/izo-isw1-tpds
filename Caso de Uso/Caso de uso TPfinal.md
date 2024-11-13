**Caso de uso Tp FINAL**

**Caso de uso Cámaras de video control vial.**  
**Precondición**:-  
**Actores**:Camara(primario)  
**Camino básico:**

1. La cámara envía al sistema fecha y hora, id de la cámara, patente y velocidad.  
2.  El sistema registra los datos y evalúa la velocidad del vehículo.

**Camino Alternativo**  
**2.a** El vehículo va a más de 70 km/h.  
 2.a.1 El sistema envía a la API  fecha y hora, id de la cámara, patente y velocidad y envía un correo con los datos que envió la cámara a la cuenta "avisos@ciudad".  
**2.b** El vehículo va a más de 100 km/h.  
 2.b.1 El sistema envía a la API  fecha y hora, id de la cámara, patente y velocidad, envía un correo con los datos que envió la cámara a la cuenta "avisos@ciudad" y envía los datos a una impresora para imprimirlos 3 veces.  
**Escenario de éxito**:  
\-El auto se pasó a menos de 70 km/h y se registraron correctamente los datos en el sistema.   
\-El vehículo pasó a más de 70km/h, se registraron correctamente los datos en el sistema, se enviaron los datos correctamente a la API y se enviaron los datos correctamente por correo electrónico.  
\-El vehículo pasó a más de 100km/h, se registraron correctamente los datos en el sistema, se enviaron los datos correctamente a la API, también por correo electrónico y a la impresora.  
**Escenario de fracaso: \-**