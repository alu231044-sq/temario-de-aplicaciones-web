# temario-de-aplicaciones-web
1.- introduccion del desarollo web: 

El desarrollo web comenzó a finales de los años 80 y principios de los 90, cuando Tim Berners-Lee inventó la World Wide Web (WWW) en 1989. La primera página web se publicó en 1991 y consistía en información sobre el propio proyecto WWW.

## Evolución por décadas

### Años 90: Los comienzos

- **HTML básico:** Las primeras páginas web eran estáticas, creadas solo con HTML.
- **Navegadores iniciales:** Mosaic y Netscape fueron los primeros navegadores populares.
- **CSS y JavaScript:** En 1996 se introdujo CSS para mejorar el diseño visual y JavaScript para interactividad.

### Años 2000: Dinamismo y expansión

- **Lenguajes de servidor:** Tecnologías como PHP, ASP y JSP permitieron crear sitios dinámicos.
- **Bases de datos:** Se empezó a usar MySQL y otros sistemas para almacenar información.
- **Web 2.0:** Se popularizó el concepto de sitios interactivos y comunidades en línea (redes sociales, blogs, wikis).

### Años 2010: Modernización y movilidad

- **Frameworks y librerías:** Surgieron herramientas como jQuery, Angular, React y Vue.js para simplificar el desarrollo.
- **Responsive Design:** El diseño adaptable a dispositivos móviles se volvió esencial.
- **Aplicaciones web avanzadas:** Web apps como Gmail y Facebook impulsaron la innovación.

### Años 2020 y actualidad

- **Single Page Applications (SPA):** Aplicaciones web que funcionan como una sola página y ofrecen experiencias similares a las apps móviles.
- **APIs y microservicios:** Integración con servicios externos y arquitectura modular.
- **Desarrollo full-stack:** Uso combinado de tecnologías de front-end y back-end.
- **WebAssembly, Progressive Web Apps (PWAs):** Nuevas tecnologías para mejorar rendimiento y experiencia de usuario.

## Principales hitos tecnológicos

- **1991:** Publicación de la primera página web.
- **1995:** Lanzamiento de JavaScript.
- **1998:** Nacimiento de PHP.
- **2004:** Surgimiento de AJAX para mejorar la interactividad.
- **2014:** Lanzamiento de React.js.
- **2017:** Popularización de Progressive Web Apps.
- <img width="200" height="480" alt="image" src="https://github.com/user-attachments/assets/5ade2203-59eb-4947-bf33-8d8b3c893953" />


El desarrollo web ha evolucionado para ofrecer diferentes tipos de aplicaciones, cada una con características y tecnologías específicas. A continuación se describen los principales tipos:

## 1. Aplicaciones web estáticas

- **Descripción:** Son sitios web cuyo contenido no cambia en función de la interacción del usuario ni de factores externos. Cada página se muestra tal cual fue creada.
- **Tecnologías:** HTML, CSS, imágenes.
- **Ventajas:** Rápidas, fáciles de desarrollar y desplegar.
- **Ejemplos:** Portafolios, páginas informativas sencillas, landing pages.

## 2. Aplicaciones web dinámicas

- **Descripción:** El contenido puede cambiar en respuesta a acciones del usuario o datos externos. Suelen interactuar con bases de datos y servidores.
- **Tecnologías:** HTML, CSS, JavaScript, lenguajes de servidor (PHP, Python, Node.js), bases de datos (MySQL, MongoDB).
- **Ventajas:** Personalización, interactividad, gestión de datos.
- **Ejemplos:** Blogs, tiendas en línea, redes sociales.

## 3. Single Page Application (SPA)

- **Descripción:** Son aplicaciones web que funcionan en una sola página; la navegación y actualización de contenido se realiza sin recargar la página completa.
- **Tecnologías:** JavaScript avanzado, frameworks como React, Angular, Vue.js.
- **Ventajas:** Experiencia de usuario rápida y fluida, menor consumo de ancho de banda.
- **Ejemplos:** Gmail, Facebook, Trello.

## 4. Progressive Web Apps (PWA)

- **Descripción:** Aplicaciones web que ofrecen funcionalidades similares a las aplicaciones móviles nativas, como acceso sin conexión, notificaciones push y posibilidad de instalarse en el dispositivo.
- **Tecnologías:** JavaScript, Service Workers, Manifest, frameworks modernos.
- **Ventajas:** Experiencia nativa en la web, instalación en el dispositivo, rendimiento optimizado.
- **Ejemplos:** Twitter Lite, Pinterest, Uber.

2.-ARQUITECTURA DE APLICACIONES WEB

cliente servidor:Es un modelo en el que dos entidades principales interactúan:

Cliente: Es el dispositivo o aplicación que utiliza el usuario final (por ejemplo, un navegador web). Solicita servicios o recursos al servidor.
Servidor: Es el sistema que almacena, procesa y responde a las solicitudes del cliente. Puede manejar múltiples clientes al mismo tiempo.

Arquitectura de tres capas:La arquitectura de tres capas es un modelo ampliamente utilizado en el desarrollo de aplicaciones web modernas. Este modelo separa la aplicación en tres niveles independientes, facilitando su mantenimiento, escalabilidad y seguridad.

## 1. Capa de Presentación (Front-End)

- **Descripción:** Es la interfaz con la que interactúa el usuario. Se encarga de mostrar la información y recibir la entrada del usuario.
- **Tecnologías:** HTML, CSS, JavaScript, frameworks como React, Angular, Vue.js.
- **Responsabilidad:** Presentar datos de forma amigable y captar las acciones del usuario (clics, formularios, etc.).

## 2. Capa de Lógica de Negocio (Back-End / Middleware)

- **Descripción:** Procesa las reglas de negocio, gestiona la lógica de la aplicación y controla el flujo de información entre la presentación y los datos.
- **Tecnologías:** Node.js, PHP, Python (Django/Flask), Java (Spring), Ruby on Rails, entre otros.
- **Responsabilidad:** Validar datos, ejecutar cálculos, procesar transacciones y coordinar la comunicación entre la presentación y la base de datos.

## 3. Capa de Datos (Base de Datos)

- **Descripción:** Se encarga del almacenamiento y recuperación de la información utilizada por la aplicación.
- **Tecnologías:** Bases de datos relacionales (MySQL, PostgreSQL), NoSQL (MongoDB, Redis).
- **Responsabilidad:** Guardar, actualizar, eliminar y consultar datos de forma eficiente y segura.

REST y API-first design: Las APIs (Application Programming Interfaces) permiten la comunicación entre diferentes sistemas y aplicaciones. Dos enfoques clave en el desarrollo moderno de aplicaciones web son REST y el diseño API-first.

## ¿Qué es REST?

REST (Representational State Transfer) es un estilo de arquitectura para diseñar servicios web que aprovechan los estándares y protocolos de la web, especialmente HTTP.

### Principios de REST

- **Recursos identificables:** Cada recurso (por ejemplo, usuarios, productos) tiene una URL única.
- **Operaciones estándar:** Se usan los métodos HTTP (GET, POST, PUT, DELETE) para interactuar con los recursos.
- **Sin estado:** Cada solicitud contiene toda la información necesaria; el servidor no guarda contexto entre llamadas.
- **Interfaz uniforme:** Las comunicaciones siguen reglas consistentes y predecibles.
- **Uso de formatos estándar:** JSON y XML son los formatos de intercambio de datos más comunes.

3.-LENGUAJES Y TECNOLOGIAS FUNDAMENTALES: 
HTLM:HTML (HyperText Markup Language) es el lenguaje de marcado principal utilizado para crear la estructura básica de las páginas web. Todos los sitios y aplicaciones web comienzan con HTML, que define los elementos visuales y el contenido que el navegador debe mostrar.

CSS:CSS (Cascading Style Sheets) es el lenguaje utilizado para definir la presentación y el diseño visual de las páginas web. Permite separar el contenido (HTML) del aspecto visual, facilitando la creación de sitios atractivos y responsivos.
