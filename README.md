# PruebaBack
Cambios en el back-end: (Faltan guardar en el GitHub real)
- queries.js  : Nuevo query 'Perfil'
- algoritms.js: Nueva función 'perfil'
- index.js    : Agregado 'router.get('/perfil', algrmts.perfil)'

Cambios en el front-end: (Faltan guardar en el GitHub real)
- API.js          : Se conecta con el back-end local, no con el que esta desplegado en heroku (Cambiar cuando termine las pruebas)
- global/Login.js : Aqui se recuperará el perfil y se enviara al localStorage
- Content.js	  : Se recupera el perfil del localStorage para desactivar los botones y al cerrar sesión se borra el perfil del localStorage	

Cambios en la BBDD:
- Creada la function 'obtener_perfil' para recuperar el perfil de un usuario (Ya esta en la BD)

Error:
- Cuando la función 'perfil' de algoritms.js recibe el parametro del 'req.body.username' no recupera el perfil

Deploys:

- FrontEnd: https://prueba1front.herokuapp.com
- BackEnd: https://prueba1back.herokuapp.com
