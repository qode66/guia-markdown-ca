## HTML

Moltes aplicacions de Markdown us permeten utilitzar etiquetes HTML en text amb format Markdown. Això és útil si preferiu certes etiquetes HTML a la sintaxi de Markdown. Per exemple, a algunes persones els resulta més fàcil utilitzar etiquetes HTML per a les imatges. L'ús d'HTML també és útil quan necessiteu canviar els atributs d'un element, com ara especificar el <font color="red">color del text</font> o canviar l'amplada d'una imatge.

Per utilitzar HTML, col·loqueu les etiquetes al text del vostre fitxer amb format Markdown.

```
Aquesta **paraula** és en negreta. Aquesta <em>paraula</em> és cursiva.
```

La sortida renderitzada té aquest aspecte:

Aquesta **paraula** és en negreta. Aquesta <em>paraula</em> és cursiva.

### Bones pràctiques d'HTML

Per motius de seguretat, no totes les aplicacions de Markdown admeten HTML als documents de Markdown. En cas de dubte, consulteu la documentació de l'aplicació Markdown. Algunes aplicacions només admeten un subconjunt d'etiquetes HTML.

Utilitzeu línies en blanc per separar els elements HTML a nivell de bloc com `<div>`, `<table>`, `<pre>` i `<p>` del contingut circumdant. Intenteu no sagnar les etiquetes amb pestanyes o espais, que poden interferir amb el format.

No podeu utilitzar la sintaxi de Markdown dins d'etiquetes HTML a nivell de bloc. Per exemple, `<p>cursiva i **negreta**</p>` no funcionaran.

## Vegeu també

[Guia Markdown](../README.md)
