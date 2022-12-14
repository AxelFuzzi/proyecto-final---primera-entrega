## Proyecto Final- Primera entrega
 


#### Rutas: 

 ##### Productos

 * **Obtener todos los productos**
    * `GET` | /productos/listar
  
 * **Obtener un producto**
    * `GET` |  /productos/listar/:id 
 
 * **Crear un nuevo producto**
    * `POST` |  /productos/agregar
 
 * **Actualizar  producto**
    * `PUT` |  /productos/actualizar/:id
 
 * **Eliminar producto**
    * `DELETE` |  /productos/borrar/:id
 
 ##### Carrito

* **Obtener todos los productos del carrito con los campos id y timestamps de carrito**
    * `GET` | /carrito/listar
  
 * **Obtener un producto del carrito con los campos id y timestamps de carrito**
    * `GET` |  /carrito/listar/:id 
 
 * **Agregar al carrito**
    * `POST` |  /carrito/agregar/:id_producto
 
 * **Eliminar item del carrito**
    * `DELETE` |  /carrito/borrar/:id

Para ejecutar en local:   
`npm start`



 


*by Axel Fuzzi.*

