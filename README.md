# Logotipos y banners de la Facultad de Ciencias

Nunca he encontrado material gráfico o de prensa en formatos reproducibles (svg o png) de la Facultad emitido por esta misma, así que lo he elaborado yo para usarlo con distintos propósitos tales como documentación, entregas, tareas, etiquetas, etcétera.

Para esto me he apoyado de otros recursos de libre acceso tales como el escudo de la Facultad de Ciencias proporcionado a Wikipedia (véase en [commons.wikimedia.org](https://commons.wikimedia.org/wiki/File:Escudo-facultad-ciencias-unam-escalable.svg)) y el de la misma Universidad (véase en [commons.wikimedia.org](https://commons.wikimedia.org/wiki/File:Escudo-UNAM-escalable.svg)).

# Demostración

Hay una versión para entornos oscuros y otra para entornos claros, así como una edición a color y otra monocromática de alto contraste.

## Facultad de Ciencias

La tipografía empleada en el logotipo de la facultad es [Montserrat](https://fonts.google.com/specimen/Montserrat), por Julieta Ulanovsky.

### Imagotipo a color dinámico

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/fciencias/banner-fciencias-color-light.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/fciencias/banner-fciencias-color-dark.svg">
  <img alt="Banner-fciencias" src="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/fciencias/banner-fciencias-color-light.svg">
</picture>

### Imagotipo de alto contraste dinámico

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/fciencias/banner-fciencias-hicontrast-light.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/fciencias/banner-fciencias-hicontrast-dark.svg">
  <img alt="Banner-fciencias" src="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/fciencias/banner-fciencias-color-light.svg">
</picture>


## Licenciatura en Ciencias de la Computación

La tipografía empleada en el logotipo de la carrera es [Open Sans](https://fonts.google.com/specimen/Open+Sans), por Steve Matteson.

### Imagotipo a color dinámico

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/licenciaturacc/banner-licenciaturacc-color-light.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/licenciaturacc/banner-licenciaturacc-color-dark.svg">
  <img alt="Banner-fciencias" src="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/licenciaturacc/banner-licenciaturacc-color-light.svg">
</picture>

### Imagotipo de alto contraste dinámico 

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/licenciaturacc/banner-licenciaturacc-hicontrast-light.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/licenciaturacc/banner-licenciaturacc-hicontrast-dark.svg">
  <img alt="Banner-fciencias" src="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/licenciaturacc/banner-licenciaturacc-hicontrast-light.svg">
</picture>

##

# Cómo usar

Para insertar cualquiera de los gráficos en documentación de Markdown en Github o de Markdown R, basta usar la notación recomendada en [GitHub docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#specifying-the-theme-an-image-is-shown-to).

Por ejemplo, este es el bloque de código para insertar el banner a color dinámico de la facultad:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/fciencias/banner-fciencias-color-light.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/fciencias/banner-fciencias-color-dark.svg">
  <img alt="Banner-fciencias" src="https://raw.githubusercontent.com/Ahexo/fciencias-banner/main/fciencias/banner-fciencias-color-light.svg">
</picture>
```

Puedes usar atributos HTML para modificar otros aspectos como el tamaño o la posición.

También puedes navegar en los ficheros del repositorio, descargar los archivos originales en .svg e insertarlos tal cual en tus documentos o donde requieras.

# Formalidades

El escudo de la Universidad y de la Facultad de Ciencias son propiedad de la Universidad Nacional Autónoma de México (UNAM) y pueden ser reproducidos con fines no lucrativos, siempre y cuando no se mutile, se cite la fuente completa y su dirección electrónica. De otra forma, requiere permiso previo por escrito de la institución.

[Sobre el escudo (unam.mx)](https://www.unam.mx/acerca-de-la-unam/identidad-unam/escudo)
