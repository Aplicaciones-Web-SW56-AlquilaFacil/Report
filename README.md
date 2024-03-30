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
            al uso de plataformas como Discord. Sin embargo, siempre hay margen para mejorar aún más nuestra coordinación 
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
#### 5.2.1.3. Development Evidence for Sprint Review
#### 5.2.1.4. Testing Suite Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint
