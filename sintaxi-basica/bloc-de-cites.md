## Bloc de cites

Per a crear una bloc de cita, afegiu un > davant d'un paràgraf.

```
> Dorothy la va seguir a través de moltes de les belles habitacions del seu castell.
```

La sortida renderitzada es veu així:

> Dorothy la va seguir a través de moltes de les belles habitacions del seu castell.

### Bloc de cites amb múltiples paràgrafs

Les Bloc de cites poden contenir diversos paràgrafs. Afegeix un `>` a les línies en blanc entre els paràgrafs.

```
> Dorothy la va seguir a través de moltes de les belles habitacions del seu castell.
>
> La Bruixa li fa malbé netejar les cassoles i els casquets i escombra el terra i manté el foc alimentat amb fusta.
```

La sortida renderitzada es veu així:

> Dorothy la va seguir a través de moltes de les belles habitacions del seu castell.
>
> La Bruixa li fa malbé netejar les cassoles i els casquets i escombra el terra i manté el foc alimentat amb fusta.

### Cites niades

Les Bloc de cites es poden niar. Afegiu un `>>` davant del paràgraf que voleu niar.

```
> Dorothy la va seguir a través de moltes de les belles habitacions del seu castell.
>
>> La Bruixa li fa malbé netejar les cassoles i els casquets i escombra el terra i manté el foc alimentat amb fusta.
```

La sortida renderitzada es veu així:

> Dorothy la va seguir a través de moltes de les belles habitacions del seu castell.
>
> > La Bruixa li fa malbé netejar les cassoles i els casquets i escombra el terra i manté el foc alimentat amb fusta.

### Bloc de cites amb altres elements

Les Bloc de cites poden contenir altres elements amb format Markdown. No es poden utilitzar tots els elements, haureu d'experimentar per veure quins funcionen.

```
> ### Els resultats trimestrals són fantàstics!
>
> - Els ingressos estaven fora de la llista.
> - Els beneficis van ser més alts que mai.
>
> *Tot* va segons el **pla**.
```

La sortida renderitzada es veu així:

> <h3>Els resultats trimestrals són fantàstics!</h3>
>
> - Els ingressos estaven fora de la llista.
> - Els beneficis van ser més alts que mai.
>
> _Tot_ va segons el **pla**.

### Bloc de cites, bones pràctiques

Per compatibilitat, poseu línies en blanc abans i després de les Bloc de cites.

<table>
  <thead>
    <tr>
      <th>✅ Fes això</th>
      <th>❌ No ho facis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>
        Intenteu posar una línia en blanc abans...<br><br>
        > Aquesta és una bloc de cita<br><br>
        ...i després d'una bloc de cita.
        </code>
      </td>
      <td>
        <code>
        Sense línies en blanc, això podria no semblar correcte.<br>
        > Aquesta és una bloc de cita<br>
        No ho facis!
        </code>
      </td>
    </tr>
  </tbody>
</table>

## Vegeu també

[Guia Markdown](../README.md)
