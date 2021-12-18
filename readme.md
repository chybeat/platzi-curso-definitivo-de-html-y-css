# Curso definitivo de HTML y css

This repository was intented to maintain and preserve the working files and challenges from platzi's "Curso definito de HTML y CSS"

## Clases

The "clases" folder has the files used or created during class

1. **08-indexYsuEstructuraBasica/**: index.html has some global tags in body and head , the file has a HTML comments about what is every tag an possible uses.

1. **13-etiquetaImg/**: Use of the `<img>` tag into `<figure>` tag

---

![Carnes](retos/listaAlimentos/img/alimentos/carne-de-res-small.jpg)![granos](retos/listaAlimentos/img/alimentos/frijol-small.jpg)![frutas](retos/listaAlimentos/img/alimentos/naranja-small.jpg)![condimentos](retos/listaAlimentos/img/alimentos/azucar-small.jpg)

## Reto Lista de alimentos (retoListaAlimentos.html)

View: [retos/listaAlimentos/](retos/listaAlimentos/index.html)

The challenge have these parameters

1. Create a food list using the list tags `<ul>`, `<ol>` and `<li>`) of HTML as you buy food in mall.
1. Set an anchor tag `<a>` to every item's recipe
1. Add a representative image of any element in list using `<figure>` and `<img>` tags if any person need to know what element is.

### What i did

1. I think, "the supermarket list, is a checklist"
    - That's the reazon to use the `<input type="checklist" id="xxx">` tag and attribures
    - And the same reason to use `<label for="xxx">` tag to click over the element's name and check
1. Into `<figcaption>` tag I set the anchor's recipe
1. The anchor in `<figcaption>` has a "title" attribute with the title where the recipes was founded
1. I was set the image size with the tag `<img>` attribute `width="60"` but later I see pictures too small. After little investment about fix the problem, some people recomends to set a higher resolution image into an anchor to expand later with javascript. For me, now is only into an anchor linked to a bigger image.
1. I use the `<footer>`tag with a little nav elements (Just for practice)
