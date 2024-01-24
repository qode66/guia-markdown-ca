## Format de taula

Les [taules de Markdown](../sintaxi-estesa/taules.md) són notòriament delicades. No podeu utilitzar molts elements de sintaxi Markdown per a formatar el text a les cel·les de la taula. Però hi ha solucions per almenys dos problemes comuns de taula: salts de línia i llistes.

### Salts de línia dins de les cel·les de la taula

Podeu separar paràgrafs dins d'una cel·la de la taula utilitzant una o més etiquetes HTML `<br>`.

```markdown
| Sintaxi   | Descripció                               |
| --------- | ---------------------------------------- |
| Capçalera | Títol                                    |
| Paràgraf  | Primer paràgraf. <br><br>Segon paràgraf. |
```

La sortida renderitzada es veu així:

| Sintaxi   | Descripció                               |
| --------- | ---------------------------------------- |
| Capçalera | Títol                                    |
| Paràgraf  | Primer paràgraf. <br><br>Segon paràgraf. |

### Llistes dins de les cel·les de la taula

Podeu afegir una llista dins d'una cel·la de taula utilitzant etiquetes HTML.

```markdown
| Sintaxi   | Descripció                                                                |
| --------- | ------------------------------------------------------------------------- |
| Capçalera | Títol                                                                     |
| Llista    | Aquí teniu una llista! <ul><li>Item primer.</li><li>Item segon.</li></ul> |
```

La sortida renderitzada té aquest aspecte:

| Sintaxi   | Descripció                                                                |
| --------- | ------------------------------------------------------------------------- |
| Capçalera | Títol                                                                     |
| Llista    | Aquí teniu una llista! <ul><li>Item primer.</li><li>Item segon.</li></ul> |

## Vegeu també

[taules de Markdown](../sintaxi-estesa/taules.md)

[Guia Markdown](../README.md)
