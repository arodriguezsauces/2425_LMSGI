### Descripción del Código

1. **Estructura Básica**:
   - `<!DOCTYPE html>`: Declara el tipo de documento como HTML5.
   - `<html lang="es">`: Inicia el documento HTML y establece el idioma como español.

2. **Encabezado (`<head>`)**:
   - `<meta charset="UTF-8" />`: Define la codificación de caracteres como UTF-8.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0" />`: Configura la vista para que sea compatible con dispositivos móviles.
   - `<title>Volcanes del Mundo</title>`: Título de la página que aparece en la pestaña del navegador.
   - `<link href="css/estilos.css" rel="stylesheet" type="text/css" />`: Enlaza una hoja de estilos CSS externa.

3. **Cuerpo (`<body>`)**:
   - **Encabezado (`<header>`)**:
     - `<h1>Volcanes del Mundo</h1>`: Título principal de la página.
     - `<nav>`: Contiene la barra de navegación con enlaces a diferentes secciones de la página.
       - `<ul>`: Lista desordenada de enlaces.
         - `<li><a href="#inicio">Inicio</a></li>`: Enlace a la sección de inicio.
         - `<li><a href="#volcanes">Volcanes</a></li>`: Enlace a la sección de volcanes.
         - `<li><a href="#contacto">Contacto</a></li>`: Enlace a la sección de contacto.

   - **Contenido Principal (`<main>`)**:
     - **Sección de Inicio (`<section id="inicio">`)**:
       - `<h2>Bienvenidos a Volcanes del Mundo</h2>`: Subtítulo de bienvenida.
       - `<p>Explora la fascinante geología de los volcanes más impresionantes del planeta.</p>`: Párrafo introductorio.

     - **Sección de Volcanes (`<section id="volcanes">`)**:
       - `<h2>Lista de Volcanes</h2>`: Subtítulo para la lista de volcanes.
       - **Artículo sobre el Monte Vesubio (`<article>`)**:
         - `<h3>Monte Vesubio</h3>`: Título del artículo.
         - `<figure>`: Contenedor para la imagen y su pie de foto.
           - `<img src="..." alt="Monte Vesubio" />`: Imagen del Monte Vesubio.
           - `<figcaption>El Monte Vesubio en Italia</figcaption>`: Pie de foto.
         - `<p>El Monte Vesubio es uno de los volcanes más famosos del mundo, conocido por la erupción que destruyó Pompeya.</p>`: Descripción del Monte Vesubio.
       - **Artículo sobre el Monte Fuji (`<article>`)**:
         - `<h3>Monte Fuji</h3>`: Título del artículo.
         - `<figure>`: Contenedor para la imagen y su pie de foto.
           - `<img src="..." alt="Monte Fuji" />`: Imagen del Monte Fuji.
           - `<figcaption>El Monte Fuji en Japón</figcaption>`: Pie de foto.
         - `<p>El Monte Fuji es el volcán más alto de Japón y un símbolo icónico del país.</p>`: Descripción del Monte Fuji.

