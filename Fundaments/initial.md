# Informacion Inicial de git. 🌿

Sabemos inicialmente que git esta basado en un VCS's que son conciderados controladores de versiones ya que estas nos ofrecen **confiabilidad** en tener una copia de versiones de nuetro trabajo.

## VCS.

Es la contraccion de Version Control System o *sistema de control de versiones o fuentes* es una herramienta de software que monitoriza y gestiona cambios en un sistema de archivos. Asimismo, un VCS ofrece herramientas de colaboración para compartir e integrar dichos cambios en otros usuarios del VCS. Al operar al nivel del sistema de archivos, un VCS monitorizará las acciones de adición, eliminación y modificación aplicadas a archivos y directorios. Un repositorio es un término del VCS que describe cuando un VCS está monitorizando un sistema de archivos. En el alcance los archivos individuales de códigos fuente, un VCS monitorizará las adiciones, eliminaciones y modificaciones de las líneas de texto que contiene ese archivo. Entre las opciones populares de VCS del sector de software, se incluyen Git, Mercurial, SVN y preforce.

![VSC](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.nettix.com.pe%2Fwp-content%2Fuploads%2F2020%2F02%2Fimg-1024x511.png&f=1&nofb=1)

Ante una de sus ventajas y el por que VCS es una valiosa herramienta con numerosos beneficios para un flujo de trabajo de equipos de software de colaboración. Cualquier proyecto de software que tiene más de un desarrollador manteniendo archivos de código fuente debe, sin duda, usar un VCS. Además, los proyectos mantenidos por una sola persona se beneficiarán enormemente del uso de un VCS. Se puede decir que no hay una razón válida para privarse del uso de un VCS en cualquier proyecto moderno de desarrollo de software.

> En el 2002 el proyecto de kernel de Linux uso un VCS bitkeeper, esta alñ dejar de ser gratuita el propio Linux creo su propio **VCS** siendo a si: Veloz, diseño facil, soporte de desarrollo no lineal (es decir, tiene ramas paralelas) y siendo su principal ventaja el poder controlar grandes proyectos.

**Git fue creado en ell año 2005**

## Git.

La diferenccia principal y ventaja que tiene git ya fue mencionada, pero *¿Que la diferencia de los demas VCS's?*.

- **Copias Instantaneas**
- **Copias Locales**
- **Sin perdidad de información**

### Los 3 estados de Git.

Dentro de git, existen los famosos *git status* el cual nos ayudaran verificar en que estado esta nuestro proyectos o los archivios de nuestros proyectos, siendo asi:

1. Commited.
2. Modified.
3. Staged.

#### Commited.

La confirmacion es la accion de saber si se guardaron de manerq segura de manera **Local** en la base de datos Local de tu ordenador.

#### Modified.

Se caracteriza poor hacer modificaciones ero sin tener una copia local.

#### Staged.

En este status se marcara un archivo *modificado* en su version actual para poder hacer commit.

### Las tres secciones de un proyecto.

1. Git Direcctorty.
2. Working Directory.
3. Staging Area.

![gitstatus](https://4.bp.blogspot.com/-NsYr3_xW1fY/XAAM0tHy3AI/AAAAAAAAAXY/GlZypaQO1cYSK97ATBBErCl8L_5uvE2VgCLcBGAs/s1600/Estados-git.png)