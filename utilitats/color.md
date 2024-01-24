## Color

Markdown no permet canviar el color del text, però si el vostre processador Markdown admet [HTML](../sintaxi-basica/html.md), podeu utilitzar l'etiqueta HTML `<font>`. L'atribut `color` permet especificar el color del tipus de lletra utilitzant el nom d'un color o el codi hexadecimal `#RRGGBB`.

```html
<font color="red">Aquest text és vermell!</font>
```

La sortida renderitzada es veu així:

<p style="color:red">Aquest text és vermell!</p>

L'etiqueta HTML `<font>` és tècnicament compatible però oficialment [obsoleta](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/font), el que significa que funciona de moment però se suposa que no l'estàs utilitzant. Malauradament, no hi ha una altra alternativa HTML pura. Podeu provar d'utilitzar una de les alternatives CSS. No totes les aplicacions Markdown proporcionen suport CSS, però si la que esteu utilitzant ho fa, aquí hi ha una alternativa a l'etiqueta `<font>`:

```html
<p style="color:blue">Fa que aquest text sigui blau.</p>
```

Si l'aplicació Markdown ho permet, la sortida es veurà així:

<p style="color:blue">Fa que aquest text sigui blau.</p>

## Vegeu també

[HTML](../sintaxi-basica/html.md)

[Guia Markdown](../README.md)
