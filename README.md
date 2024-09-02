# Proyecto Web Personal - Grupo Wired

Este es un proyecto web personal que representa el sitio del "Grupo Wired", un grupo de estudio universitario especializado en cursos generales de ingeniería. El sitio fue construido utilizando HTML5, SASS y Bootstrap para un diseño moderno y responsive.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

```bash
├── index.html               # Página principal
├── paginas/                 # Directorio con las páginas individuales
│   ├── calculodiferencial.html
│   ├── equipo.html          
│   ├── fisicauno.html       
│   └── quimicauno.html      
├── estilos/                 # Directorio de estilos
│   ├── style.css            
│   ├── style.css.map       
├── sass/                    # Directorio de archivos SASS
│   ├── _cursos.scss         
│   ├── _equipo.scss         
│   ├── _footer.scss         
│   ├── _general.scss        
│   ├── _inicio.scss         
│   ├── _keyframes.scss      
│   ├── _mediaQueries.scss   
│   ├── _navbar.scss         
│   └── style.scss          
├── imagenes/                # Directorio de imágenes
└── README.md                # Documentación del proyecto
```
## Tecnologías Utilizadas
- `HTML5:` Estructura del contenido.
- `SASS:` Preprocesador CSS que facilita la modularidad y mantenibilidad de los estilos.
- `Bootstrap 5:` Framework CSS para un diseño responsive y moderno.
- `Font Awesome:` Biblioteca de iconos para mejorar la interfaz visual.
## Compilación de SASS
Para compilar los archivos SASS a CSS, puedes usar el siguiente comando:
```bash
sass sass/style.scss estilos/style.css
```
Si deseas compilar automáticamente cada vez que realices cambios en los archivos SASS, puedes usar:
```bash
sass --watch sass/style.scss:estilos/style.css
```
## Personalización
Los estilos se organizan en parciales SASS para facilitar la modificación y escalabilidad. Cada sección de la página tiene su propio archivo SASS, que luego es importado en el archivo principal `style.scss`.
