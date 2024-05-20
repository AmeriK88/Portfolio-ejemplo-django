# Proyecto Django: Portfolio y Blog Personal
  Este proyecto de Django es una aplicación web que consta de dos partes principales: un portfolio personal para mostrar tus proyectos y habilidades, y un blog personal para compartir tus pensamientos y experiencias.

## Funcionalidades
  ### Portfolio:
    Muestra tu trabajo, proyectos y habilidades.
    Los visitantes pueden navegar por diferentes categorías de proyectos y ver detalles sobre cada uno de ellos.
    Cada proyecto tiene su propia página con información detallada, incluyendo imágenes, descripción y enlace (si corresponde).
  ### Blog:
    Permite crear, editar y eliminar entradas de blog.
    Los visitantes pueden leer las entradas del blog y ver detalles.
    Cada entrada del blog tiene su propia página con título, fecha, imagen destacada y contenido detallado.
## Estructura de Directorios
**portfolio/:** Contiene los archivos relacionados con la aplicación Portfolio, incluyendo modelos, vistas, plantillas HTML y archivos estáticos (imágenes, CSS).
**blog/:** Contiene los archivos relacionados con la aplicación Blog, incluyendo modelos, vistas, plantillas HTML y archivos estáticos (imágenes, CSS).
**static/:** Contiene archivos estáticos compartidos entre las dos aplicaciones, como imágenes y CSS. Está organizado en subdirectorios separados para cada aplicación.
Páginas de Código Relevantes
 -home.html:
Este archivo HTML representa la página de inicio del portfolio. Contiene secciones para mostrar una introducción personal, una lista de proyectos y un botón para descargar el CV.

 ### layout.html:
  El layout.html define la estructura básica de todas las páginas del proyecto. Incluye el encabezado, la barra de navegación y el contenedor principal para el contenido de cada página.

 ### post.html:
  Esta plantilla HTML se utiliza para mostrar una lista de entradas de blog. Cada entrada se muestra en una tarjeta con título, descripción, fecha y botón para ver detalles.

 ### post_detail.html:
  Esta plantilla HTML muestra los detalles completos de una entrada de blog específica, incluyendo título, fecha, imagen destacada y contenido detallado.

 ## Configuración
  El archivo settings.py está configurado para incluir las aplicaciones Portfolio y Blog en la lista de aplicaciones instaladas.
  Los archivos estáticos (imágenes y CSS) se encuentran en la carpeta static/, con subdirectorios separados para las aplicaciones Portfolio y Blog.
