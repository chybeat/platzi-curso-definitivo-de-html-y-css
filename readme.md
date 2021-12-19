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

---

![Carnes](retos/listaAlimentos/img/alimentos/carne-de-res-small.jpg)![granos](retos/listaAlimentos/img/alimentos/frijol-small.jpg)![frutas](retos/listaAlimentos/img/alimentos/naranja-small.jpg)![condimentos](retos/listaAlimentos/img/alimentos/azucar-small.jpg)

## Reto Lista de alimentos (retoListaAlimentos.html)

View: [lista de alimentos](https://chybeat.github.io/platzi-curso-definitivo-de-html-y-css/retos/listaAlimentos/index.html)

Challenge parameters:

1. Create a food list using the list tags `<ul>`, `<ol>` and `<li>` for foods bought in supermarket.
1. Set an anchor tag `<a>` to every item's recipe
1. Add a representative image of any element in list using `<figure>` and `<img>` tags to advice what element is.

### What I did

1. I think, "the supermarket list, is a checklist"
    - That's the reason to use the `<input type="checklist" id="xxx">` tag and attribures
    - And the same reason to use `<label for="xxx">` tag to click over the element's name to check
1. Into `<figcaption>` tag is the anchor's recipe
1. The anchor in `<figcaption>` has a "title" attribute with the destination page title
1. I was set the image height with attribute `width="60"` for the `<img>` tag. Later I see pictures too small. After little investment about fix the problem, some people recomends to set a higher resolution image into an anchor to expand later with javascript. For me, now is only into anchor linked to a bigger image.
1. I use the `<footer>`tag with a little nav elements using internal "id" attribute set in principal `<li>` tags and "href" attribute with "#" character to id's value. (Just for practice)
