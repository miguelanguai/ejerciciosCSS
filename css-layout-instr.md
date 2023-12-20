# CSS layout: task instructions

## Se pide

- Dentro de la parte sobre CSS del Learning Pathway del MDN, abordamos aquí
  el capítulo sobre:

  [CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)

- Sigue las indicaciones siguientes respecto a lo que hay que hacer para
  cada una de sus guías guía:
  - 0 Overview
    - Léela.
  - 1 Introduction to CSS layout
    - Síguela.
  - 2 Normal flow
    - Síguela (es muy breve).
  - 3 Flexbox
    - Síguela y haz el Test skills.
    - Sigue y haz también entero el [FlexboxFroggy](https://flexboxfroggy.com/).
      - Al final, genera captura (firmada con tu nombre y apellido en la URL),
        con el desplegable de niveles mostrado, que muestre los que hayas
        logrado superar.
      - La captura se llamará:

        `flexbox-froggy.png`

  - 4 Grid
    - Síguela y haz el Test skills.
    - Sigue y haz también entero el [GridGarden](https://cssgridgarden.com/).
      - Al final, genera captura del estilo de la del FlexboxFroggy, y llamada:

      `grid-garden.png`

  - 5 Floats
    - Síguela y haz el Test skills.
  - 6 Positioning
    - Síguela y haz el Test skills.
  - 7 Multiple-column layout
    - Si tienes margen mírala, pero con menos detenimiento.
    - Si no, sáltatela.
  - 8 Responsive design
  - 9 Beginner's guide to media queries
    - Sigue **las dos** y al final haz su compartido Test skills.
  - 10 Legacy layout methods
    - Esta guía es interesante porque hace el enlace entre lo histórico
      (no tan lejano) con el flexbox y grid.
    - Si tienes margen mírala, pero con menos detenimiento (puede ayudar a
      reforzar el conocimiento de flexbox/grid).
    - Si no, sáltatela.
  - 11 Supporting older browsers
    - Síguela (pese a no tener Test your skills, es importante).
  - 12 Fundamental layout comprehension assessment
    - Haz este Assessment.
  - 13 See also: Practical positioning examples
    - Nota: los enlaces a esta y la siguiente guía no están en el panel de
      navegación, pero sí en la introducción "0 overview".
    - Puede ser interesante leerla como complemento, aunque cierta parte está un
      tanto outdated (el contexto de haber aprendido lo anterior te puede ayudar
      a diferenciar).
  - 14 See also: CSS layout cookbok
    - Superútil "libro de recetas": respecto a distintos common layout
      patterns (centrar horizontal/vertical, card, breadcrumb,
      pagination, sticky footer, ...), sugiere receta de cómo resolverlo y
      justifica las elecciones que ha hecho.
    - Lee al menos de cada receta la intro (saber a qué se refieren
      visualmente con cada una).
    - Y si tienes margen, lee el resto de cada una sobre cómo sugieren
      implementarla y porqué así.

### Indicaciones para la entrega

- Al hacer los ejercicios, edita solo las zonas que te indiquen de editar,
  marcándolas con comentario.
- Indicaciones respecto a los ficheros:
  - Descarga todos los ficheros de los "Test skills" bajo carpeta `tasks/`:
    los `.html` con el **nombre propuesto** y las imágenes/recursos
    necesarios manteniendo sus nombres y localización relativa (encontrarás
    los recursos en la carpeta de Github donde esté el html a descargar).
  - Para el "Assessment" baja los ficheros con sus nombres y su estructura
    bajo una carpeta `assessment/`

- La estructura esperada es así:

  ```text
  assessment/
    images/
      balloon-*.jpg
    index.html
    styles.css
  tasks/
    balloons*.jpg
    flexbox*-download.html
    flexbox-froggy.png
    float*-download.html
    grid*-download.html
    grid-garden.png
    position*-download.html
    rwd-download.html
  ```

  <!--
  Nota: Nos hemos saltado este año:

  ```text
  tasks/
    multicol*-download.html
  ```
  -->

## Deliver

- Put your produced files with the expected structure **directly under the
  root** of a ZIP file named:

  `first-surname.name.name-of-the-task.zip`

  - Where the `name-of-the-task` is current file name without `-instr.md`.
  - Use only ascii characters and kebab-case in the file name.
  - For example:
    - If the name of this file is

      `foo-bar-instr.md`

      and your name is

      José Luís NÚÑEZ CLEMENTE,

      file name should be:

      `nunez.jose-luis.foo-bar.zip`

  - Put **only** the requested files. If you have to comment something
    or add something extra:
    - Comment internally to the files.
    - If not enough, you can use a `readme.md` (all lowercase) in the root,
      and mention there anything extra or files/folders not expected.
  - Deliver the ZIP file in the medium indicated by the teacher.
