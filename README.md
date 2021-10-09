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



# `EJERCICIO 7` 
`Soluciones De SalesForce`

A.	¿Qué es Salesforce?

Sales force es un sistema CMR (custom Managment Relationship), ayuda a gestionar mejorando relaciones comerciales con Clientes y Potenciales clientes, Optimiza procesos y mejora la rentabilidad , permite conectar con Clientes es un sistema basado en la nube , permite la suspervision de actividades de la empresa, y la Recopilacion de datos  para detectar oportunidades y mas . Contiene Varios modulos como : SalesClod , Service Cluod,Marketing Cloud , etc...

B.	¿Qué es Sales Cloud?

Sales Cloud es una aplicacion basada en la nube usada para companias enfocadas en potenciales clientes, ventas , oportunidades, fidelizar clientes , se orienta mas a las ventas o potenciales clientes : Web-toLead

C.	¿Qué es Service Cloud?

Service Cloud incluye todo lo que sales Cloud puede ofrecer y se extiende , permite automatizar proceso de servicios,los usuarios estan mas centrados al servicio se orienta mas a los casos: Web-toCase , es una diferente licencia a la de Sales Cloud

D.	¿Qué es Health Cloud?

Healt Cloud es la plataforma orientada a la relacion medico-Paciente , Reune informacion variada y de Distintas fuentes aportando una vision amplia de cada paciente , logrando una atencion mss rapida y personalizada ,permite la gestion de los datos clinicos y el acceso en tiempo real . Los pacientes pueden utilizar tambien la plataforma obteniendo informacion y/o rellenando formularios 

E.	¿Qué es Marketing Cloud?

Es una plataforma que centraliza las comunicaciones con los clientes sobre multiples canales, Compuesta por varias Subclouds como :Mobile Studio , Email Studio,etc...  permite la recoleccion de datos de clientes a fines estadisticos de muchos lugares y la centralizacion de esos datos ,tambien permite Automatizaciones en cada Subcloud 

Funcionalidades de Salesforce
A.	¿Qué es un RecordType?
B.	¿Qué es un ReportType?
C.	¿Qué es un Page Layout?
D.	¿Qué es un Compact Layout?
E.	¿Qué es un Perfil?
F.	¿Qué es un Rol?
G.	¿Qué es un Validation Rule?
H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?
I.	¿Qué es un Sandbox?
J.	¿Qué es un ChangeSet?
K.	¿Para qué sirve el import Wizard de Salesforce?
L.	¿Para qué sirve la funcionalidad Web to Lead?
M.	¿Para qué sirve la funcionalidad Web to Case?
N.	¿Para qué sirve la funcionalidad Omnichannel?
O.	¿Para qué sirve la funcionalidad Chatter?
Conceptos generales
A.	¿Qué significa SaaS? 
B.	¿Salesforce es Saas?
C.	¿Qué significa que una solución sea Cloud?
D.	¿Qué significa que una solución sea On-Premise?
E.	¿Que es un pipeline de ventas?
F.	¿Que es un funnel de ventas?
G.	¿Qué significa Customer Experience?
H.	¿Qué significa omnicanalidad?
I.	¿Qué significa que un negocio sea B2B?
J.	¿Qué significa que un negocio sea B2C?
K.	¿Qué es un KPI?
L.	¿Qué es una API y en qué se diferencia de una Rest API?
M.	¿Qué es un Proceso Batch?
N.	¿Qué es Kanban?
O.	¿Qué es un ERP? 
P.	¿Salesforce es un ERP?



