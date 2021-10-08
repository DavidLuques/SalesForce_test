   <h1 align="center">

   `RESOLUCION DE ACTIVIDADES PROPUESTAS EN : SALESFORCE🚀`
       <br> <br>
   </h1> 

# `EJERCICIO 2`

1 _http (hipertext transfer Protocol) es un protocolo de transferencia de datos , donde un cliente realiza una "peticion" y un servidor envia le Respuesta

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

# `EJERCICIO 3`

REQUEST GET A LA URL 👉

![Image text](https://github.com/DavidLuques/SalesForce_test/blob/main/images/img_1.png)

2_REALIZO EL POST A LA URL CON BODY RAW EN JSON 👉

![Image text](https://github.com/DavidLuques/SalesForce_test/blob/main/images/img_2.png)

3_REALIZO UN GET DENUEVO A LA URL 👉

![Image text](https://github.com/DavidLuques/SalesForce_test/blob/main/images/img_3.png)

// La diferencia Percibida es que al producirse el post se inserto nuevamente el usuario pablo mediante el uso de json viajando por POST , y al volver a consultar ya tenemos a pablo guardado en la DB.


////////////////////////////////////////////////////////////////////////////////////////////////

# `EJERCICIO 4`
link de perfil en SalesForce:
<a href="https://trailblazer.me/id/daluques" class="btn btn-suces" target="_blank">Ver online</a>

////////////////////////////////////////////////////////////////////////////////////////////////

# `EJERCICIO 5`

```sh
$ npm start hola que tal aun modificando aqui :P
```
![Image text](https://github.com/DavidLuques/SalesForce_test/blob/main/images/diagrama1.png)

1.	Lead:

Es un potencial cliente, por ende una oportunidad de negocio que es necesario atender bajo varios recursos a fin de que sea un cliente, lead es una persona que solicita informacion y con cierto interes, aunque todavia es un contacto no calificado, demuestra incertidumbrey dudas aun por resolver.

2.	Account:

utilizadas para almacenar informacion de clientes o individuos con lo cual Realizas negocios. hay 2 tipos de cuentas : de Empresa/negocio que guarda informacion de las companias, y personal que almacena informacion acerca de personas individuales, es la organizacion/individuo a la que planeas vender.


3.	Contact:

Asociadas usualmente a Account, pueden tambien estar asociadas a otros registros como opportunity y mas , esta nos permite una manipulacion mas versatil , se les puede asignar ciertos contenidos compartidos y ciertas jerarquias, es la persona 'calificada' para realizar negocios contigo

4.	Opportunity:

 No es una persona ni una entidad comercial, Es una posible venta futura para una cuenta en la que desea trabajar o realizar un seguimiento, las probabilidades son altas , son utilizados para predecir las ventas 

5.	Product:

productos son cosas que generan ingresos a la compania, sin importar si son o no tangibles

6.	PriceBook:

Es una lista de productos y sus precios, pueden ser lista de precio standard y lista de precios costomizado, util por ejemplo para diferentes segmentos mercados , o cuando los precios varian de clientes Nacionales a Internacionales.

7.	Quote:

Son los precios propuestos por los producto/servicios ofrecido por la empresa, son creadas a partir de una oportunidad, donde cada oportunidad pueden tener multiples cotizaciones (quotes)

8.	Asset:

Los activos representan productos específicos que han comprado clientes, Se utliza activos para almacenar información sobre los productos de clientes, se pueden trackear los productos vendidos almacenando informacion

9.	Case:

Un case es un feedback,pregunta ,problema planteado por un cliente , donde son requeridas acciones , estas se utilizan para retroalimentar y mejorar el proceso de venta .

10.	Article:

Los articles son documentos con informacion como porejemplo como restaurar un producto , o las preguntas mas frecuentes. Los articulos son publicados y se pueden usar tanto interna como externamente, compartir en Sitios web , etc..


# `EJERCICIO 6`


