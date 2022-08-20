# API-sequelize-mysql

Los verbos HTTP comúnmente utilizados son GET, POST, PUT y DELETE.

GET para obtener datos del servidor o mejor conocido como READ, POST para CREAR nuevos datos, PUT para ACTUALIZAR datos y DELETE para eliminar datos.

O mejor conocido como CRUD (Crear-Leer-Actualizar-Eliminar).

En este tutorial, compartiré cómo hacer una API RESTful simple para recuperar datos del servidor (GET), crear nuevos datos en el servidor (POST), actualizar datos en el servidor (PUT) y eliminar datos en el servidor ( DELETE) de una tabla en la base de datos, a saber, la tabla " productos ".

Aquí está el diseño EndPoint de la API RESTful que crearemos:

| Methods | Urls | 	Actions |
| :---         |     :---      |          :--- |
| GET   | /products     | List of products    |
| GET     | /products/{id}       | View a product      |
| POST    | /pruducts       | Create new product      |
| PUT     | /products/{id}       | Update a product      |
| DELETE     | /products/{id}       | Delete a product      |

# POSTMAN

<img src="https://mfikri.com/assets/images/files/en/sequelize/create-product.png" width="950" title="hover text">
<img src="https://mfikri.com/assets/images/files/en/sequelize/read-all-products.png" width="950" title="hover text">
<img src="https://mfikri.com/assets/images/files/en/sequelize/read-single-product.png" width="950" title="hover text">
<img src="https://mfikri.com/assets/images/files/en/sequelize/create-product.png" width="950" title="hover text">
<img src="https://mfikri.com/assets/images/files/en/sequelize/create-product.png" width="950" title="hover text">
