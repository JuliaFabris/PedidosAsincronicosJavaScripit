# Pedidos asincrónicos con JavaScript

En home.html: listar todas las películas que nos trae el endpoint de listado de
películas: router.get('/', moviesAPIController.list);
● En formulario.html: cargar los datos de una película en particular, para luego
poder modificarla y/o eliminarla utilizando los endpoints:
○ Detalle de una película: router.get('/:id', moviesAPIController.detail);
○ Modificar una película: router.put('/update/:id', moviesAPIController.update);
● Utilizar el mismo formulario anterior para poder crear una película por medio del
endpoint: router.post('/create', moviesAPIController.create);