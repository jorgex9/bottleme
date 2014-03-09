bottleme
========

BottleMe: Sistema de Mensajes en botellas digitales lanzados a la Red de redes

Description
===========

Partimos de la premisia de que todo usuario de la aplicacione esta en una
isla solitaria, donde puede lanzar mensajes al mar y recojer mensajes en su playa
El usuario no necesita loggearse en la aplicacion de tal manera que todo 
lo que en ella haga es anonima

La aplicacion consta de dos partes principales
	1- Lanzar un mensaje al mar
	2- Recoger un mensaje en la playa

1- Lanzar un mensaje al Mar:
	Esta seccion cuenta con un editor de mensajes de boteela con la opcion de adjuntar una foto (*3)
	este mensaje puede ser firmado con un nomnre o nick (opcional). En su defecto figurara
	como anonimo y se sera lanzado al mar.
	Como opcione el usuario podra elegir el estilo de su botella. Es decir el color o insignia

	
2- Recoger un mensaje en la playa:
	En esta seccion el usuario recoge un mensaje del mar donde puede o no encontrar un mensaje
	en su playa (*1). Una ves que se recoje un mensaje el usuario tiene 4 opciones:

			a- Leerlo
			b- Devolverlo al mar
			c- Destruirlo
			d- Responderlo

a- Al leer el mensaje este queda en un baul de mensajes a la espera de una de las opciones
	siguientes.
b- Devolverlo al mar: en este caso el mensaje no sufre ningun cambio y es devuelto al mar
	con la posibilidad de que le llegue a alguien mas.
c- Destruirlo: esta opcion destruye el mensaje de forma definitiva eliminandolo del baul de 
	mensajes y sin posibilidad de las otras opciones.
d- Responder el mensaje es la parte mas cuestionable del sistema, dando lugar a dos formas
	de trabajo.

		c.1- Responder el mensaje directamente a quien lo escribio.
		c.2- Responder el mensaje y volver a arrojarlo al mar.

		c.1- Esta primera opcion implica que se debe registrar al usuario que lo envio
			de forma que este pueda recibir directamente el mensaje en su playa. Por lo
			que la aplicacion necesitaria un loggin.
		c.2- Esta segunda opcion es mas realista pues el mensaje es respondido y devuelto al
			mar directamente, dando opcion a que un usuario mas reciba la botella que contiene
			ambos mensajes, con la opcion tambien de responderlo y arrojarlo nuevamente al mar (*2)




Referencias:
*1: Se debe generar un algoritmo de fortuna que genere la probabilidad de encontrar un mensaje.
	Esto es discutible.
*2: Aqui hay que ver si se va a limitar la cantidad de mensajes que pueden ser respondidos en una botella
*3: Las fotos son cargadas a pedido del usuario que recibe el mensaje. Este al recibir el mensaje en botella
	lee el texto y previsualiza un version reducida (en tamaño o calidad) de la imagen que contiene, dando
	opcion de descargarla completamente.