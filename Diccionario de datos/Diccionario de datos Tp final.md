**Diccionario de datos Tp FINAL**

**registro=**  patente \+ velocidad  \+ fecha \+IdCam  
**camara \=** @IdCam \+ desc \+ ubi \+ IP \+ modelo \+ fecha  
**ubi=** coord X \+ coord Y

| Nombre | Descripción | Tipo | Longitud | Dominio |
| :---: | :---- | :---: | :---: | :---: |
| IdCam | número identificador de la cámara | Int | 12 | continuo |
| desc | Descripción general de la cámara | str | 100 | a-Z |
| IP | Dirección IP de la cámara | str | 12 | continuo |
| modelo | Nombre y marca de la cámara | str | 100 | a-Z |
| coordX | coordenadas en X de la cámara | str | 20 | continuo |
| coordY | coordenadas Y de la cámara | str | 20 | continuo |
| patente | identificador del vehicular | str | 7 | continuo |
| velocidad | velocidad del vehículo | float | 5 | continuo |
| fecha | fecha y hora del registro | date | \- | continuo |

