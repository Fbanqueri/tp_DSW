# Propuesta TP DSW

## Grupo
### Integrantes
* 47834 - Banqueri, Federico - federicobanqueri@hotmail.com
* 43081 - Bozio, Rodrigo - rodrigobozio96@gmail.com

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


Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Productos<br>2. CRUD Cliente<br>3. CRUD Ventas<br>|
|CRUD dependiente|1. CRUD Ventas {depende de} CRUD Productos<br>2. CRUD Ventas {depende de} CRUD Clientes|
|Listado<br>+<br>detalle| 1. Listado de productos filtrado por nombre y codigo de barra => detalle CRUD Productos<br> 2. Listados de ventas filtrado por nombre de clientes y fecha  => detalle CRUD Ventas<br>
|CUU/Epic|1. Realizar una venta <br>2. Dar de alta un producto|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. 1. CRUD Productos<br>2. CRUD Cliente<br>3. CRUD Ventas<br>4. CRUD Usuarios|
|CUU/Epic|1. Realizar una venta <br>2. Dar de alta/baja/modificacion un producto<br>3.Dar de alta/baja/modificacion un cliente<br>4.Facturar una venta.|


