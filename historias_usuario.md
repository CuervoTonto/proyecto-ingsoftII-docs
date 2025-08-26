# Historias de usuario

## Historia #001

**como** empleado **quiero** poder iniciar sesion **para** acceder a las funcionalidades de la aplicacion

**Estimacion:** 5

### Criterios de aceptacion

1. [ ] **Datos incorrectos**

- **Dado que:** quiero autenticarme
- **Cuando:** ingrese datos incorrectos
- **Entonces:** fallara la autenticacion

2. [ ] **Datos faltantes**

- **Dado que:** quiero autenticarme
- **Cuando:** no propocione los datos requeridos
- **Entonces:** fallara la autenticacion

3. [ ] **Primer ingreso**

- **Dado que:** me autentique correcamente
- **Cuando:** sea mi primer ingreso al sistema
- **Entonces:** debo establecer una contraseña de acceso

***

## Historia #002

**como** mesero **quiero** registrar los pedidos de los clientes **para** que la cocina obtenga la informacion requerida para la preparacion de los platos

**Estimacion:** 8

### Criterios de aceptacion

1. [ ] **Toma de pedido sin seleccion de mesa**

- **Dado que:** Quiero tomar el pedido de un cliente
- **Cuando:** No seleccione una mesa
- **Entonces:** No me sera posible crear el pedido

2. [ ] **Toma de pedido con informacion valida**

- **Dado que:** Quiero tomar el pedido de un cliente
- **Cuando:** Seleccione una mesa disponible
- **Entonces:** El pedido se creara satisfactoriamente

***

## Historia #003

**como** mesero **quiero** poder cancelar los creados **para** reflejar el estado actual de los pedidos

**Estimacion:** 3

### Criterios de aceptacion

1. [ ] **Cancelacion de un pedido completado** 

- **Dado que:** decida eliminar un pedido
- **Cuando:** el estado del pedido sea "completado"
- **Entonces:** no se permite la eliminacion del pedido

2. [ ] **Cancelacion de un pedido entregado**

- **Dado que:** decida eliminar un pedido
- **Cuando:** el estado del pedido sea "entregado"
- **Entonces:** no se permite la eliminacion del pedido

3. [ ] **Cancelacion de un pedido estado valido**

- **Dado que:** decida eliminar un pedido
- **Cuando:** el pedido no se encuentre completado
- **Entonces:** el pedido es eliminado exitosamente

***

## Historia #005

**como** mesero **quiero** visualizar la informacion basica de los pedidos creados junto a sus respectivos estados **para** poder obtener rapidamente informacion sobre los pedidos

**Estimacion:** 3

***

## Historia #006

**como** bartender **quiero** visualizar una lista con los pedidos del area de bar **para** facilitar la navegacion y busqueda entre los distintos pedidos

**Estimacion:** 3

***

## Historia #007

**como** bartender **quiero** poder acceder a la informacion detallada de un pedido **para** preparar correctamente el pedido del cliente

**Estimacion:** 3

***

## Historia #008

**como** bartender **quiero** marcar un pedido como preparado **para** dar a conocer a las partes interesadas sobre el estado actual del pedido

**Estimacion:** 3

### Criterios de aceptacion

1. [ ] **Estado de completado a preparado**

- **Dado que:** quiera cambiar el estado de un pedido
- **Cuando:** el estado del pedido sea "completado"
- **Entonces:** no se efectua el cambio

2. [ ] **Estado de pendiente a preparado**

- **Dado que:** quiera cambiar el estado de un pedido
- **Cuando:** el estado del pedido sea "pendiente"
- **Entonces:** el estado es actualizado correctamente

***

## Historia #009

**como** jefe de cocina **quiero** visualizar un listado con los pedidos del area de cocina **para** facilitar la navegacion y busqueda entre los diferentes pedidos

**Estimacion:** 3

***

## Historia #010

**como** jefe de cocina **quiero** poder acceder a la informacion detallada de un pedido **para** preparar correctamente el pedido del cliente

**Estimacion:** 3

***

## Historia #011

**como** jefe de cocina **quiero** marcar un pedido como "preparado" **para** dar a conocer a las partes interesadas sobre el estado actual del pedido

**Estimacion:** 3

### Criterios de aceptacion

1. [ ] **Estado de completado a preparado**

- **Dado que:** quiera cambiar el estado de un pedido
- **Cuando:** el estado del pedido sea "completado"
- **Entonces:** no se efectua el cambio

2. [ ] **Estado de pendiente a preparado**

- **Dado que:** quiera cambiar el estado de un pedido
- **Cuando:** el estado del pedido sea "pendiente"
- **Entonces:** el estado es actualizado correctamente

***

## Historia #012

**como** administrador **quiero** poder crear productos **para** enriquecer el catalogo y las posibles opciones para el menu del dia

**Estimacion:** 5

### Criterios de aceptacion

1. [ ] **Crear un producto sin los datos necesarios**

- **Dado que:** quiera crear un producto
- **Cuando:** no proporcione la informacion pertinente
- **Entonces:** no se podra crear el producto

2. [ ] **Crear un producto con datos incorrectos**

- **Dado que:** quiera crear un producto
- **Cuando:** no proporcione la informacion en el formato requerido
- **Entonces:** no se podra crear el producto

3. [ ] **Crear un producto con nombre en uso**

- **Dado que:** quiera crear un producto
- **Cuando:** propocione un nombre que ya se encuentre en uso por otro producto
- **Entonces:** no se podra crear el producto

***

## Historia #013

**como** administrador **quiero** poder eliminar un producto **para** mantener un catalogo limpio

**Estimacion:** 3

***

## Historia #014

**como** adminsitrador **quiero** poder cambiar la informacion de un producto **para** mantenerla actualizada

**Estimacion:** 5

### Criterios de aceptacion

1. [ ] **Actualizar un producto con datos incorrectos**

- **Dado que:** quiera cambiar la informacion de un producto
- **Cuando:** no proporcione la informacion en el formato requerido
- **Entonces:** no se podra actualizar la informacion del producto

2. [ ] **Actualizar un producto con nombre en uso**

- **Dado que:** quiera cambiar la informacion de un producto
- **Cuando:** propocione un nombre que ya se encuentre en uso por otro producto
- **Entonces:** no se podra actualizar la informacion del producto

***

## Historia #015

**como** administrador **quiero** poder visualizar el listado de los productos **para** mantenerme informado de los productos del restaurante

**Estimacion:** 3

### Criterios de aceptacion

1. [ ] **Filtrado por nombre**

- **Dado que:** quiera visualizar un listado de productos y opte por filtrar
- **Cuando:** ingrese como dato el nombre para un producto
- **Entonces:** solo se visualizaran los productos que coincidan con el nombre del producto

2. [ ] **Filtrado por categoria**

- **Dado que:** quiera visualizar un listado de productos y opte por filtrar
- **Cuando:** ingrese como dato la(s) categoria(s) para los productos
- **Entonces:** solo se visualizaran los productos que pertenescan a la categoria

***

## Historia #016

**como** administrador **quiero** poder obtener la informacion detallada de un producto **para** consultar la informacion actual de un producto

**Estimacion:** 3

***

## Historia #017

**como** administrador **quiero** poder crear un menu del dia **para** designar los productos que estaran en venta 

**Estimacion:** 5

### Criterios de aceptacion

1. [ ] **Agregar un producto ya presente**

- **Dado que:** quiera crear un nuevo menu del dia
- **Cuando:** incluya dos (2) veces un mismo producto en el mismo
- **Entonces:** solo se tomara una (1) vez el producto y el menu sera creado satifcatoriamente

***

## Historia #018

**como** administrador **quiero** poder modificar un menu del dia **para** mantener al dia las opciones en el menu

**Estimacion:** 8

### Criterios de aceptacion

1. [ ] **Agregar un producto ya presente**

- **Dado que:** quiera actualizar el menu del dia
- **Cuando:** incluya un producto que ya se encuentre presente
- **Entonces:** solo se tomara una (1) vez el producto y el menu sera creado satifcatoriamente

***

## Historia #019

**como** administrador **quiero** poder crear una categoria **para** obtener un nuevo elemento para enriquecer la informacion de los productos

**Estimacion:** 5

### Criterios de aceptacion

1. [ ] **Datos faltantes**

- **Dado que:** quiera crear una categoria
- **Cuando:** no incluya todos los datos requeridos
- **Entonces:** no se creara la categoria

2. [ ] **Datos incorrectos**

- **Dado que:** quiera crear una categoria
- **Cuando:** los datos no cumplan con el formato necesario
- **Entonces:** no se creara la categoria

3. [ ] **Nombre en uso**

- **Dado que:** quiera crear una categoria
- **Cuando:** el nombre de la categoria ya se encuentre en uso
- **Entonces:** no se permitira la creacion de la categoria

***

## Historia #020

**como** administrador **quiero** poder eliminar una categoria **para** poder gestionar de manera efectiva mis categorias

**Estimacion:** 2

***

## Historia #021

**como** administrador **quiero** poder visualizar un listado con las categorias disponibles **para** obtener la informacion de las categorias disponibles

**Estimacion:** 2

***

## Historia #022

**como** administrador **quiero** poder asignar una categoria a un producto **para** enriquecer la informacion del producto

**Estimacion:** 3

***

## Historia #023

**como** administrador **quiero** remover una categoria de un producto **para** mantener actualizada la informacion de un producto

**Estimacion:** 3

***

## Historia #024

**como** administrador **quiero** poder crear un nuevo empleado **para** agregar un nuevo usuario y permiterle acceder al sistema

**Estimacion:** 5

***

## Historia #025

**como** administrador **quiero** poder modificar la informacion de un empleado **para** mantener actualizados los datos del empleado

**Estimacion:** 5

***

## Historia #026

**como** administrador **quiero** poder eliminar un empleado **para** gestionar de manera efectiva mis empleados

**Estimacion:** 2

***

## Historia #027

**como** administrador **quiero** poder obtener la informacion detallada de un empleado **para** conocer los datos actuales del empleado

**Estimacion:** 3

***

## Historia #028

**como** administrador **quiero** poder asignar roles a un empleado **para** designar las responsabilidades y funciones del empleado

**Estimacion:** 3

### Criterios de aceptacion

1. [ ] **Rol ya presente**

- **Dado que:** quiera agregar roles a un empleado
- **Cuando:** agrege roles con los que ya cuenta el empleado
- **Entonces:** no se contaran los roles "duplicados" y se asignaran correctamente los demas roles

***

## Historia #029

**como** administrador **quiero** poder remover roles de un empleado **para** designar las responsabilidades y funciones del empleado

**Estimacion:** 5

***

## Historia #030

**como** administrador **quiero** poder iniciar sesion **para** tener acceso a las funcionalidades que me corresponden en el software

**Estimacion:** 3

### Criterios de aceptacion

1. [ ] **Datos incorrectos**

- **Dado que:** quiero autenticarme
- **Cuando:** no propocione los datos con el formato requerido
- **Entonces:** fallara la autenticacion

2. [ ] **Datos faltantes**

- **Dado que:** quiero autenticarme
- **Cuando:** no propocione los datos requeridos
- **Entonces:** fallara la autenticacion

3. [ ] **Credenciales incorrectas**

- **Dado que:** quiero autenticarme
- **Cuando:** no propocione las credenciales correctas para el inicio de sesion
- **Entonces:** fallara la autenticacion

## Historia #031

**como** administrador **quiero** poder crear una mesa **para** establecer los puntos de atencion de mis meseros

**Estimacion:** 5

### Criterios de aceptacion

1. [ ] **Numero de mesa repetido**

- **Dado que:** quiero crear una nueva mesa
- **Cuando:** proporcione un numero de mesa que ya se encuentre en uso
- **Entonces:** no se permitira la creacion de la nueva mesa

## Historia #032

**como** administrador **quiero** poder eliminar una mesa **para** poder llevar una mejor gestion de las mesas

**Estimacion:** 5

### Criterios de aceptacion

1. [ ] **Pedidos afectados**

al elminar un mesa los pedidos asociados a la mesa no se veran alterados
