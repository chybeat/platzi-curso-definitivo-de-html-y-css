# Curso definitivo de HTML y CSS

This repository was intented to maintain and preserve the working files and challenges from platzi's "Curso definito de HTML y CSS". You can see part of rendered project from see in [https://chybeat.github.io/platzi-curso-definitivo-de-html-y-css/](https://chybeat.github.io/platzi-curso-definitivo-de-html-y-css/)

## Folder Clases in repository

[Goto clases folder in repository](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/tree/main/clases)

The "clases" folder has the files used or created while studing

1. **08-indexYsuEstructuraBasica**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/08-indexYsuEstructuraBasica/index.html "View code for indexYsuEstructuraBasica on index.html") has some global tags in body and head , the file has an HTML comments about some tags in code an possible uses.
1. **13-etiquetaImg**: [index.html ](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/13-etiquetaImg/index.html "View code for etiquetaImg on index.html") Shows some use of the `<img>` tag and `<figure>` tag
1. **15-etiquetaVideo**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/15-etiquetaVideo/index.html "View code for etiquetaVideo on index.html") Shows some use of the `<video>` tag and `<source>` tag
1. **16-forms**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/16-forms/index.html "View code for forms on index.html") Shows some use of the `<form>`, `<label>` and `<input>` tags
1. **17-calendario**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/16-calendario/index.html "View code for calendario on index.html") Shows some `<input>` tags with types for calendar like week, datetime-local, etc and the attributes "require" and "autocomplete" in some `<input>` tags
1. **19-select**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/19-select/index.html "View code for select tag on index.html") Shows the standarized use of `<select>` and `<option>` tags. Additionaly a best way to lists elements using `<input list="id-datalist">` and `<datalist id='id-datalist'>` and a diference between `<button>` tag and `<input type="submit">`
1. **22-CSS**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/22-CSS/index.html "View how to apply CSS code to index.html") and [style.css](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/22-CSS/style.css "View part of the CSS code applied in index.html") Shows how to set styles in three ways into HTML language and read orders
1. **23-Pseudos**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/23-Pseudos/index.html "View the BEM metodology in index.html") and [style.css](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/23-Pseudos/style.css "View the CSS code applied in index.html") The HTML shows information about the BEM methodology with a block and elements samples. The CSS shows information about the anathomy of CSS code and information about pseudo elements and pseudo class
1. **25-modeloCaja**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/25-modeloCaja/index.html "View simply HTML box model on index.html") and [style.css](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/25-modeloCaja/style.css "View box model CSS code to use the mox model of HTML code from index.html") The HTML is a simply box model code. The CSS code set a box to 100% and the code to reset all HTML to use a 100% box into browser width (box-sizing: boder-box).
1. **26-herencia**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/26-herencia/index.html "View a simply HTML code") and [style.css](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/26-herencia/style.css "a CSS inherith value applied") The simply HTML code in HTML donesn't care, but an explaination about how to apply inheritance with css with 'inherith value' for font-size writed on style.css". Other topic there is about css specificity with some examples.
1. **30-combinadores**: [index.html](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/30-combinadores/index.html "?????") and [style.css](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/30-combinadores/style.css "????") ?????.

---

![Carnes](retos/listaAlimentos/img/alimentos/carne-de-res-small.jpg)![granos](retos/listaAlimentos/img/alimentos/frijol-small.jpg)![frutas](retos/listaAlimentos/img/alimentos/naranja-small.jpg)![condimentos](retos/listaAlimentos/img/alimentos/azucar-small.jpg)

## Challenge Lista de alimentos (retoListaAlimentos.html)

View: [lista de alimentos](https://chybeat.github.io/platzi-curso-definitivo-de-html-y-css/retos/listaAlimentos/index.html)

Challenge parameters:

**HTML**

1. Create a food list using the list tags `<ul>`, `<ol>` and `<li>` for foods bought in supermarket.
1. Set an anchor tag `<a>` to every item's recipe
1. Add a representative image of any element in list using `<figure>` and `<img>` tags to advice what element is.

**CSS**

1. Implement the style.css file and some styles in list
1. Apply the BEM methodology in project

### What I did

**HTML**

1. I think, "the supermarket list, is a checklist"
    - That's the reason to use the `<input type="checklist" id="xxx">` tag and attribures
    - And the same reason to use `<label for="xxx">` tag to click over the element's name to check
1. Into `<figcaption>` tag is the anchor's recipe
1. The anchor in `<figcaption>` has a "title" attribute with the destination page title
1. I was set the image height with attribute `width="60"` for the `<img>` tag. Later I see pictures too small. After little investment about fix the problem, some people recomends to set a higher resolution image into an anchor to expand later with javascript. For me, now is only into anchor linked to a bigger image.
1. I use the `<footer>`tag with a little nav elements using internal "id" attribute set in principal `<li>` tags and "href" attribute with "#" character to id's value. (Just for practice)

**CSS**

1. Just to start I implement the file into list, then added color and font size for titles some class elements to HTML (icon and food groups) and color for text on every group using the id attribute
1. Bem implemented!. 😱OMG a lot of work in HTML code!
