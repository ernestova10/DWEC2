# Aplicación de deportes
## Informe técnico
**- Análisis de modelo cliente/servidor**
<br> Este modelo es fundamental en el desarrollo de una aplicación web. El modelo Cliente-Servidor es una aquitectura de comunicación en la que el cliente solicita servicios y el servidor proporciona esos servicios que requiere el cliente.
1. Componentes claves
<br> **Cliente:** Es la parte que inicia las solicitudes de servicio. En una aplicación web, el cliente es el navegador que envía peticiones HTTP al servidor.
<br> **Servidor:** Es el componente que proporciona los servicios solicitados por el cliente. Procesa las peticiones y envía una respuesta al cliente.

2. Tipos de arquitecturas
<br> *- Modelo de dos capas:* En este modelo, el cliente se comunica directamente con el servidor. Es simple pero puede ser ineficiente si el número de clientes es muy alto.
<br> *- Modelo de tres capas:* En este modelo, hay una capa intermedia la cual es conocida como lógica de negocio. Esta mejora la escabilidad y la gestión de la aplicación.
<br> *- Modelo multicapa:* Similar al modelo de tres capas, pero con más capas intermedia para manejar diferentes aspectos de la aplicación, como la seguridad, la lógica de negocio y la presentación.

3. Objetivo de la arquitectura cliente-servidor
<br> El objetivo principal de esta arquitectura es realizar la separación de las funciones y responsabilidades del software en distintas capas. Los beneficios de esta separación de responsabilidades son diversos. Entre ellos podemos destacar la posibilidad de escalar o mantener aplicaciones por separado y también la posibilidad de utilizar infraesctructuras distintas y especializadas en cada una de las partes del software.



**- Bibliografía**
https://www.arsys.es/blog/todo-sobre-la-arquitectura-cliente-servidor
