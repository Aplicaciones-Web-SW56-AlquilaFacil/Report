# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
A continuación, presentaremos el proceso por el cual organizamos, gestionamos y controlamos los cambios en el 
desarrollo de este proyecto.
### 5.1.1. Software Development Environment Configuration
El software necesita diferentes entornos para su desarrollo, prueba, despliegue y operación. La configuración del 
entorno de implementación de software es una actividad que se ocupa de crear y mantener estos entornos. 
Es por ello que en este apartado detallaremos las herramientas usadas.

1.	Notion:  https://www.github.com/

    Empleamos Github para organizar las actividades que teníamos que realizar, principalmente respecto al desarrollo de 
    este informe. Realizábamos seguimiento del estatus de las actividades, con la facilidad de organizarnos como equipo. 
    Esta es una plataforma que con ayuda de un repositorio permite gestionar de buena manera los proyectos.

2.	Whatsapp: https://web.whatsapp.com/

    Whatsapp es una aplicación que te permite comunicarte por voz y texto con tus amigos y grupos. Se empleó 
    esta herramienta como el medio para realizar coordinaciones de trabajo con los integrantes del equipo.

3.	Visual Studio Code: https://code-visualstudio-com/

    Para el desarrollo nuestro landing page usamos herramientas básicas para el diseño de páginas web como lo son: 
    HTML5, CSS3 y JavaScript.  

4.	Google Docs: https://docs.google.com/document/

    Para el desarrollo del documento y dividir partes entre nosotros usamos Google docs ya que permite editar en un documento
    muchas personas al mismo tiempo.

5.	Figma: https://www.figma.com/

    Usamos esta herramienta para la creación de nuestros Wireframes, mockups y mobile aplication prototyping ya que 
    permite trabajar de manera colaborativa y tiene muchas utilidades.  

### 5.1.2. Source Code Management

El manejo y registro de las modificaciones de nuestra landing page y este documento lo manejamos mediante una organización en Github.
-    Organization: 
-    Landing Page Repository: 
-    Report Repository: 

Además, para mejorar el control de nuestro proyecto usamos GitFlow para la creación de ramas y cambios en el código fuente.
Es por ello que se manejan dos ramas principales: main y develop.
    **Main**: La rama main almacena el historial oficial de las publicaciones de nuestro repositorio listas para producción.
    **Develop**: Esta rama sirve como una rama de integración para las características (“features”).

En nuestro caso hemos implentado la rama develop: "develop". 

Esta rama es la rama principal donde se integran todas las características. Cuando se completa una característica, se fusiona con develop. Todas las ramas de características deben fusionarse con develop.

Ejemplo de flujo de trabajo con GitFlow:
    1.	Se crea una rama de “feature” a partir de la rama develop. 
    2.	Se trabaja en la rama de “feature”.
    3.	Se hace un merge de la rama de “feature” a la rama develop.

**Ramas auxiliares:**

-	**Feature**: Para desarrollar nuevas funcionalidades o mejoras a partir de la rama develop y fusionarlas con ella al terminar. Estas ramas permiten trabajar en el código sin afectar a la estabilidad de la rama develop, y facilitan la revisión y el control de calidad de las características antes de integrarlas.

Para la implemntación de las ramas "features", nosotros hemos implementado la siguiente nomenclatura: "feature/feature-name".

Donde:
    -	Feature: Es el nombre de la rama.
    -	Feature-name: Es el nombre de la característica que se está desarrollando.

Ejemplo Report:
    - "feature/chapter-1.1". Indicando el capitulo a implementar.


**Commit Conventions**

Para el formato de nuestros commits nos hemos basado en la estructura de los “Conventional Commits” en su versión 1.0.0 
(https://www.conventionalcommits.org/en/v1.0.0/).

Seguimos el siguiente formato:
< type >[optional scope]:< description >
“feat: add chapter 1.1”
Donde:
-	Type: Es un identificador que indica el tipo de cambio que se ha realizado en el código. Puede ser uno de los 
siguientes valores: feat, fix, docs, style, refactor, perf, test, build, ci, chore, revert.
-	Scope: Es un identificador opcional que indica el alcance o el contexto del cambio. Puede ser cualquier palabra que 
ayude a diferenciar el cambio de otros similares. Por ejemplo: [login], [navbar], [api], etc.
-	Description: Es una descripción breve y concisa del cambio que se ha realizado. Debe explicar qué se ha hecho y por qué, pero no cómo.

### 5.1.3. Source Code Style Guide & Conventions

Para el desarrollo de la parte de HTML y CSS, seguiremos las convenciones del Google HTML/CSS Style Guide, que nos indica cómo trabajar con estas tecnologías. Algunas de las convenciones que aplicaremos son:
- Declarar siempre el tipo de documento con <DOCTYPE html>
- Usar siempre minúsculas para los nombres de los elementos HTML (como &lt;p&gt;, &lt;h1&gt;, &lt;section&gt;, etc.)
- Cerrar siempre los elementos HTML (por ejemplo, &lt;p&gt; &lt;/p&gt;)
- Poner siempre entre comillas los atributos de los elementos HTML (por ejemplo, &lt;p class="name"&gt;&lt;/p&gt;)
- Evitar líneas de código muy largas
- Usar meta tags al inicio

Para el lenguaje JavaScript, seguiremos las convenciones del Google JavaScript Style Guide. Algunas de las convenciones que aplicaremos son:
- Nombrar las variables y funciones con camelcase, como "numberArray"
- Usar comillas simples para los strings, como 'This is a string'
- Usar punto y coma (; )  al final de cada sentencia
- Evitar declarar variables con var y usar *let* o *const* en su lugar

### 5.1.4. Software Deployment Configuration

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
En esta sección se especifican los detalles del Sprint Planning Meeting, que es una reunión que se lleva a cabo al inicio de cada sprint con la finalidad de establecer las tareas que se realizarán durante el período determinado.

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 1</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            29/03/24         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            10:00 pm         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad remota y coordinacion a traves de Whastapp   
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            AlquilaFacil   
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendess (to planning meeting)</b>
        </td>
        <td>
            Todos los miembros del grupo AlquilaFacil 
        </td>
    </tr>
      </tr>
       <tr align="left">
        <td>
            <b>Sprint n - 0</b>
            <b>Review Summary</b>
        </td>
        <td>
            Se establecieron las primeras historias de usuario centradas en el desarrollo del Landing Page y la implementación 
            de la lógica de funcionamiento para la plataforma AlquilaFacil.
            </br></br>
Se cumplió con éxito el despliegue del Landing Page dentro del plazo acordado.

La documentación se ha enriquecido con la expansión de la visión de negocio y la incorporación de los artefactos correspondientes.   
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 1</b>
            <b>Retrospective Summary</b>
        </td>
        <td>
            En líneas generales, hemos logrado mantener una excelente organización y comunicación como equipo, gracias 
            al uso de plataformas como Google Meet. Sin embargo, siempre hay margen para mejorar aún más nuestra coordinación 
            y colaboración en pos de la excelencia en nuestros proyectos.

Para garantizar un progreso continuo en nuestros proyectos, es esencial que perfeccionemos la estimación del desarrollo 
de los wireframes y mockups. Esto evitará posibles desajustes en nuestro calendario y garantizará un flujo de trabajo más estable.

Debemos hacer un uso más frecuente y consistente del formato Markdown en nuestra documentación y comunicaciones, ya que 
esto facilitará la lectura y comprensión de la información por parte de todos los miembros del equipo.  
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 1 Velocity</b>
        </td>
        <td>
            6
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            9  
        </td>
    </tr>
</table>



#### 5.2.1.2. Sprint Backlog 1

<div align=center>
   <img src="/assets/trelloAF.png" alt="carrusel"></img>
</div>

Link del trello:
https://trello.com/b/aRpjb6j9/alquilafacil

</br>

<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 1</b></td>
     </tr>
     <tr>
       <td colspan="2"><b>User Story</b></td>
       <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
     <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
     </tr>
     <tr>
       <td rowspan="3">US01</td>
       <td rowspan="3">Implementación de CSS</td>
       <td>T01</td>
       <td>Agregar RESET</td>
       <td>Restablecer los estilos predeterminados del navegador</td>
       <td>1</td>
       <td>Italo Luna</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T02</td>
       <td>Agregar CSS main</td>
       <td>Dar formato y estilo a la sección principal</td>
       <td>3</td>
       <td>Josten Marc</td>
       <td>Done</td>
    </tr>
     <tr>
       <td>T03</td>
       <td>Agregar CSS footer</td>
       <td>Dar formato y estilo al pie de página </td>
       <td>2</td>
       <td>Antonio</td>
       <td>Done</td>
    </tr>
    <tr>
       <td rowspan="2">US02</td>
       <td rowspan="2">Implementación de Diseño Responsivo</td>
       <td>T04</td>
       <td>Agregar CSS main (media queries)</td>
       <td>Hacer responsive a la sección principal</td>
       <td>1</td>
       <td>Brenda Gamio</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T05</td>
       <td>Agregar CSS footer (media queries)</td>
       <td>Hacer responsive al pie de página
    </td>
       <td>0.5</td>
       <td>Italo Luna</td>
       <td>Done</td>
    </tr>
   <tr>
       <td>US03</td>
       <td>Implementación de JavaScript</td>
       <td>T06</td>
       <td>Agregar Botón en JS HTML y CSS</td>
       <td>Agregar comportamientos dinámicos al botón, estructurarlo y estilizarlo</td>
       <td>2</td>
       <td>Augusto Pin</td>
       <td>Done</td>
    </tr>
   <tr>
       <td>US04</td>
       <td>Implementación de Cover</td>
       <td>T07</td>
       <td>Agregar cover landing page</td>
       <td>Diseñar una portada atractiva</td>
       <td>3</td>
       <td>Brenda Gamio</td>
       <td>Done</td>
    </tr>
</table>

#### 5.2.1.3. Development Evidence for Sprint Review.
| Repository                                                      | Branch   | Commit id | Commit Message                                    | Commit Message Body                               | Commited on (Date) |
|-----------------------------------------------------------------|----------|-----------|---------------------------------------------------|---------------------------------------------------|-------------------- 
| https://github.com/Aplicaciones-Web-SW56-AlquilaFacil/Landing-Page-AF.git | variety  | 2b4f926   | feat: added section variety and design responsive | feat: added section variety and design responsive | 11/04/2024         | 
|                                                                 | banner-1 | c867f51   | feat: added banner #1 for landing page            | feat: added banner #1 for landing page            | 11/04/2024         | 
|                                                                 | banner-2 | 4c6f4c5   | feat(section): added banner and button            | feat(section): added banner and button            | 12/04/2024         | 
|                                                                 | banner-3 | c867f51   | feat: Added banner #3 for Landing page            | feat: Added banner #3 for Landing page            | 11/04/2024         | 
|                                                                 | places   | f82e444   | feat: add places for landing page                 | feat: add places for landing page                 | 11/04/2024         | 
|                                                                 | nav      | c9516af   | feat: Added nav partial                           | feat: Added nav partial                           | 11/04/2024         | 
|                                                                 | footer   | 951d833   | feat: added footer                                | feat: added footer                                | 12/04/2024         | 

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th >Branch</th>
    <th>Commit</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
  </tr>
  <tr>
    <td>Landing-Page-AF</td>
    <td>feature/aceptance_test</td>
    <td>71084fd</td>
    <td>Augusto Pin</td>
    <td>doc: add acceptance tests</td>
    <td>12/04/2024</td>
  </tr>
</table>

#### 5.2.1.5. Execution Evidence for Sprint Review

1. Sección  banner de presentacion, donde se puede visualizar un paisaje con nuestras funcionalidades.

<div align=center>
   <img src="/assets/landingAF-1.png" alt="carrusel"></img>
</div>

2. Sección de ciudades donde se puede ver donde opera AlquilaFacil.

<div align=center>
   <img src="/assets/landingAF-2.png" alt="carrusel"></img>
</div>

3. Sección sabe mas donde damos mas explicacion de detalle de AlquilaFacil.

<div align=center>
   <img src="/assets/landingAF-3.png" alt="carrusel"></img>
</div>

4. Sección  donde llamamos a los usuarios que tienen propiedades a que tenga una cuenta en AlquilaFacil.

<div align=center>
   <img src="/assets/landingAF-4.png" alt="carrusel"></img>
</div>

5. Sección donde mostramos que clase de locales hay en AlquilaFacil.

<div align=center>
   <img src="/assets/landingAF-5.png" alt="carrusel"></img>
</div>

6. Sección  del footer donde se muestra nuestro logo y el objetivo que tenemos como aplicacion.

<div align=center>
   <img src="/assets/landingAF-6.png" alt="carrusel"></img>
</div>


#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Durante el primer sprint, se ha creado el landing page como primer paso del proyecto, sin que se haya hecho uso de web services para su funcionamiento.

Para saber más sobre los web services, se le deja un pequeño resumen de lo que son y para qué sirven.

- Un web service es un software que permite la comunicación e intercambio de datos entre distintas aplicaciones, independientemente del lenguaje de programación o la plataforma en la que se hayan desarrollado. Los web services facilitan la integración y la interoperabilidad entre sistemas heterogéneos.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Para el presente sprint, se ha desarrollado el landing page. Para el desarrollo del landing page se ha utilizado las siguientes herramientas:

- Git: Herramienta de gestión de versiones que facilitó la colaboración en equipo durante la creación del landing page. Git es un sistema que permite a los programadores registrar y seguir los cambios realizados en el código fuente de un proyecto. Con Git, podemos crear ramas para trabajar en diferentes partes del código sin interferir con el trabajo de los demás, integrar los cambios cuando estén listos y revertirlos si es necesario.

- GitFlow: Método de trabajo que contribuyó al seguimiento del progreso individual de cada miembro del equipo en la creación del landing page. GitFlow es un modelo de flujo de trabajo con ramificaciones en Git que establece una estructura estándar para organizar las diferentes versiones y características del código. Con GitFlow, podemos mantener una rama principal (master o main) con el código más estable y seguro, una rama de desarrollo (develop) con el código en proceso, y varias ramas auxiliares (feature, release, hotfix) que se utilizan para desarrollar nuevas funcionalidades, preparar lanzamientos y solucionar errores urgentes, respectivamente.

- GitHub: Plataforma que facilitó la colaboración en equipo para almacenar las versiones de nuestro proyecto. GitHub es un servicio web que utiliza Git para alojar repositorios remotos y fomentar la colaboración entre programadores. Con GitHub, podemos cargar nuestro código en la nube, compartirlo con otros usuarios, recibir comentarios y sugerencias, hacer seguimiento de tareas y problemas, y acceder a una amplia gama de proyectos de código abierto.

- GitHub Pages: Servicio que nos permitió publicar nuestro landing page directamente desde nuestro repositorio de GitHub. GitHub Pages ofrece una manera sencilla de crear sitios web estáticos para nuestros proyectos, utilizando temas prediseñados o personalizados. Con GitHub Pages, podemos mostrar nuestro landing page al mundo sin la necesidad de adquirir un servidor o un dominio.

#### 5.2.1.8. Team Collaboration Insights during Sprint

El equipo creó el landing page utilizando el modelo de gitflow, el cual implica utilizar distintas ramas para abordar cada parte del proyecto, optimizarlo y mantenerlo actualizado. La ventaja de adoptar este enfoque es que simplifica la tarea de actualizar y realizar modificaciones, permitiendo luego mostrar y comprobar la integración sin problemas en la rama principal.

| Alumno        | Actividad                                                   | 
|---------------|-------------------------------------------------------------|
| Angel Cancho  | Implementación del banner 1                                 |
| Josten Huaman | Implementación del banner 2                                 |
| Italo Luna    | Implementación del responsive y características del website |
| Augusto Pin   | Implementación de los lugares                               |
| Brenda Gamio  | Implementación del banner 3                                 |

**GitFlow:**
<div align=center>
   <img src="/assets/Gitflow-AF.jpg" alt="carrusel"></img>
</div>
<div align=center>
   <img src="/assets/Gitflow-AF2.jpg" alt="carrusel"></img>
</div>

**Nethwork Graphs del repositorio del Landing Page**
<div align=center>
   <img src="/assets/NethworkGraph1.png" alt="insights"></img>
</div>
<div align=center>
   <img src="/assets/NethworkGraph2.png" alt="insights"></img>
</div>
<div align=center>
   <img src="/assets/NethworkGraph3.png" alt="insights"></img>
</div>
<div align=center>
   <img src="/assets/NethworkGraph4.png" alt="insights"></img>
</div>

