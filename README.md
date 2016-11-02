# Clase_WS


Clase pasada: Session y cookies
	Ver EjemploAjax
	
	*******************************
	Usar .then en todo AJAX de PHP.
	*******************************


Cliente:

HTML
- Botón que muestre un alert "hola"
- Botón que muestre alert con 3 datos

- Debe tener los campos para ABM de CDs.
- Haciendo click en el botón, se pasan los datos por POST a nexo.php
- Muestra el botón de Crear.
- Mostrar la grilla, con botones de Borrar y Modificar.

JS
- AJAX



Servidor:

nexo.php
- Crearlo a partir de ws_5/index.php
- Crear el cliente WS
- Consume el WS.
- Recibe los datos desde el html inicial por POST
- Al volver al html inicial (AJAX) se borra el formulario de ingreso de datos y se muestran dos botones: "Mostrar grilla" y "Mostrar ingreso".

WS
- Crear/server.
- Creo que le falta el método InsertarCd().
- Tiene que tener métodos de ABM y listado (consulta).


Clase CD
- PDO
