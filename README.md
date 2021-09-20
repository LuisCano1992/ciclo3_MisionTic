SalesWeb - Project
---

**Descripcion**

Se propone analizar, diseñar y construir una aplicación software que permita `controlar las ventas físicas y virtuales de una empresa de manufactura y hacerles el correspondiente seguimiento.`


**Arquitectura Propuesta**

Se propone la siguiente arquitectura:
![Captura](https://user-images.githubusercontent.com/90949069/133953345-3eb1f81d-857a-44c5-a2ed-b9a402cd0435.PNG)

**Metodologia de desarollo:** **`SCRUM`**


**MODULOS DEL PROYECTO**
---

| Modulo | Descripción |
|------|------|
| Administrador de ventas | Permite ingresar o registrar los pedidos realizados por cada uno de los clientes. Deberá tener un identificador único de venta, almacenar el valor total de la venta y la descripción detallada de la misma y tener una fecha inicial y una fecha futura de pago. Además, deberá contar con un encargado de gestionar dicha venta (responsable). |
|Registrar el estado de la venta|Permite establecer los diferentes estados de la venta a lo largo del ciclo de vida de la línea de producción (creación, embalaje, despacho, ruta, ubicación, recepción). |
|Gestión de vendedores|Permite ingresar la información básica de los vendedores que participan en un negocio de ventas. La información a registrar sería el identificador único del vendedor, el nombre, la especialidad, el número de celular y la fecha de ingreso.|
|ingreso al sistema de información|El sistema contendrá una pantalla de ingreso con login y password. - Este módulo hará la integración de los demás módulos del sistema para garantizar que los roles de los usuarios se ajusten a las distintas opciones de cada menú o formulario. Se contempla la identificación y el desarrollo de los casos de uso relacionados con la seguridad, así como el análisis de requisitos y el diseño del módulo.|
|Gestión de usuarios y roles|Deberá contener un identificador único del usuario, el nombre y el rol en el sistema de información (vendedor, administrador, ejecutivo, operario, director, gerente comercial) con el fin de restringir/otorgar accesos al sistema de información.|





