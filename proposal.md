# Propuesta TP DSW

## Grupo
### Integrantes
* 47834 - Banqueri, Federico
* 43081 - Bozio, Rodrigo

### Repositorios
* [frontend app](https://github.com/Bozio96/tp-back)
* [backend app](https://github.com/Bozio96/tp-front)


## Tema
### Descripción
Desarrollo de un sistema integral de gestión comercial (ABM), orientado al control eficiente de productos, ventas, clientes y stock. La aplicación permite administrar altas, bajas y modificaciones, visualizar  y mantener actualizada la información del negocio en tiempo real, optimizando así la toma de decisiones operativas.

### Modelo
![DER-PROYECTO](https://res.cloudinary.com/dnfil5isx/image/upload/v1747062694/DER_rxuupf.png)

[DRAW.IO](https://drive.google.com/file/d/1RTLf_E5UD35Dk5Pul_CtIHzCp6Ftm9do/view?usp=drive_link)

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Producto<br>2. CRUD Cliente<br>|
|CRUD dependiente|1. CRUD Habitación {depende de} CRUD Tipo Habitacion<br>2. CRUD Cliente {depende de} CRUD Localidad|
|Listado<br>+<br>detalle| 1. Listado de habitaciones filtrado por tipo de habitación, muestra nro y tipo de habitación => detalle CRUD Habitacion<br> 2. Listado de reservas filtrado por rango de fecha, muestra nro de habitación, fecha inicio y fin estadía, estado y nombre del cliente => detalle muestra datos completos de la reserva y del cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Habitacion<br>2. CRUD Servicio<br>3. CRUD Localidad<br>4. CRUD Provincia<br>5. CRUD Habitación<br>6. CRUD Empleado<br>7. CRUD Cliente|
|CUU/Epic|1. Reservar una habitación para la estadía<br>2. Realizar el check-in de una reserva<br>3. Realizar el check-out y facturación de estadía y servicios|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados |1. Estadía del día filtrado por fecha muestra, cliente, habitaciones y estado <br>2. Reservas filtradas por cliente muestra datos del cliente y de cada reserve fechas, estado cantidad de habitaciones y huespedes|
|CUU/Epic|1. Consumir servicios<br>2. Cancelación de reserva|
|Otros|1. Envío de recordatorio de reserva por email|

