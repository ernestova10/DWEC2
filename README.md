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

### - Un análisis de los mecanismos de integración de los lenguajes de marcas con los lenguajes de programación de clientes web

La integración de lenguajes de marcas, como HTML y XML, con lenguajes de programación de clientes web, como JavaScript, es fundamental para el desarrollo de aplicaciones web interactivas y dinámicas.

**Mecanismo de integración**

1. Manipulación del DOM
   - **Descripción:** El DOM es una representación estructurada del documento HTML o XML que permite a los lenguajes de programación acceder y manipular su contenido y estructura.
   - **Implementación:** JavaScript puede interactuar con el DOM para modificar elementos, atributos y estilos en tiempo real.

2. Eventos y Listeners
   - **Descripción:** Los eventos permiten que los lenguajes de programación respondan a las acciones del usuario, como clics, movimientos del ratón o entradas de teclado.
   - **Implementación:** JavaScript utiliza listeners para detectar eventos y ejecutar funciones específicas.

3. AJAX
   - **Descripción:** AJAX permite la actualización de partes de una página web sin recargarla completamente, mejorando la experiencia del usuario.
   - **Implementación:** Utilizando el objeto XMLHttpRequest o la API Fetch, JavaScript puede enviar y recibir datos de un servidor de manera asíncrona.

4. JSON
   - **Descripción:** JSON es un formato de intercambio de datos ligero y fácil de leer que se utiliza comúnmente en lugar de XML.
   - **Implementación:** JavaScript puede convertir objetos JSON en objetos JavaScript y viceversa.

**Consideraciones para la Elección de Tecnologías**

1. Compatibilidad y Soporte
   - Asegurarse de que las tecnologías elegidas sean compatibles con los navegadores y dispositivos objetivo es crucial para evitar problemas de compatibilidad.
2. Rendimiento
   - Evaluar el impacto en el rendimiento de la aplicación, especialmente en dispositivos móviles y conexiones lentas.
3. Facilidad de Uso y Mantenimiento
   - Optar por tecnologías que faciliten el desarrollo y mantenimiento del código, como frameworks y librerías bien documentadas y con una comunidad activa.
4. Seguridad
   - Implementar prácticas de seguridad para proteger los datos y prevenir vulnerabilidades comunes, como ataques XSS (Cross-Site Scripting).

### - La evaluación de herramientas de programación para clientes web, funciones y ventajas.

1. React
   - **Funciones:** Biblioteca de JavaScript para construir interfaces de usuario.
   - **Ventajas:** Componentes reutilizables, virtual DOM para mejorar el rendimiento y gran comunidad y ecosistema de herramientas

2. Angular
   - **Funciones:** Framework de desarrollo web basado en TypeScript.
   - **Ventajas:** Arquitectura MVC (Modelo-Vista-Controlador), inyección de dependencias y soporte para aplicaciones de una sola página (SPA).

3. Vue.js
   - **Funciones:** Framework progresivo de JavaScript.
   - **Ventajas:** Fácil de integrar con otros proyectos, documentación clara y detallada, reactividad y vinculación de datos bidireccional.

4. Visual Studio Code
   - **Funciones** Editor de código fuente.
   - **Ventajas:** Extensiones para múltiples lenguajes y herramientas, depuración integrada y soporte para GIT.

5. Git
   - **Funciones:** Sistema de control de versiones.
   - **Ventajas:** Seguimiento de cambios en el código, colaboración en equipo, integración con plataformas como GitHub y GitLab.

     
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

4. Un análisis de los mecanismos de integración de los lenguajes de marcas con los lenguajes de programación de clientes web

   - [Mecanismos de integración](https://www.eniun.com/lenguajes-marcas-sistemas-gestion-informacion/)

5. La evaluación de herramientas de programación para clientes web, funciones y ventajas.

   - [React, Vue.js, Visual Studio Code, Git](https://tuatara.co/blog/software/herramientas-desarrollo-web/)
   - [Angular](https://blog.hubspot.es/website/que-es-angular)
