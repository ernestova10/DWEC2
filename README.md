# Aplicación de deportes
## Informe técnico
### - Análisis de modelo cliente/servidor

Este modelo es fundamental en el desarrollo de una aplicación web. El modelo Cliente-Servidor es una aquitectura de comunicación en la que el cliente solicita servicios y el servidor proporciona esos servicios que requiere el cliente.
1. Componentes claves
   
     **- Cliente:** Es la parte que inicia las solicitudes de servicio. En una aplicación web, el cliente es el navegador que     envía peticiones HTTP al servidor.
   
     **- Servidor:** Es el componente que proporciona los servicios solicitados por el cliente. Procesa las peticiones y envía   una respuesta al cliente.

2. Tipos de arquitecturas

     **- Modelo de dos capas:** En este modelo, el cliente se comunica directamente con el servidor. Es simple pero puede ser     ineficiente si el número de clientes es muy alto.
   
     **- Modelo de tres capas:** En este modelo, hay una capa intermedia la cual es conocida como lógica de negocio. Esta         mejora la escabilidad y la gestión de la aplicación.
   
     **- Modelo multicapa:** Similar al modelo de tres capas, pero con más capas intermedia para manejar diferentes aspectos de   la aplicación, como la seguridad, la lógica de negocio y la presentación.

3. Objetivo de la arquitectura cliente-servidor

      El objetivo principal de esta arquitectura es realizar la separación de las funciones y responsabilidades del software en    distintas capas. Los beneficios de esta separación de responsabilidades son diversos.            Entre ellos podemos destacar la posibilidad de escalar o mantener aplicaciones por separado y también la posibilidad de utilizar infraesctructuras           distintas y especializadas en cada una de las                    partes del software.

4. Ventajas e inconvenientes del modelo cliente-servidor

     **- Ventajas:** Facilita la adminisración de los datos y la seguridad de la información, mejora la escabilidad, permite un   mantenimiento individual de las capas del software, mejora la felxibilidad de usos de las aplicaciones y permite un          desarrollo menos dependiente.

     **- Inconvenientes:** Requiere el uso de red para funcionar, si el servidor falla, a menudo impacta en los clientes y        están expuestos a una red en la cuál puede haber posibilidades de ataques de seguridad.

### - Evolución lenguajes de programación, ventajas y desventajas
1. HTML

   **- Ventajas:**
   - Simplicidad: Fácil de aprender y usar.
   - Compatibilidad: Compatible con todos los navegadores web.
   - SEO: Facilita la optimización para motores de búsqueda.

   **- Desventajas:**
   - Estático: No permite la creación de contenido dinámico por sí solo.
   - Limitado: Necesita de otros lenguajes como CSS y JavaScript para mejorar funcionalidades y diseño.

2. CSS
   
   **- Ventajas:**
   - Estilo y diseño: Permite separar el contenido del diseño, facilitando la creación de páginas web atractivas.
   - Reutilización: Los estilos pueden ser reutilizados en múltiples páginas.
   
   **- Desventajas:**
   - Compatibilidad: Algunas propiedades pueden no ser compatibles con todos los navegadores.
   - Complejidad: Puede volverse complejo en proyectos grandes sin una buena organización.

3. JavaScript

   **- Ventajas:**
   - Interactividad: Añade dinamismo e interactividad a las páginas web.
   - Versatilidad: Utilizable tanto en el lado del cliente como en el servidor.
   
   **- Desventajas:**
   - Seguridad: Puede ser vulnerable a ataques como XSS.
   - Rendimiento: Puede afectar el rendimiento si no se optimiza de la manera adecuada.

4. Java
   
   **- Ventajas:**
   - Portabilidad: Se puede ejecutar en cualquier lugar gracias a la JVM.
   - Madurez: Ecosistema robusto y bien establecido.
   - Seguridad: Ofrece seguridad avanzada.
   
   **- Desventajas:**
   - Verbosidad: Requiere escribir mucho código para tareas simples.
   - Rendimiento: Las aplicaciones de escritorio pueden no ser tan rápidas como las nativas.

5. Web Scraping (con Python)
   
   **- Ventajas:**
   - Automatización: Facilira la extracción de datos de sitios web.
   - Bibliotecas: Herramientas como BeautifulSoup y Scrapy simplifican el proceso.
   
   **- Desventajas:**
   - Legalidad: Puede haber problemas legales si se realiza sin permiso.
   - Bloqueos: Los sitios web pueden bloquear los scrapers.

6. SQL
   
   **- Ventajas:**
   - Eficiencia: Ideal para manejar grandes volúmenes de datos.
   - Estándar: Amplia adopción y soporte en múltiples sistemas de gestión de bases de datos.
   
   **- Desventajas:**
   - Complejidad: Puede ser complejo de aprender para principiantes.
   - Escabilidad: Puede tener limitaciones en aplicaciones distribuidas.

### - Un estudio sobre la compatibilidad en navegadores

La compatibilidad entre navegadores es un aspecto crucial en el desarrollo web, ya que asegura que una aplicación o sitio web funcione correctamente en diferentes navegadores y dispositivos.

1. Problemas comunes de compatibilidad

   - **Validación de HTML y CSS:** Diferentes navegadores pueden interpretar el código HTML y CSS de manera distinta. Un error común puede ser etiquetas no cerradas que hace que dee problemas en algunos navegadores.
   - **Falta de Resets CSS:** Los navegadores aplican sus propios estilos por defecto, lo que puede causar inconsistencias  en el diseño.
   - **Errores de DOCTYPE:** La ausencia de una declaración DOCTYPE puede hacer que los navegadores más antiguos tenga problemas a la hora de presentar la página.
   - **Problemas con JavaScript:** Diferentes motores de JavaScript pueden ejecutar el código de manera distinta, lo que puede causar errores o comportamientos inesperados.

2. Soluciones
   - **Herramientas de validación:** Utilizar herramientas como W3C HTML Validator y Jugsaw CSS Validator para asegurar que el código esté libre de errores.
   - **Hojas de Estilo Reset:** Implementar hojas de estilo como Normalize.css para asegurar una base consistente en todos los navegadores.
   - **Pruebas automatizadas:** Utilizar herramientas como Selenium y BrowserStack para realizar pruebas automatizadas en múltiples navegadores y dispositivos.
   - **Diseño Responsivo:** Adoptar frameworks como Bootstrap o Foundation que facilitan la creación de diseños responsivos y compatibles.

### - Bibliografía
1. Cliente-servidor
   
   - [Análisis de modelo cliente/servidor](https://www.arsys.es/blog/todo-sobre-la-arquitectura-cliente-servidor)

2. Evolución de lenguajes de programación, ventajas y desventajas.

   - [HTML y CSS](https://www.registrodominiosinternet.es/2013/08/lenguajes-programacion-web-ventajas.html)
   - [JavaScript 1](https://itcwebsolutions.com/desarrollo-y-soporte-web/programacion-y-herramientas/lenguajes-de-programacion/ventajas-y-desventajas-de-los-principales-lenguajes-de-programacion/)
   - [JavaScript 2](https://blog.hubspot.es/website/ventajas-y-desventajas-de-javascript)
   - [Java](https://itcwebsolutions.com/desarrollo-y-soporte-web/programacion-y-herramientas/lenguajes-de-programacion/ventajas-y-desventajas-de-los-principales-lenguajes-de-programacion/)
   - [Web Scraping](https://proxy-seller.com/es/blog/web_scraping_vs_web_crawling_ventajas_y_desventajas/)

3. Un estudio sobre la compatibilidad en navegadores

   - [Problemas comunes de compatibilidad](https://comparium.app/es/blog/cross-browser-compatibility-issues/)
   - [Soluciones](https://guiasopensource.net/herramientas-de-desarrollo/pruebas-compatibilidad-crossbrowser-codigo-abierto-desafios-soluciones/)
   - [Soluciones2](https://comparium.app/es/blog/cross-browser-compatibility-issues/)
