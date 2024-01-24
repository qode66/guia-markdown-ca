## Sagnat (Tab)

Les pestanyes i els espais en blanc tenen un significat especial a Markdown. Podeu utilitzar els espais en blanc finals per a crear [salts de línia](../sintaxi-basica/salt-de-linia.md), i podeu utilitzar tabuladors per a crear [blocs de codi](../sintaxi-basica/codi.md). Però i si necessiteu sagnar un paràgraf de la manera antiga, utilitzant la tecla de tabulació? Markdown no proporciona una manera fàcil de fer-ho.

La vostra millor opció podria ser utilitzar un editor Markdown que admeti el sagnat. Això és comú en aplicacions que estan més orientades cap a la publicació d'escriptori. Per exemple, el [iA Writer](https://www.markdownguide.org/tools/ia-writer/) permet personalitzar la configuració del sagnat per a l'editor a les preferències de l'aplicació. També proporciona opcions de personalització de les plantilles perquè pugueu fer que el document renderitzat sembli com s'espera, sagnat i tot.

Una altra opció, si el vostre processador Markdown admet [HTML](../sintaxi-basica/html.md), és utilitzar l'entitat HTML per a espais no separables (`&nbsp;`). Aquesta hauria de ser probablement la vostra opció d'últim recurs, ja que pot ser incòmoda. Bàsicament, cada `&nbsp;` a la vostra font de Markdown se substituirà amb un espai a la sortida renderitzada. Per tant, si fixeu quatre instàncies de `&nbsp;` abans d'un paràgraf, el paràgraf es veurà com si estigués sagnat amb quatre espais.

```html
&nbsp;&nbsp;&nbsp;&nbsp;Aquesta és la primera frase del meu paràgraf sagnat.
```

La sortida renderitzada es veu així:

&nbsp;&nbsp;&nbsp;&nbsp;Aquesta és la primera frase del meu paràgraf sagnat.

## Vegeu també

[salts de línia](../sintaxi-basica/salt-de-linia.md)  
[blocs de codi](../sintaxi-basica/codi.md)  
[HTML](../sintaxi-basica/html.md)

[Guia Markdown](../README.md)
