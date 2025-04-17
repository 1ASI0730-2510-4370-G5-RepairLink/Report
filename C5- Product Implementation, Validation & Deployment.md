# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management

En el marco de este proyecto, se han tomado decisiones clave para garantizar la consistencia y eficiencia durante todo el ciclo de vida de la solución web distribuida. Estas decisiones aseguran que la aplicación web sea  escalable y fácil de mantener a lo largo de su ciclo de desarrollo y despliegue. Los principales aspectos de configuración incluyen:

-CONTROL DE VERSIONES DE GITHUB: La gestión del código fuente se lleva a cabo mediante GitHub, una plataforma de control de versiones distribuido que facilita la colaboración entre los miembros del equipo. Utilizamos el modelo GitFlow, que define un flujo de trabajo claro con las siguientes ramas:

*main (producción): contiene el código de la versión estable de la aplicación.

*develop (desarrollo): integrador para nuevas características y cambios no verificados aún.

*Ramas feature: para el desarrollo de características específicas del producto.

*Ramas hotfix: utilizadas para corregir errores urgentes en producción.

*SEMANTIC VERSIONING: Adoptamos el versionado semántico (Semantic Versioning) para asegurar que las versiones del producto sean claras y fáciles de entender para el equipo y los stakeholders. Esto facilita la gestión de la evolución del producto, permitiendo versiones como 1.0.0, 1.1.0, 2.0.0 para reflejar los cambios en la funcionalidad o la corrección de errores.

*CONVENCIONES DE COMMITS: Para mejorar la comunicación del equipo, se sigue el estándar de Conventional Commits para los mensajes de commit. Esto establece una estructura uniforme en los mensajes.
Feat para nuevas características , fix, para corrección de errores,docs, para documentación.

*ENTORNO DE DESARROLLO: La configuración del entorno de desarrollo se basa en tecnologías open-source, utilizando herramientas que faciliten la implementación y el mantenimiento del código. El uso de Docker para la creación de contenedores y la replicación del entorno de producción asegura que todos los miembros del equipo trabajen en condiciones similares.

*OCUMENTACIÓN DE SERVICIOS: La solución emplea una API RESTful como arquitectura principal, y se utiliza OpenAPI para documentar todos los endpoints, lo que garantiza que la documentación esté actualizada y sea fácilmente accesible para los desarrolladores y otros stakeholders.

*DESPLIEGUE EN LA NUBE: Utilizamos plataformas de Cloud Computing para el despliegue, asegurando que la solución sea escalable y accesible a través de diferentes dispositivos, manteniendo la consistencia entre el Landing Page y la Web Application.

### 5.1.1. Software Development Environment Configuration

El entorno de desarrollo para el proyecto ha sido configurado utilizando diversas herramientas y tecnologías que permiten una colaboración eficiente y una implementación efectiva durante todo el ciclo de vida del producto. A continuación, se detallan las herramientas y su propósito de uso:

*Figma
Propósito: Diseño de la interfaz de usuario (UX/UI).
Ruta de acceso: Figma
Figma es utilizado por el equipo para crear prototipos interactivos y realizar diseño de interfaz de usuario adaptable a diferentes dispositivos.

*Visual Studio Code
Propósito: Desarrollo de la aplicación web, edición de código y colaboración en tiempo real.
Ruta de acceso: Visual Studio Code
Visual Studio Code es la herramienta principal para la programación en HTML, CSS y JavaScript. Permite trabajar en un entorno flexible con extensiones y configuración personalizada.

Estas herramientas permiten una gestión eficiente del proyecto, cubriendo desde el diseño UX/UI hasta el desarrollo, asegurando que cada miembro del equipo tenga acceso a los recursos necesarios para cumplir con los objetivos del proyecto.

### 5.1.2. Source Code Management

El equipo ha decidido utilizar GitHub como plataforma para la gestión del código fuente y el control de versiones, garantizando la colaboración eficiente y el seguimiento de todas las modificaciones realizadas a lo largo del proyecto. El repositorio de GitHub se encuentra en el siguiente enlace:https://github.com/1ASI0730-2510-4370-G5-RepairLink

ESQUEMA DE CONTROL DE VERSIONES:

-Rama principal (main): Contendrá siempre la versión estable de la aplicación.

-Rama de desarrollo (develop): Servirá como rama integradora para el desarrollo de nuevas características y cambios no verificados.

-Ramas de características (feature branches): Cada nueva funcionalidad se desarrollará en una rama propia, siguiendo la convención de nombres como feature/<nombre-de-la-caracteristica>.

-Ramas de corrección de errores (hotfix branches): En caso de problemas críticos en producción, se utilizarán ramas de corrección rápida, denominadas hotfix/<descripcion-del-arreglo>.

-Ramas de liberación (release branches): Para preparar las versiones estables y nuevas funcionalidades, se creará una rama release/<version> para realizar pruebas y ajustes finales antes de la liberación.

CONVENCIONES DE NOMBRES Y VERSIONES:

Se aplicará el modelo Semantic Versioning (SemVer) para nombrar las versiones de los productos, asegurando claridad y coherencia en la gestión de las versiones. Por ejemplo:

-1.0.0: Primera versión estable.

-1.1.0: Inclusión de nuevas características.

-2.0.0: Cambios importantes que rompen la compatibilidad con versiones anteriores.

GITFLOW Y CONVENCIONES DE COMMITS:

El equipo implementará el flujo de trabajo GitFlow como modelo para el control de versiones. Además, se utilizarán las convenciones Conventional Commits para los mensajes de commit, siguiendo las siguientes directrices:

-feat: para nuevas características.

-fix: para correcciones de errores.

-docs: para cambios en la documentación.

-style: para modificaciones en la apariencia del código sin cambios de funcionalidad.

-refactor: para mejoras del código que no afectan su funcionalidad.

### 5.1.3. Source Code Style Guide & Conventions

En el proyecto, se adoptarán las siguientes convenciones de codificación para garantizar la consistencia en la implementación del código:

HTML: Se seguirán las pautas de estilo recomendadas en el "Google HTML/CSS Style Guide" y las convenciones establecidas por W3C para garantizar que el código sea legible y semántico. El código será indentado con 2 espacios y todos los elementos HTML serán escritos en inglés.

CSS: Se aplicará el "Google HTML/CSS Style Guide" para asegurar que las clases y los identificadores sean nombrados de manera clara y coherente, usando convenciones como la notación BEM (Block Element Modifier) cuando sea adecuado.

JavaScript: Se adoptarán las pautas del "Google JavaScript Style Guide" y el MDN JavaScript Guidelines para el desarrollo del código, asegurando buenas prácticas en la estructura del código, manejo de variables, y funciones. Las variables y funciones estarán nombradas en inglés y en notación camelCase.

Figma Integration: Los diseños creados en Figma seguirán el mismo enfoque de nomenclatura en inglés, con clases y estilos organizados de manera consistente con el código para facilitar la integración entre la interfaz de usuario y el desarrollo frontend.

### 5.1.4. Software Deployment Configuration

En esta sección se detalla el proceso de despliegue de los productos digitales desarrollados para la solución. A partir de los repositorios de código fuente en GitHub, el despliegue de cada componente se realizará de la siguiente manera:

*Landing Page:
-Entorno de Despliegue: La Landing Page se desplegará en una plataforma de hosting web, como Netlify o Vercel, que permite una integración sencilla con GitHub para realizar despliegues automáticos cada vez que se actualice el código.

*Pasos de Despliegue:

-Conectar el repositorio de GitHub con la plataforma de despliegue.

-Configurar las variables de entorno necesarias (si las hay).

-Activar los despliegues automáticos para que cualquier cambio en el repositorio active una actualización en la Landing Page.

-Verificar que la página sea accesible públicamente después del despliegue.

*Web Services (API RESTful):

Entorno de Despliegue: Los servicios web se desplegarán en plataformas como Heroku o AWS, que proporcionan servidores para alojar APIs y gestionar el escalado.

*Pasos de Despliegue:

-Crear una aplicación en Heroku o instancia de AWS.

-Conectar el repositorio GitHub al servicio.

-Establecer configuraciones de base de datos si es necesario.

-Implementar la API y realizar pruebas de integración para verificar su funcionamiento.

-Configurar el despliegue continuo (CI/CD) para permitir actualizaciones automáticas desde el repositorio.

*Frontend Web Application:

Entorno de Despliegue: La aplicación web frontend se desplegará en una plataforma como AWS, Netlify o Vercel, siguiendo un proceso similar al de la Landing Page.

*Pasos de Despliegue:

-Conectar el repositorio de GitHub con la plataforma de despliegue.

-Configurar el entorno y las variables necesarias para la producción (por ejemplo, rutas de API).

-Hacer uso de CI/CD para despliegues automáticos.

-Verificar la accesibilidad de la aplicación y la integración con la API RESTful.

## 5.2. Landing Page, Services & Applications Implementation
La implementación de la solución digital se realizó bajo una arquitectura distribuida basada en servicios, en concordancia con los lineamientos definidos durante la etapa de diseño. Esta sección documenta el proceso de desarrollo, pruebas, documentación técnica y despliegue de los componentes clave: Landing Page, Servicios Web (RESTful API) y la Aplicación Web Frontend.

Para asegurar una experiencia de usuario consistente e intuitiva, se diseñaron las interfaces en Figma, utilizando un enfoque centrado en el usuario. Este prototipo de alta fidelidad sirvió como guía visual durante el desarrollo, asegurando la alineación entre lo diseñado y lo implementado. El prototipo puede consultarse en el siguiente enlace:

 https://www.figma.com/design/VMTUTmSN9k1qX1JiXnVIgR/App-Web?node-id=6-14359

El desarrollo se organizó en sprints conforme a un enfoque ágil, permitiendo iterar y validar avances progresivamente con base en el Product Backlog. A continuación, se detallan los avances realizados por sprint, incluyendo las tareas ejecutadas, funcionalidades implementadas, pruebas realizadas y despliegues correspondientes.

### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1
SPRINT 1:

SPRINT PLANNING BACKGROUND

Date: 06-04-2025

Time: 8:00 pm

Location: Via virtual por Google Meet

Prepared By: Karen Stephanie Ramos Carpio

Attendees (to planning meeting): Sebastian Cordova Valdivia,Stanley Jeremy Gutierrez Tume,Edson Diego Llamozas Diaz,José Luis Martinez Valdivia,Karen Stephanie Ramos Carpio.

Sprint 1 - Review Summary: Durante la primera reunión del Sprint, el equipo se enfocó en definir las tareas y responsabilidades de cada miembro, asegurando que todos estuvieran alineados con los objetivos del informe a desarrollar y cualquier duda acerca del desarrollo hacernoslo saber por nuestro chat de whatsapp.

Sprint 1– Retrospective Summary: En esta retrospectiva, el equipo discutió cómo se llevó a cabo la planificación del Sprint y la distribución de tareas.Todos los participantes lograron hacer su parte del trabajo , ya que corregimos algunos puntos que nos parecían que se podían mejorar.

Sprint Goal & User Stories:

Sprint 1 goal: 

Sprint 1 Velocity:

Sum of Story Points:


#### 5.2.1.2. Sprint Backlog 1
En esta sección se muestran los tasks que se realizaron en el presente sprint y se adjunta una captura del trello y el link del tablero.
Enlace trello: https://trello.com/invite/b/680047bc1475a699e1fdd74d/ATTI898007e03e65fc1f955c95981381d097EB4EC5B8/apps

<img src="images/SPRINT BACKLOG.PNG" alt="images/SPRINT BACKLOG.PNG" style="width: 80%;">



#### 5.2.1.3. Development Evidence for Sprint Review

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

#### 5.2.1.8. Team Collaboration Insights during Sprint
