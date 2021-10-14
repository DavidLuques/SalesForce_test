   <h1 align="center">

   `RESOLUCION DE ACTIVIDADES PROPUESTAS EN : SALESFORCE🚀`
       <br> <br>
   </h1> 

# `EJERCICIO 1`

Contaba ya con Vs Code , Git , este Readme fue commiteado desde Vs Code

# `EJERCICIO 2`

1 _http (hipertext transfer Protocol) es un protocolo de transferencia de datos , donde un cliente realiza una "peticion" y un servidor envia le Respuesta

2_los verbos http mas conocidos son post y get , son metodos de peticion para ultilizar en un determinado recurso

3_un request es una peticion al servidor del cliente (navegador) en la barra de direcciones HTTP, URL y version, response es la respuesta de este.

4_querystring (cadena de consulta )con las que contienen los parametros para que la pagina web sea tambien una aplicacion web, es decir sea interactiva a los usuarios, conecta a la BBDD

5_el response code es la respuesta que se obtiene al solicitar al realizar alguna peticion y pueden ser varias , por ejemplo error en el servidor,en los clientes, respuestas informativas y sastifactorias , etc... existe una lista grande con codigos correspondientes a cada caso , de manera organizada

6_En el metodo Get se recuperan datos por medio de la URL, en el Post no sino que se trabaja en el servidor, por ejemplo en el caso de las password,un formulario por get podría revelar nuestra contrasenia. el Metodo get es para solicitudes a servidores y obtener informacion solicitada , es un metodo del protocolo HTTP

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

///////////////////////////////////////////////////////////////////////////////////////////////

# `EJERCICIO 6` 

'en desarrollo'


///////////////////////////////////////////////////////////////////////////////////////////////

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

`Funcionalidades de Salesforce`

A.	¿Qué es un RecordType?

son basicamente diferentes registros ofrecidos a los usuarios que seran diferentes en su disenio, valores de lista de seleccion, etc..

B.	¿Qué es un ReportType?

Actua como una plantilla que facilita la confeccion de un reporte, determina cuales campos y registros estaran disponibles para la creacion del reporte basado en la relacion entre el objeto primario y sus objetos relacionados

C.	¿Qué es un Page Layout?

Los disenios de pagina controlan : disenio , organizacion de campos,botones, determinan que campos son o no visibles , lectura obligatoria 

D.	¿Qué es un Compact Layout?

compact Layout controlan los campos que aparecen en el encabezado de pagina ,se pueden poner hasta 10 por objeto , vienen predeterminados con la opcion de agregar/quitar .

E.	¿Qué es un Perfil?

Los perfiles definen cómo acceden los usuarios a objetos y datos y qué pueden hacer en la aplicación. existen perfiles estandar aunque se pueden crear otros 

F.	¿Qué es un Rol?

los roles controlan la visibilidad que tendra un usuario sobre los datos de su organizacion, mientras mayor sea la visibiliada  tambien mayor sera su jerarquia. 

G.	¿Qué es un Validation Rule?

es la regla de validacion que asegura que los datos que ingrase un usuario cumpla la "norma especifica propuesta" antes de guardar el registro.

H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?

La diferencia es que la realacion master-detail es una relacion donde detail tiene "herencia" del master , es decir tiene una fuerta depandencia , es necesario indicarle cual es el master , si se elimina el master , tambien desaparcec el Detail , se pueden crar hasta 2 master  en 1 objeto.  En cambio Lookup  crea una relacion entre 2 objetos, si eliminamos alguno de los 2 objetos el otro no sera eliminado , no tiene una relacion jerarquica como la anterior.


I.	¿Qué es un Sandbox?

es una copia de la organizacion en un entorno aislado para pruebas , capacitacion. No estan en produccion por lo cual su modificacion no afectara en produccion

J.	¿Qué es un ChangeSet?

Es un conjunto de cmabios para enviar desde una organizacion de salesforce a otra , por ejemplo de un sandbox pasarla a produccion .

K.	¿Para qué sirve el import Wizard de Salesforce?

Es para la importacion de datos como objetos , objetos customizados , permite la importacion de 50.000 records a la vez

L.	¿Para qué sirve la funcionalidad Web to Lead?

Sirve para canalizar los visitantes y convertirlos en clientes potenciales a travez de formularios donde ingresan datos de ellos e intereses quizas a cambio de un webinar, pdf, etc..


M.	¿Para qué sirve la funcionalidad Web to Case?

sirve para la recopilacion de solicitudes de asistencia de clientes desde el sitio web de la organizacion , ayuda a la organizacion a responder mas rapidamente por parte del equipo de soporte.

N.	¿Para qué sirve la funcionalidad Omnichannel?

sirve para relacionarse con un cliente a travez de un canal y tenga la capacidad de finalizar y mantener en otros canales, busca unificar todos los canales de la empresa en uno solo a fin de mejorar la practicidad.

O.	¿Para qué sirve la funcionalidad Chatter?

Sirve para trabajar juntos con multiples usuarios en tiempo real compartiendo informacion , permitiendo la comunicacion, permite la realizacion de seguimiento de personas , grupos , temas , en salesforce cuenta con una aplicacion mobile.


`Conceptos generales`

A.	¿Qué significa SaaS? 

El acronomo SaaS (Software as a service) es un modelo de negocio de pago en forma de suscripcion por lo gral donde el proveedor de servicios en la nube se encarga de todo lo relacionado al manejo de Software y hadware , garantizando la seguridad y disponibilidad de la aplicacion y sus datos. es una Ventaja por que permite la facil y rapida puesta en marcha  con un pago minimo.

B.	¿Salesforce es Saas?

SalesForce es Saas ya que ofrece tanto el almacentamiento como la gestion en la nube garantizando su correcto funcionamiento , y lo respectivo a su implementacion .

C.	¿Qué significa que una solución sea Cloud?

Una solucion cloud, cloud computing es la contratacion de servicios que en oposicion a on-premise esta se aloja en la nube ,por lo cual no se requiere un equipo TI para su mantenimiento.

D.	¿Qué significa que una solución sea On-Premise?

Basicamente trata de que la empresa sea la responsable de la seguridad, disponibilidad, y gestion del Software, por lo cual la empresa debe contar con un Derpartamento de sistemas que gestione la ingfraestructura. La inversion inicial es mayor

E.	¿Que es un pipeline de ventas?

Es una herramienta de Gestion de ventas para observar las etapas de ventas en ciclos medios o largos, es el seguimiento cercano de las etapas de la venta tales como : la captacion del cliente, la prospeccion, propuesta ,el cierre y las posventa.  el pipeline son las acciones realizadas para convertir un Lead en un Cliente.

F.	¿Que es un funnel de ventas?

Un embudo de ventas es una representacion visual de la fase del proceso de venta, es decir las etapas que el cliente pasa  desde el conocimiento hacia  la compra , uno conocido es el modelo AIDA  awareness => interest => desire => Actiom

G.	¿Qué significa Customer Experience?

Es la experiencia que el usuario se genero, imagen mental a travez de sensaciones y emociones que percibio durante y despues de la compra

H.	¿Qué significa omnicanalidad?

es la estrategia de comunicacion para mantener el contacto con Prospects y clientes en diversos canales (redes sociales, web, email,etc..) entontrando una interaccion unificada de los diferentes canales

I.	¿Qué significa que un negocio sea B2B?
Business to Business es el negocio de empresa a empresa , por lo cual la forma de presentar el producto sera distina al cliente, no sera a un consumidor final, en este segmento se suele presentar el producto dejando de lado emociones , el mercado ya posee conocimiento, las negociaciones son mas prolongadas, es importante estableceer relaciones durareras ya que el mercado es mas chico


J.	¿Qué significa que un negocio sea B2C?

Business to customer es el negocio empresa a cliente , aca la cantidad de clientes es mayor , se evocan las emociones en los clientes, el proceso de compra debe ser rapido , se utilizan publicidades para la construccion de la imagen .

K.	¿Qué es un KPI?
El key Perfomance Indicator son indicadores de clave de desempenio, son metricas que evaluan la eficacia de los pasos realizados en el negocio ,con el fin de la retroalimentacion y mejora del proceso interno.

L.	¿Qué es una API y en qué se diferencia de una Rest API?

Rest es un tipo de arquitectura web que determina como usar el protocolo HTTP y las URL para estructurar un API, es decir que estructura el comportamiento de CLientes y sevidores, API es un conjunto de protocolos implementados para establecer comunicacion entre distintos componentes de Software, unos esjemplos serian el servicio de google Maps,  la integracion de Videos de Youtube a paginas web

M.	¿Qué es un Proceso Batch?

El Proceso en lotes o batch, no necesita de la interaccion con el usuario, es el procesamiento de grandes volumenes de datos y trabajos repetitivos, que hacerlo manualmente seria tedioso.
ejemplos son el renderizado, el procesamiento de las transacciones del movimiento en una tarjeta de credito , que no es perceptible el gasto sino hasta 2 semanas despues , donde el batch sucede y se procesan todos los datos en un momento "mas" oportuno.

N.	¿Qué es Kanban?

kanban es un sistema que reduce la "procrastinacion" en todas las areas de la empresa , es un sistema de gestion  , control de inventario y flujo de componentes, basadas en referencias visuales donde se utilizan papeles de colores para facilitar la comunicacion de los funcionarios ante la facilidad de interpretacion  de los datos por parte de estos. En el area de produccion podemos clasificar 3 etapas " -To do   -Doing   -Done " , en un metodo practico se trazaria en una pizarra blanca 3 lineas verticales, con las inscripciones mencionadas anteriormente como titulo, y los "Post-its" que son las tareas irian anotadas en cada columna .

O.	¿Qué es un ERP? 

Enterprise Resource Planning  ayuda a las organizaciones  a gestionar de manera integral todas o gran parte de sus Areas. Es  un unico programa que centraliza los multiples modulos que pueda tener , es decir tiene acceso a base de datos desentralizadas, este sistema da respuestas rapidas a los clientes, permite un manejo eficiente de la informacion minimizando costes

P.	¿Salesforce es un ERP?

SalesForce es un ERP, por que permite de la plataforma configurar triggers , multiples funcionalidades que gestionen envios de correos o otras acciones de otros modulos , tratando asi de ser un sistema integrado avanzado de CMR, que facilite el trabajo no solo a la empresa sino tambien a sus clientes.




///////////////////////////////////////////////////////////////////////////////////////////////
