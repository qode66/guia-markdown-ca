## Enllaços

Per crear un enllaç, afegiu el text de l'enllaç entre parèntesis (p. ex., `[Duck Duck Go]`) i seguiu-lo immediatament amb l'URL entre parèntesis (p. ex., `(https://duckduckgo.com)`).

```
El meu motor de cerca preferit és [Duck Duck Go](https://duckduckgo.com).
```

La sortida renderitzada té aquest aspecte:

El meu motor de cerca preferit és [Duck Duck Go](https://duckduckgo.com).

> <strong>Nota:</strong> per enllaçar a un element de la mateixa pàgina, vegeu enllaç a identificadors d'encapçalament. Per crear un enllaç que s'obri en una pestanya o finestra nova, consulteu la secció sobre objectius d'enllaç

### Afegint títols

Opcionalment, podeu afegir un títol per a un enllaç. Això apareixerà com a informació sobre eines quan l'usuari passi el cursor per sobre de l'enllaç. Per afegir un títol, poseu-lo entre cometes després de l'URL.

```
El meu motor de cerca preferit és [Duck Duck Go](https://duckduckgo.com "El millor motor de cerca per a la privadesa").
```

La sortida renderitzada té aquest aspecte:

El meu motor de cerca preferit és [Duck Duck Go](https://duckduckgo.com "El millor motor de cerca per a la privadesa").

### URL i adreces de correu electrònic

Per convertir ràpidament un URL o una adreça de correu electrònic en un enllaç, afegiu-lo entre claudàtors angulars.

```
<https://www.markdownguide.org>
<fake@example.com>
```

La sortida renderitzada té aquest aspecte:

<https://www.markdownguide.org><br/>
<fake@example.com>

### Format dels enllaços

Per [emfatitzar](#emphasis) enllaços, afegiu asteriscs abans i després dels claudàtors i els parèntesis. Per indicar els enllaços com a [codi](#codi), afegiu-los entre claudàtors.

```
M'encanta donar suport a l'**[Qode66](https://www.qode66.xyz/)**.
Aquesta és la *[Guia de Markdown](https://www.qode66.xyz/markdown/))*.
Vegeu la secció sobre [`codi`](#codi).
```

La sortida renderitzada té aquest aspecte:

M'encanta donar suport a l'**[Qode66](https://www.qode66.xyz/)**.<br/>
Aquesta és la _[Guia de Markdown](https://www.qode66.xyz/markdown/)_.<br/>
Vegeu la secció sobre [`codi`](#codi).

### Enllaços amb l'estil de referència

Els enllaços amb l'estil de referència són un tipus especial d'enllaç que facilita la visualització i la lectura dels URL a Markdown. Els enllaços amb l'estil de referència es construeixen en dues parts: la part que manteniu en línia amb el vostre text i la part que emmagatzemeu en un altre lloc del fitxer perquè el text sigui fàcil de llegir.

#### Format de la primera part de l'enllaç

La primera part d'un enllaç amb l'estil de referència està formatada amb dos conjunts de claudàtors. El primer conjunt de claudàtors envolta el text que hauria d'aparèixer enllaçat. El segon conjunt de claudàtors mostra una etiqueta que s'utilitza per apuntar a l'enllaç que esteu emmagatzemant en un altre lloc del document.

Tot i que no és obligatori, podeu incloure un espai entre el primer i el segon conjunt de claudàtors. L'etiqueta del segon conjunt de claudàtors no distingeix entre majúscules i minúscules i pot incloure lletres, números, espais o signes de puntuació.

Això significa que els formats d'exemple següents són aproximadament equivalents per a la primera part de l'enllaç:

- `[forat-de-hobbit][1]`
- `[forat-de-hobbit] [1]`

#### Format de la segona part de l'enllaç

La segona part d'un enllaç amb l'estil de referència té el format amb els atributs següents:

1. L'etiqueta, entre parèntesis, seguida immediatament de dos punts i almenys d'un espai (p. ex., `[etiqueta]: `).
2. L'URL de l'enllaç, que podeu incloure opcionalment entre claudàtors angulars.
3. El títol opcional de l'enllaç, que podeu incloure entre cometes dobles, cometes simples o parèntesis.

Això significa que els formats d'exemple següents són aproximadament equivalents per a la segona part de l'enllaç:

- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Estils de vida hobbit"`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Estils de vida hobbit'`
- `[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Estils de vida Hobbit)`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Estils de vida de Hobbit"`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Estils de vida de Hobbit'`
- `[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Estils de vida Hobbit)"`

Podeu col·locar aquesta segona part de l'enllaç a qualsevol lloc del vostre document Markdown. Algunes persones les col·loquen immediatament després del paràgraf en què apareixen, mentre que altres les col·loquen al final del document (com les notes finals o les notes al peu).

#### Un exemple d'ajuntar les peces

Suposem que afegiu un URL com a [enllaç URL estàndard](#links) a un paràgraf i té aquest aspecte a Markdown:

```
En un forat a terra hi vivia un hòbbit. No és un forat desagradable, brut i humit, ple d'excrements
de cucs i una olor supurada, ni tanmateix un forat sec, nu i sorrenc sense res per seure o per menjar: era un [forat-de-hobbit](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Estils de vida hobbit"), i això significa comoditat.
```

Tot i que pot indicar informació addicional interessant, l'URL tal com es mostra realment no afegeix gaire al text en brut existent, a part de dificultar la lectura. Per solucionar-ho, podeu formatar l'URL com aquest:

```
En un forat a terra hi vivia un hòbbit. No és un forat desagradable, brut i humit, ple d'excrements
de cucs i una olor supurada, ni tanmateix un forat sec, nu i sorrenc sense res per seure o per menjar: era un [forat-de-hobbit][1], i això vol dir comoditat.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Estils de vida hobbit"
```

En els dos casos anteriors, la sortida representada seria idèntica:

> En un forat a terra hi vivia un hòbbit. No és un forat desagradable, brut i humit, ple de puntes de cucs i una olor sudorosa, ni tanmateix un forat sec, nu i sorrenc sense res per seure o menjar: era un [forat de hobbit](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Estils de vida hobbit"), això vol dir comoditat.

i l'HTML de l'enllaç seria:

```
<a href="https://en.wikipedia.org/wiki/Hobbit#Lifestyle" title="Estils de vida de Hobbit">forat-de-hobbit</a>
```

### Bones pràctiques d'enllaços

Les aplicacions Markdown no estan d'acord sobre com gestionar els espais al mig d'un URL. Per a la compatibilitat, proveu de codificar l'URL qualsevol espai amb `%20`. Alternativament, si la vostra aplicació Markdown [admet HTML](#html), podeu utilitzar l'etiqueta HTML `<a>`.

<table>
   <thead>
     <tr>
       <th>✅&nbsp; Fes això</th>
       <th>❌&nbsp; No facis això</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>
         <code>
         [enllaç](https://www.example.com/my%20great%20page)<br><br>
         &lt;a href="https://www.example.com/la%20meva%20gran%20pàgina"&gt;enllaç&lt;/a&gt;<br><br>
         </codi>
       </td>
       <td>
         <code>
         [enllaç](https://www.example.com/la meva gran pàgina)<br><br>
         </codi>
       </td>
     </tr>
   </tbody>
</table>

Els parèntesis al mig d'un URL també poden ser problemàtics. Per a la compatibilitat, proveu de codificar l'URL del parèntesi d'obertura (`(`) amb `%28` i el parèntesi de tancament (`)`) amb `%29`. Alternativament, si la vostra aplicació Markdown [admet HTML](#html), podeu utilitzar l'etiqueta HTML `<a>`.

<table>
   <thead>
     <tr>
       <th>✅&nbsp; Fes això</th>
       <th>❌&nbsp; No facis això</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>
         <code>
         [una novel·la](https://en.wikipedia.org/wiki/The_Milagro_Beanfield_War_%28novel%29)<br><br>
         &lt;a href="https://en.wikipedia.org/wiki/The_Milagro_Beanfield_War_(novel)"&gt;una novel·la&lt;/a&gt;<br><br>
         </codi>
       </td>
       <td>
         <code>
         [una novel·la](https://en.wikipedia.org/wiki/The_Milagro_Beanfield_War_(novel·la))
         </codi>
       </td>
     </tr>
   </tbody>
</table>

## Vegeu també

[Guia Markdown](../README.md)
