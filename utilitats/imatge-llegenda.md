## Llegendes de la imatge

Markdown no suporta nativament les llegendes de les imatges, però hi ha dues possibles solucions. Si la vostra aplicació Markdown admet l'[HTML](../sintaxi-basica/html.md), podreu utilitzar les etiquetes HTML `figure` i `figcaption` per a afegir una llegenda per a la vostra imatge.

```html
<figure>
  img src="/assets/images/albuquerque.webp" alt="Albuquerque, Nou Mèxic">
  <figcaption>
    Un sender solitari a les afores d'Albuquerque, Nou Mèxic.
  </figcaption>
</figure>
```

La sortida renderitzada es veu així:

<figure>
    <img src="../Imatges/albuquerque.png" alt="Albuquerque, Nou Mèxic">
    <figcaption>Un sender solitari a les afores d'Albuquerque, Nou Mèxic.</figcaption>
</figure>

> **Consell:** Si la vostra aplicació Markdown admet CSS, podeu utilitzar CSS per a estilitzar l'aparença de la llegenda.

Si la vostra aplicació Markdown no admet HTML, podeu intentar col·locar la llegenda directament a sota de la imatge i utilitzar [èmfasi](../sintaxi-basica/emfasi.md).

```text
![Albuquerque, Nou Mèxic](../Images/albuquerque.png)
*Un sender solitari a les afores d'Albuquerque, Nou Mèxic.*
```

La sortida renderitzada es veu així:

![Albuquerque, Nou Mèxic](../Imatges/albuquerque.png)

_Un sender solitari a les afores d'Albuquerque, Nou Mèxic._

## Vegeu també

[èmfasi](../sintaxi-basica/emfasi.md)  
[HTML](../sintaxi-basica/html.md)

[Guia Markdown](../README.md)
