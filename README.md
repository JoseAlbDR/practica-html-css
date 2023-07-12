## Proyecto de HTML y CSS - Documentación

Sitio web personal llamado "Portfolio JADR". El proyecto utiliza HTML y CSS para crear una interfaz visualmente atractiva y responsive.

### Estructura de directorios

El proyecto sigue la siguiente estructura de directorios:

```
├── assets                  # Carpeta contenedora de los recursos de la Web
|   ├── icons               # Contiene los iconos como el favicon o los iconos de las redes sociales
|   ├── images              # Carpeta contenedora de las imagenes usadas en la web
|   |   ├── main            # Contiene Imágenes de la página pricipal
|   |   ├── projects        # Contiene Imágenes de los proyectos
|   |   ├── skills          # Contiene Archivos svg de las tecnologías que aperecn en el apartado skills
|   ├── svg                 # Contiene Archivos svg relacionados con el logo del sitio 
|   ├── videos              # Contiene un Archivo mp4 con el video que se muestra en la página portfolio.html      
|   ├── styles              # Contiene los archivos .css de estilos     
├── 404.html                # Página de error
├── index.html              # Página principal
├── portfolio.html          # Página donde se encuentran los proyectos
```

La carpeta assets contiene los archivos CSS, imágenes, íconos, archivos SVG y videos utilizados en el proyecto. El archivo index.html representa la página principal del sitio web, mientras que portfolio.html muestra una sección de proyectos. Además, se ha creado una página de error 404 llamada 404.html para las páginas no encontradas.

## Proyecto en vivo

Puedes ver una versión en vivo del proyecto en la siguiente [dirección](https://www.jadero.dev/)

Para hospedar la página he utilizado un servicio de máquina virtual en la nube de vultr con un sistema operativo Ubuntu 22.04 x64 y un servidor nginx para responder a las peticiones HTTPS. Para la navegación segura HTTPS he utilizado un certificado SSL/TSL emitido por Let's Encrypt y administrado por Certbot.

El dominio jadero.dev apunta con un registro DNS A a la ip del servidor y el subdominio www.jadero.dev apunta con un registro DNS CNAME a jadero.dev.

Cuando se intenta navegar una página que no existe el servidor redirige directamente a la página 404.html

## Funcionalidades

Este sitio web tiene las siguientes funcionalidades:

### En index.html

- Navegación: barra de navegación que permite al usuario acceder a diferentes secciones del sitio web, como el inicio, habilidades, contacto y portfolio.

- Sección del encabezado: La sección del encabezado muestra el logotipo del sitio web y el menú de navegación.

- Sección del banner: Esta sección presenta un título principal.

- Sección "Acerca de mí": En esta sección, presento una breve descripción de mí mismo y mis habilidades.

- Sección de habilidades: Aquí se muestran mis habilidades, representadas por iconos y barras de progreso.

- Sección de contacto: Esta sección incluye un formulario de contacto con campos para nombre, apellidos, teléfono, etiqueta de GitHub, lugar de conocimiento, información adicional y opción de suscripción a la newsletter.

### En portfolio.html

- Sección de video: En esta sección se reproduce un video automatica mente al entrar en la página, el video tiene una animación fadeIn, es un video en el que se ve el formato responsive de la página en diferentes resoluciones.

- Sección de proyectos: En esta sección se presentan diferentes proyectos del autor, mostrando una imagen, descripción, tecnologías utilizadas y enlaces a GitHub y versiones en vivo de los proyectos.

### Común

- Pie de página: El sitio web tiene un pie de página con enlaces a mis redes sociales y derechos de autor.

## Guía de uso

Para utilizar el proyecto "Portfolio JADR", sigue estos pasos:

1. Clona el repositorio del proyecto o descarga los archivos HTML y CSS.

2. Abre el archivo index.html en tu navegador para acceder a la página principal del sitio web.

3. Utiliza la barra de navegación para moverte entre las diferentes secciones del sitio web.

4. Explora la sección "Acerca de mí" para conocer más sobre el autor y sus habilidades.

5. En la sección de contacto, completa el formulario con tu nombre, apellidos, teléfono, etiqueta de GitHub, lugar de conocimiento y otra información adicional. Puedes seleccionar la opción de suscripción a la newsletter si lo deseas.

6. En la sección de proyectos, verás diferentes proyectos del autor. Haz clic en los enlaces de GitHub y versiones en vivo para obtener más información sobre cada proyecto.

7. Navega hasta la parte inferior del sitio web para encontrar enlaces a las redes sociales del autor y los derechos de autor.

## Desarrollo del proyecto

El proyecto "Portfolio JADR" ha sido desarrollado utilizando HTML y CSS. Se han utilizado varias bibliotecas y recursos externos, como Google Fonts, para aplicar estilos y fuentes personalizados al sitio web.

El código HTML se ha estructurado utilizando etiquetas semánticas para mejorar la accesibilidad y el SEO del sitio web. Se han utilizado clases y selectores CSS para aplicar estilos a los elementos y crear una apariencia coherente en todo el sitio.

Los estilos CSS se han organizado en archivos separados según su función, como estilos de normalización, estilos comunes, estilos de encabezado, estilos de pie de página, etc. Se han utilizado reglas CSS para controlar el diseño, colores, fuentes y animaciones del sitio web.

El proyecto utiliza imágenes y videos para mejorar la experiencia visual. Se han optimizado las imágenes para reducir el tamaño del archivo y mejorar el rendimiento del sitio web.

## Conclusiones

El proyecto "Portfolio JADR" es un sitio web personal que utiliza HTML y CSS para crear una interfaz atractiva y funcional. El sitio web incluye diferentes secciones, como "Acerca de mí", habilidades, proyectos y contacto. Los usuarios pueden navegar por el sitio web y acceder a la información, así como ver proyectos específicos.

El proyecto demuestra habilidades en el desarrollo web front-end utilizando HTML y CSS, así como la capacidad para crear una estructura de directorios organizada y seguir las mejores prácticas en la creación de sitios web.
