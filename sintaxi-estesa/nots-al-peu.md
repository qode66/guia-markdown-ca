# Notes al peu

Les notes al peu permeten afegir notes i referències sense desordenar el cos del document. Quan creeu una nota al peu, apareix un número de superíndex amb un enllaç on heu afegit la referència de la nota al peu. Els lectors poden fer clic a l'enllaç per saltar al contingut de la nota al peu a la part inferior de la pàgina.

Per a crear una referència de nota al peu, afegiu un accent circumflex i un identificador dins dels claudàtors (`[^1]`). Els identificadors poden ser números o paraules, però no poden contenir espais o tabuladors. Els identificadors només correlacionen la referència de la nota al peu amb la mateixa nota al peu — a la sortida, les notes al peu es numeren seqüencialment.

Afegiu la nota al peu utilitzant un altre cursor i un número dins dels claudàtors amb dos punts i text (`[^1]: La meva nota al peu.`). No cal posar notes al peu al final del document. Podeu posar-los a qualsevol lloc excepte dins d'altres elements com llistes, blocs de codi i taules.

```text
Aquí hi ha una simple nota a peu de pàgina,[^1] i aquí n'hi ha una més llarga.[^bignote]

[^1]: Aquesta és la primera nota al peu.

[.bignote]: Aquí n'hi ha un amb diversos paràgrafs i codi.

    Sagna els paràgrafs per a incloure'ls a la nota al peu.

    `{ el meu codi }`

    Afegiu tants paràgrafs com vulgueu.
```

La sortida renderitzada es veu així:

Aquí hi ha una simple nota a peu de pàgina,[^1] i aquí n'hi ha una més llarga.[^bignote]

[^1]: Aquesta és la primera nota al peu.

[.bignote]: Aquí n'hi ha un amb diversos paràgrafs i codi.

    Sagna els paràgrafs per a incloure'ls a la nota al peu.

    `{ el meu codi }`

    Afegiu tants paràgrafs com vulgueu.

## Vegeu també

[Guia Markdown](../README.md)
