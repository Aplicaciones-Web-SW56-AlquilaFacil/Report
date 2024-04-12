# Capítulo IV: Product Design
## 4.1. Style Guidelines.
Un **Style Guideline** es un conjunto de reglas y normas que definen cómo se debe redactar, diseñar o presentar documentos, contenido web, software u otros trabajos creativos. A continuación, se detallan las especificaciones de los parámetros implementados en la estructura del proyecto. 
### 4.1.1. General Style Guidelines

**Overview:** <td>Deseamos capturar la atención del usuario desde el inicio mediante la creación y el diseño de una perspectiva del producto que establezca una conexión inmediata y reconocible.</td>

**Brand overview**

<td>Alquilafacil es un startup tecnológico fundada en el 2024 por un grupo de estudiantes compuesta por un grupo de estudiantes de la carrera de Ingeniería de Software. Nuestro startup está dedicada a simplificar el proceso de alquiler de espacios para eventos, brindando una plataforma innovadora y accesible para propietarios y organizadores por igual.</td>
<br><br>

**Misión:** <td>Nuestra misión es simplificar el proceso de alquiler de espacios para eventos mediante una plataforma intuitiva y eficiente, conectando a propietarios de espacios con organizadores de manera rápiad y conveniente.</td>

**Visión:** <td>Convertirnos en la principal plataforma global de alquiler de espacios para eventos, impulsando la eficiencia y la satisfacción de nuestros usuarios.</td>

**Brand Name:** <td>Como la startup se trata de alquilar centros para eventos y también para publicitar centros que podrían ser alquilados, se vio conveniente llamarlo “AlquilaFacil”.</td>

<img src="assets/Logo.png" alt="AlquilaFacil">

**Typography:** <td>El tamaño elegido para la tipografía por el equipo fue:</td>
<img src="assets/Typography-stylesheet.png" alt="AlquilaFacil">

<td>Y sus modificaciones han sido de:</td>
<img src="assets/Typography Modifiers-stylesheet.png" alt="AlquilaFacil">

**Colors:** <td>La gama de colores elegidos son:</td>
<img src="assets/Colors-stylesheet.png" alt="AlquilaFacil">

### 4.1.2. Web Style Guidelines
<td>AlquilaFacil se diseñará como plataforma web, por lo tanto, aplicaremos un diseño adaptable (Web Responsive Design) con el objetivo de presentar la información de manera óptima en cualquier dispositivo, asegurando que el contenido permanezca intacto para mejorar la experiencia del usuario.</td>
<br><br>
<td>Además, como equipo, hemos elegido implementar el patrón de diseño en forma de Z en el sitio web. Esta técnica de diseño web resulta efectiva para mejorar la experiencia del usuario al dirigir su atención hacia los elementos clave y potenciar la eficacia del contenido en la página. Por lo general, colocamos el logotipo en la esquina superior izquierda para que sea lo primero que capte la atención del usuario. Justo en frente, en la esquina superior derecha, ubicamos la barra de navegación, acompañado de un llamado a la acción que se destaca.</td>

## 4.2. Information Architecture
<td>Esta sección se basa principalmente del contenido visual, los estilos, los tags y más que se tomarán en cuenta para nuestra web y landing page de AquilaFacil. Se verá los tópicos de Organization Systems, Labeling Systemes, SEO and Meta Tags y Searching y Navigation Systems.</td>

### 4.2.1. Organization Systems
**Menú Principal**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Inicio</td>
            <td style="text-align: left">La página de inicio puede mostrar una vista general del servicio y destacar las características clave.</td>
        </tr>
        <tr>
            <td>Tarifas</td>
            <td style="text-align: left">La página que ofrece los planes de suscripción para beneficios específicos con diferentes costos para cualquier tipo de presupuesto.</td>
        </tr>
        <tr>
            <td>Log In</td>
            <td style="text-align: left">La página para que el usuario ingrese a su sesión. En caso de no tener sesión hay una sección para poder registrarse gratis al servicio web.</td>
        </tr>
        <tr>
            <td>Publicar centro</td>
            <td style="text-align: left">La página primero te va pedir iniciar sesión para poder identificar el usuario que quiere publicar su propiedad. Luego se mostrará una ventana en donde se pondrá todos los datos y características de la propiedad.</td>
        </tr>
        <tr>
            <td>Alquilar centro</td>
            <td style="text-align: left">La página primero te mostrará centros ya publicados y que se pueden alquilar. Sin embargo, también se presenta una barra de búsqueda con filtros para buscar los centros más idóneos de manera mucho más rápida y eficaz.</td>
        </tr>
         <tr>
            <td>Barra de búsqueda</td>
            <td style="text-align: left">En la misma página principal se muestra una barra para poder buscar centros a través de distritos.</td>
        </tr>
         <tr>
            <td>Lista de centros destacados</td>
            <td style="text-align: left">La página principal te mostrará todo una lista de los centros más usados y populares que el público ha usado para sus eventos.</td>
        </tr>
    </body>
</table>

**Página de Tarifas**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Lista de planes de suscripción</td>
            <td style="text-align: left">La página mostrará todos los planes que ofrece el servicio.</td>
        </tr>
        <tr>
            <td>Detalles de planes</td>
            <td style="text-align: left">La página mostrará los detalles de todos los planes que ofrece el servicio.</td>
        </tr>
    </body>
</table>

**Página de Log In**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Registro y autenticación</td>
            <td style="text-align: left">La página de inicio puede mostrar una vista general del servicio y destacar las características clave.</td>
        </tr>
    </body>
</table>

**Página de Publicar centro**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Paso 1</td>
            <td style="text-align: left">La página mostrará todos los detalles que se deben poner sobre el centro que el propietario quiere alquilar.</td>
        </tr>
        <tr>
            <td>Paso 2</td>
            <td style="text-align: left">La página muestra las características que se deben agregar para el anuncio de la propiedad a alquilar sea como el propietario quiera que se vea.</td>
        </tr>
        <tr>
            <td>Paso 3</td>
            <td style="text-align: left">La página mostrará los planes para mantener su anuncio en alquiler y el usuario decidirá que plan usará.</td>
        </tr>
    </body>
</table>

**Página de Alquilar centro**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Filtros de búsqueda</td>
            <td style="text-align: left">Permite a los usuarios filtrar los resultados por ubicación, tipo de servicio, calificaciones, etc.</td>
        </tr>
        <tr>
            <td>Lista de propiedades</td>
            <td style="text-align: left">Muestra los resultados de la búsqueda con información resumida de cada centro técnico.</td>
        </tr>
        <tr>
            <td>Detalles de propiedades</td>
            <td style="text-align: left">Al hacer clic en un centro técnico, se muestra información detallada, calificaciones y comentarios.</td>
        </tr>
        <tr>
            <td>Comentarios y calificaciones</td>
            <td style="text-align: left">Permite a los usuarios agregar comentarios y calificaciones al servicio.</td>
        </tr>
    </body>
</table>

**Página de favoritos:** <td>Muestra los centros en alquiler marcados como favoritos por el usuario.</td>

**Otras páginas y funciones**
<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Perfil de usuario</td>
            <td style="text-align: left">Permite a los usuarios gestionar su perfil y la información personal.</td>
        </tr>
        <tr>
            <td>Configuraciones</td>
            <td style="text-align: left">Permite a los usuarios y técnicos configurar sus preferencias.</td>
        </tr>
        <tr>
            <td>Pagina acerca de nosotros</td>
            <td style="text-align: left">Información sobre la empresa o la aplicación.</td>
        </tr>
        <tr>
            <td>Ayuda y soporte</td>
            <td style="text-align: left">Recursos de ayuda, preguntas frecuentes y opciones de asistencia.</td>
        </tr>
    </body>
</table>

**Barra de navegación:** <td>Una barra de navegación clara y consistente en la parte superior de cada página facilita la navegación entre las secciones principales de la aplicación.</td>

**Responsive design:** <td>La aplicación debe ser fácil de usar tanto en dispositivos de escritorio como en dispositivos móviles, adaptando la interfaz de usuario según
el tamaño de la pantalla.</td>

### 4.2.2. Labeling Systems
<td>Para los sistemas de etiquetado, hemos optado por organizar el contenido mediante encabezados que agrupen las secciones a las que el usuario puede acceder. De esta manera, el usuario sabe dónde hacer clic para acceder a las secciones correspondientes.</td>

<table style="text-align:center">
    <thead>
        <tr>
            <th style="text-align:center">Tópico</th>
            <th style="text-align:center">Definición</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td>Inicio</td>
            <td style="text-align: left">Sección principal a la cual llegará el usuario al entrar al link de la aplicación web.</td>
        </tr>
        <tr>
            <td>Acerca de</td>
            <td style="text-align: left">En esta sección proporcionaremos a los usuarios la información necesaria para comprender el propósito de nuestra startup y los servicios que ofrecemos.</td>
        </tr>
        <tr>
            <td>Nosotros</td>
            <td style="text-align: left">Aquí el usuario podrá conocer quienes son los integrantes del proyecto y una descripción de ellos.</td>
        </tr>
        <tr>
            <td>Precios</td>
            <td style="text-align: left">En esta sección, se podrán ver los planes y tarifas disponibles con los cuales contamos.</td>
        </tr>
        <tr>
            <td>Testimonios</td>
            <td style="text-align: left">Aquí los clientes pondrán sus reseñas y comentarios acerca del servicio que se les brindó.</td>
        </tr>
        <tr>
            <td>Contacto</td>
            <td style="text-align: left">Esta es la sección en la cual se le brindará al usuario todos los canales por los cuales nos puede contactar.</td>
        </tr>
    </body>
</table>

### 4.2.3. SEO Tags and Meta Tags
<td>Las meta etiquetas nos permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las leen. Estas etiquetas facilitan el análisis de archivos HTML y ayudan en el mantenimiento del contenido. Además, influyen en el posicionamiento de nuestra página en los motores de búsqueda.</td>
<br><br>

**Titulo** 
<br>
<td>Las meta etiquetas nos permiten codificar y especificar metadatos en una página web. Aunque no son visibles para los usuarios, los navegadores y rastreadores web las leen. Estas etiquetas facilitan el análisis de archivos HTML y ayudan en el mantenimiento del contenido. Además, influyen en el posicionamiento de nuestra página en los motores de búsqueda.</td>

`<title>Register your processes with AlquilaFacil</title>`

**Codificación de caracteres** 
<br>
<td>Se decidió usar el utf-8 por la eficiencia de memoria. Es más eficiente en términos de memoria para caracteres del BMP (Plano Multilingüe Básico, que incluye la mayoría de los caracteres comunes).</td>

`<meta charset="utf-8">` 

**Descripción** 
<br>
<td>Esta etiqueta meta nos permite ofrecer un resumen del contenido de la página web. En ella, proporcionamos una breve descripción de lo que los usuarios pueden esperar visualizar en la página.</td>

`<meta name="description" content="AlquilaFacil is a web application focused on plublish and rent centers for events"/>` 

**Palabras clave** 
<br>
<td>En esta etiqueta se pone las palabras claves relacionadas con el tema o contenido de la página web.</td>

`<meta name="keywords" content="publish, rent, management, application, announcements, centers"/>` 

**Autor y derechos de autor** 
<br>
<td>Se utiliza para registrar la información del autor de la página web y la propiedad y derechos de autor.</td>

`<meta name="author" content="AlquilaFacil"/>` <br>
`<meta name="copyright" content="Copyright AlquilaFacil team" />` 

### 4.2.4. Searching Systems
<td>El motor de búsqueda es fundamental para que los usuarios encuentren rápidamente detalles específicos</td>
<br><br>

**Características claves**
- *Busqueda por ubicación:* <td>Los usuarios podrán buscar centros para eventos cercanos a su ubicación actual o especificar una ubicación deseada.</td>
- *Busqueda por características:* <td>Los usuarios podrán buscar características específicos, como piscina, parrilla, pet friendly, vigilancia.</td>
- *Filtros avanzados:* <td>Se proporcionarán filtros para refinar la búsqueda, como calificaciones, precios y disponibilidad.</td>
- *Resultados revelantes:* <td>El sistema de búsqueda mostrará resultados revelantes y oirdenaelos de acuerdo con la ubicación y otros criterios</td>

### 4.2.5. Navigation Systems
<td>El Sistema de Navegación es la estructura que permite a los usuarios desplazarse eficientemente entre las distintas secciones y páginas de la aplicación</td>
<br><br>

**Estructura de navegación:** <td> El Sistema de Navegación constará de las siguientes secciones principales en la barra de navegación</td>

- Inicio
- Tarifas
- Publicar centro
- Iniciar sesión
  
<td>Luego la vista del usuario va a la opción "Alquilar centro" para al final ir a un panel con centros destacados.</td>


## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
**Landing Page para Desktop Web Browser**
<img src="assets/LandingPage-wireframe-desktop.png">

**Landing Page para Mobile Web Browser**
<img src="assets/LandingPage-wireframe-mobile.png">

### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.3. Web Applications Mock-ups
### 4.4.4. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
A continuación, se visualizarán los diagramas C4.
### 4.6.1. Software Architecture Context Diagram
Se puede visualizar el diagrama de contexto que representa un panorama general de la comunicación entre nuestros segmentos objetivo y la aplicación.

![contextDiagram](assets/contextDiagram.png)
### 4.6.2. Software Architecture Container Diagrams
En este diagrama se puede apreciar el funcionamiento que tendrá la aplicación y las relaciones con los bounded context correspondientes, se busca organizarlos de tal forma que no generen dependencias fuertes que perjudiquen migraciones a future.

![containerDiagram](assets/containerDiagramA.png)
### 4.6.3. Software Architecture Components Diagrams
En este diagrama se presenta de forma detallada las conexiones entre controllers, services y repositories de las entidades que contiene el bounded context.

<p style="text-align: center;"><strong>User Context</strong></p>

![componentDiagram](assets/userContextA.png)

<p style="text-align: center;"><strong>Subscription Context</strong></p>

![componentDiagram](assets/subscriptionContextA.png)

<p style="text-align: center;"><strong>Space Context</strong></p>

![componentDiagram](assets/spaceContextA.png)

<p style="text-align: center;"><strong>CreateReservation Context</strong></p>

![componentDiagram](assets/createReservationContextA.png)

<p style="text-align: center;"><strong>Reservations Context</strong></p>

![componentDiagram](assets/reservationsContextA.png)

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

![diagramClass](assets/diagramClass.png)

### 4.7.2. Class Dictionary

<table style="text-aling:center">
    <thead>
        <tr>
            <th>Clase</th>
            <th>Descripción</th>
        </tr>
    </thead>
    <body>
        <tr>
            <td> 
            <img src="assets/userC.png" alt="userClass" height="200" width="200">
            </td>
            <td>Es la clase padre de las clases Organizer y Owner, es la encargada de almacenas los datos del usuario</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/ownerC.png" alt ="ownerC" height="120">
            </td>
            <td>La clase Owner hereda de la clase User. Representa a los propietarios de los espacios que pueden ser alquilados para eventos.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/organizerC.png" alt ="organizerC" height="120">
            </td>
            <td>La clase Organizer hereda de la clase User. Representa a los organizadores de eventos que buscan y reservan espacios para sus eventos.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/reservationC.png" alt ="reservationC" height="200" width="200">
            </td>
            <td>Gestiona las reservas realizadas por organizadores para espacios de eventos específicos.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/eventSpaceC.png" alt ="eventSpaceC" height="200" width="200">
            </td>
            <td>Representa los espacios físicos disponibles para alquiler. Proporciona información detallada sobre el espacio, como ubicación, capacidad y características.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/paymentsC.png" alt ="paymentsC" height="200" width="200">
            </td>
            <td>Representa los pagos asociados a las reservas de espacios de evento. Registra información sobre el monto, la fecha y el estado de los pagos realizados.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/subscriptionC.png" alt ="subscriptionC" height="200" width="200">
            </td>
            <td>Representa las suscripciones de los propietarios a planes de servicio que ofrecen beneficios adicionales.</td>
        </tr>
        <tr>
            <td> 
            <img src="assets/plansC.png" alt ="plansC" height="200" width="200">
            </td>
            <td>Define los diferentes niveles de suscripción disponibles para los propietarios de espacios.</td>
        </tr>
    </body>
</table>    

## 4.8. Database Design.
### 4.8.1. Database Diagram.

![dataBaseDiagram](assets/dataBaseDiagram.png)