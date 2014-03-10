bottleme
========

BottleMe: Sistema de Mensajes en botellas digitales lanzados a la Red de redes

Description
===========

Partimos de la premisia de que todo usuario de la aplicacione esta en una
isla solitaria, donde puede lanzar mensajes al mar y recoger mensajes en su playa
El usuario no necesita loggearse en la aplicación de tal manera que todo 
lo que en ella haga es anónima

La aplicacion consta de dos partes principales
	1- Lanzar un mensaje al mar
	2- Recoger un mensaje en la playa

1- Lanzar un mensaje al Mar:
	Esta sección cuenta con un editor de mensajes de botella con la opción de adjuntar una foto (*3)
	este mensaje puede ser firmado con un nomnre o nick (opcional). En su defecto figurara
	como anónimo y se sera lanzado al mar.
	Como opcion el usuario podrá elegir el estilo de su botella. Es decir el color o insignia

	
2- Recoger un mensaje en la playa:
	En esta sección el usuario recoge un mensaje del mar donde puede o no encontrar un mensaje
	en su playa (*1). Una vez que se recoge un mensaje el usuario tiene 4 opciones:

			a- Leerlo
			b- Devolverlo al mar
			c- Destruirlo
			d- Responderlo

a- Al leer el mensaje este queda en un baúl de mensajes a la espera de una de las opciones
	siguientes.
b- Devolverlo al mar: en este caso el mensaje no sufre ningún cambio y es devuelto al mar
	con la posibilidad de que le llegue a alguien más.
c- Destruirlo: esta opción destruye el mensaje de forma definitiva eliminandolo del baúl de 
	mensajes y sin posibilidad de las otras opciones.
d- Responder el mensaje es la parte más cuestionable del sistema, dando lugar a dos formas
	de trabajo.

		c.1- Responder el mensaje directamente a quien lo escribió.
		c.2- Responder el mensaje y volver a arrojarlo al mar.

		c.1- Esta primera opción implica que se debe registrar al usuario que lo envió
			de forma que este pueda recibir directamente el mensaje en su playa. Por lo
			que la aplicación necesitaria un login.
		c.2- Esta segunda opción es más realista pues el mensaje es respondido y devuelto al
			mar directamente, dando opción a que un usuario mas reciba la botella que contiene
			ambos mensajes, con la opción también de responderlo y arrojarlo nuevamente al mar (*2)




Referencias:
*1: Se debe generar un algoritmo de fortuna que genere la probabilidad de encontrar un mensaje.
	Esto es discutible.
*2: Aqui hay que ver si se va a limitar la cantidad de mensajes que pueden ser respondidos en una botella
*3: Las fotos son cargadas a pedido del usuario que recibe el mensaje. Este al recibir el mensaje en botella
	lee el texto y previsualiza un version reducida (en tamaño o calidad) de la imagen que contiene, dando
	opcion de descargarla completamente.

NOTAS:

1- La aplciación deberá ser ambientada por todos los sentidos:
	a- Toda acción deberá ser acompañada por imágenes de fondo de pantalla representando la ubicación del usuario
	b- Toda acción deberá ser acompañada por efectos de sonidos que ambienten la acción realizada
	c- Toda acción deberá ser acompañada por efectos visuales (una pequeña animación) representando
		la acción realizada.
