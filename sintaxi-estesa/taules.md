## Taules

Per afegir una taula, utilitzeu tres o més guions (`---`) per crear la capçalera de cada columna i utilitzeu barres verticals (`|`) per separar cada columna. Per a la compatibilitat, també hauríeu d'afegir una barra a cada extrem de la fila.

```text
| Sintaxi | Descripció |
| ----------- | ----------- |
| Capçalera | Títol |
| Paràgraf | Text |
```

La sortida renderitzada té aquest aspecte:

| Sintaxi   | Descripció |
| --------- | ---------- |
| Capçalera | Títol      |
| Paràgraf  | Text       |

L'amplada de les cel·les pot variar, tal com es mostra a continuació. La sortida renderitzada tindrà el mateix aspecte.

```text
| Sintaxi | Descripció |
| --- | ----------- |
| Capçalera | Títol |
| Paràgraf | Text |
```

> **Consell**: crear taules amb guions i barres verticals pot ser tediós. Per accelerar el procés, proveu d'utilitzar el [Markdown Tables Generator](https://www.tablesgenerator.com/markdown_tables) o l'[AnyWayData Markdown Export](https://anywaydata.com). Creeu una taula utilitzant la interfície gràfica i, a continuació, copieu el text amb format Markdown generat al vostre fitxer.

### Alineació

Podeu alinear el text de les columnes a l'esquerra, a la dreta o al centre afegint dos punts (`:`) a l'esquerra, a la dreta o als dos costats dels guions dins de la fila de la capçalera.

```text
| Sintaxi | Descripció | Text de prova |
| :--- | :----: | ---: |
| Capçalera | Títol | Aquí teniu aquest |
| Paràgraf | Text | I més |
```

La sortida renderitzada té aquest aspecte:

| Sintaxi   | Descripció |   Text de prova |
| :-------- | :--------: | --------------: |
| Capçalera |   Títol    | Aquí teniu això |
| Paràgraf  |    Text    |           i més |

### Format del text a les taules

Podeu formatar el text dins de les taules. Per exemple, podeu afegir [enllaços](../sintaxi-basica/enllaços.md), [codi](../sintaxi-basica/codi.md) (paraules o frases entre accents greus (`` ` ``) només, no [blocs de codi](../sintaxi-basica/codi.md) i [èmfasi](../sintaxi-basica/emfasi.md).

No podeu utilitzar encapçalaments, bloc de cites, llistes, línies horitzontals, imatges o la majoria de les etiquetes HTML.

> **Consell:** podeu utilitzar HTML per crear [salts de línia](../utilitats/formatant-taules.md/#salt-linia-cella-taula) i afegir [llistes](../utilitats/formatant-taules.md) a les cel·les de la taula.

### Escapament de caràcters de barres verticals a les taules

Podeu mostrar un caràcter pipe (`|`) en una taula utilitzant el seu codi de caràcter HTML (`&#124;`).

## Vegeu també

[enllaços](../sintaxi-basica/enllaços.md)  
[codi](../sintaxi-basica/codi.md)  
[blocs de codi](../sintaxi-basica/codi.md)  
[èmfasi](../sintaxi-basica/emfasi.md)

[Guia Markdown](../README.md)
