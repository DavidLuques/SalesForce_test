          RESOLUCION DE ACTIVIDADES PROPUESTAS EN : SALESFORCE🚀

EJERCICIO2

1 \_http (hipertext transfer Protocol) es un protocolo de transferencia de datos , donde un cliente realiza una "peticion" y un servidor envia le Respuesta

2_los verbos http mas conocidos son post y get , son metodos de peticion para ultilizar en un determinado recurso

3_un request es una peticion al servidor del cliente (navegador) en la barra de direcciones HTTP, URL y version, response es la respuesta de este.

4_querystring (cadena de consulta )con las que contienen los parametros para que la pagina web sea tambien una aplicacion web, es decir sea interactiva a los usuarios, conecta a la BBDD

5_el response code es la respuesta que se obtiene al solicitar al realizar alguna peticion y pueden ser varias , por ejemplo error en el servidor,en los clientes, respuestas informativas y sastifactorias , etc... existe una lista grande con codigos correspondientes a cada caso , de manera organizada

6_En el metodo Get se recuperan datos por medio de la URL, en el Post no sino que se trabaja en el servidor, por ejemplo en el caso de las password,un formulario por get podría revelar nuestra contrasenia.

7_utiliza el metodo get que es solo lectura , y no son modificados del lado del servidor

8\_ json, javascript objet notation es un formato de texto independiente del lenguaje de Programacion que usa un formato conocido por todos por lo cual favorece el intercambio de datos
[ { "nombre": "enriquepenia", "edad": 45, "ejercita": true },
{ "nombre": "estebanquito", "edad": 15, "ejercita": false }]
se compone de dos partes , un nombre y un valor ,
XML es un lenguaje de marcado, utiliza la estructura de marcado para representar elementos de dato,tiene etiquetas de inicio y finalización.
<persona><nombre>elisa perez</Nombre>
<edad>64</edad>
<ejercita>si</ejercita></persona>
XML utiliza etiquetas para definir el contenido y el signficado de la información.
esta mas extendido el uso de json al ser mas rapido y de sencilla sintaxis

9\_ soap es un protocolo ligero para intercambio de informacion, define como dos objetos en diferentes procesos pueden comunicarse por medio de intercambio de datos XML

10_el estandar rest es una arquitectura cliente/servidor en el protocolo http, que expresa :servicio web sin estado,acceso a recursos por URL,uso de json o XML, rest ful es la api que se basara en esta arquitectura y utilizara sus estandares

11_los headers es donde estan los datos de las cookies, Son esquemas de key:value y contienen información sobre el http request y el navegador
La key ,Content-Type dice el tipo de contenido devuelto al cliente

////////////////////////////////////////////////////////////////////////////////////////////////

EJERCICIO3

REQUEST GET A LA URL

![Image text](https://github.com/DavidLuques/SalesForce_test/blob/main/images/img_1.png)

2_REALIZO EL POST A LA URL CON BODY RAW EN JSON

![Image text](https://github.com/DavidLuques/SalesForce_test/blob/main/images/img_2.png)

3_REALIZO UN GET DENUEVO A LA URL

![Image text](https://github.com/DavidLuques/SalesForce_test/blob/main/images/img_3.png)

// La diferencia Percibida es que al producirse el post se inserto nuevamente el usuario pablo mediante el uso de json viajando por POST , y al volver a consultar ya tenemos a pablo guardado en la DB.


////////////////////////////////////////////////////////////////////////////////////////////////

EJERCICIO4
link de perfil en SalesForce:
<a href="https://trailblazer.me/id/daluques" class="btn btn-suces" target="_blank">Ver online</a>



Comenzando 🚀
Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.

Mira Deployment para conocer como desplegar el proyecto.

Pre-requisitos 📋
Que cosas necesitas para instalar el software y como instalarlas

Da un ejemplo
Instalación 🔧
Una serie de ejemplos paso a paso que te dice lo que debes ejecutar para tener un entorno de desarrollo ejecutandose

Dí cómo será ese paso

Da un ejemplo
Y repite

hasta finalizar
Finaliza con un ejemplo de cómo obtener datos del sistema o como usarlos para una pequeña demo

Ejecutando las pruebas ⚙️
Explica como ejecutar las pruebas automatizadas para este sistema

Analice las pruebas end-to-end 🔩
Explica que verifican estas pruebas y por qué

Da un ejemplo
Y las pruebas de estilo de codificación ⌨️
Explica que verifican estas pruebas y por qué

Da un ejemplo
Despliegue 📦
Agrega notas adicionales sobre como hacer deploy

Construido con 🛠️
Menciona las herramientas que utilizaste para crear tu proyecto

Dropwizard - El framework web usado
Maven - Manejador de dependencias
ROME - Usado para generar RSS
Contribuyendo 🖇️
Por favor lee el CONTRIBUTING.md para detalles de nuestro código de conducta, y el proceso para enviarnos pull requests.

Wiki 📖
Puedes encontrar mucho más de cómo utilizar este proyecto en nuestra Wiki

Versionado 📌
Usamos SemVer para el versionado. Para todas las versiones disponibles, mira los tags en este repositorio.

Autores ✒️
Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios

Andrés Villanueva - Trabajo Inicial - villanuevand
Fulanito Detal - Documentación - fulanitodetal
También puedes mirar la lista de todos los contribuyentes quíenes han participado en este proyecto.

Licencia 📄
Este proyecto está bajo la Licencia (Tu Licencia) - mira el archivo LICENSE.md para detalles

Expresiones de Gratitud 🎁
Comenta a otros sobre este proyecto 📢
Invita una cerveza 🍺 o un café ☕ a alguien del equipo.
Da las gracias públicamente 🤓.
etc.
