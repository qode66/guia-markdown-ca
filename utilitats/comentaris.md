## Comentaris

Algunes persones necessiten la capacitat d'escriure frases als seus fitxers Markdown que _no apareixeran_ a la sortida renderitzada. Aquests comentaris són essencialment un text ocult. L'autor del document pot veure el text, però no s'imprimeix a la pàgina web o PDF. Markdown no dóna suport natiu als comentaris, però diversos individus emprenedors han ideat una solució.

Per a afegir un comentari, situeu el text dins dels claudàtors seguits d'un dos punts, un espai i un coixinet (p. ex., `[comment]: #`). Heu de posar línies en blanc abans i després d'un comentari.

```text
Aquest és un paràgraf que serà visible.

[Aquest és un comentari que s'ocultarà]: #

I aquest és un altre paràgraf que és visible.
```

La sortida renderitzada es veu així:

Aquest és un paràgraf que serà visible.

[Aquest és un comentari que s'ocultarà]: #

I aquest és un altre paràgraf que és visible.

> **Consell:** Aquest consell ve de [Stack Overflow](https://stackoverflow.com/questions/4823468/comments-in-markdown). Ha estat revisat per experts i utilitzat per milers de persones!

## Vegeu també

[Guia Markdown](../README.md)
