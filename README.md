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
-    Organization: https://github.com/Open-Source-SW53-Group-3
-    Landing Page Repository: https://github.com/Open-Source-SW53-Group-3/Landing-Page
-    Report Repository: https://github.com/Open-Source-SW53-Group-3/Report

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
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
#### 5.2.1.2. Sprint Backlog 1
#### 5.2.1.3. Development Evidence for Sprint Review
#### 5.2.1.4. Testing Suite Evidence for Sprint Review
#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint