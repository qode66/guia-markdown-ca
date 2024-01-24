## Centrat

Tenir la capacitat de centrar el text és una necessitat quan s'escriu un paper o un informe. Malauradament, Markdown no té cap concepte d'alineació de text (una possible excepció és quan s'utilitzen [taules](../sintaxi-estesa/taules.md)). La bona notícia és que hi ha una etiqueta HTML que podeu utilitzar: `<center>`. Si el vostre processador Markdown admet [HTML](../sintaxi-basica/html.md), podreu col·locar aquestes etiquetes al voltant del text que vulgueu centrar l'alineació.

```html
<center>Aquest text està centrat.</center>
```

La sortida renderitzada es veu així:

<p style="text-align:center">Aquest text està centrat.</p>

L'etiqueta HTML `<center>` és tècnicament compatible però oficialment [obsoleta](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/center), el que significa que funciona de moment però se suposa que no l'estàs utilitzant. Malauradament, no hi ha una altra alternativa HTML pura. Podeu provar d'utilitzar una de les alternatives CSS. No totes les aplicacions Markdown proporcionen suport CSS, però si la que esteu utilitzant ho fa, aquí hi ha una alternativa a l'etiqueta `<center>`:

```html
<p style="text-align:center">Centra aquest text</p>
```

Si l'aplicació Markdown ho permet, la sortida es veurà així:

<p style="text-align:center">Centra aquest text</p>

## Vegeu també

[taules](../sintaxi-estesa/taules.md)  
[HTML](../sintaxi-basica/html.md)

[Guia Markdown](../README.md)
