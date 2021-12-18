# Curso definitivo de HTML y CSS

This repository was intented to maintain and preserve the working files and challenges from platzi's "Curso definito de HTML y CSS". You can see part of rendered project from see in [https://chybeat.github.io/platzi-curso-definitivo-de-html-y-css/](https://chybeat.github.io/platzi-curso-definitivo-de-html-y-css/)

## Folder Clases in repository

[Goto clases folder in repository](https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/tree/main/clases)

The "clases" folder has the files used or created while studing

1. **08-indexYsuEstructuraBasica/**: [index.html] https://github.com/chybeat/platzi-curso-definitivo-de-html-y-css/blob/main/clases/08-indexYsuEstructuraBasica/index.html has some global tags in body and head , the file has an HTML comments about some tags in code an possible uses.

1. **13-etiquetaImg/**: Use of the `<img>` tag and `<figure>` tag

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
