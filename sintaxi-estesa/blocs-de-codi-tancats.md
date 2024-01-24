## Blocs de codi tancats

```text
{
"firstName": "John",
"lastName": "Smith",
"edat": 25
}
```

La sintaxi bàsica de Markdown permet crear [blocs de codi](../sintaxi-basica/codi.md/) sagnant les línies per quatre espais o una tabulació. Si ho trobeu incòmode, proveu d'utilitzar blocs de codi tancats. Depenent del vostre processador o editor Markdown, utilitzareu tres accents greus (` ``` `) o tres titlles (`~~~`) a les línies abans i després del bloc de codi. La millor part? No heu de sagnat cap línia!

```text
~~~
{
  "firstName": "John",
  "lastName": "Smith",
  "edat": 25
}
~~~
```

La sortida renderitzada es veu així:

```text
{
  "firstName": "John",
  "lastName": "Smith",
  "edat": 25
}
```

> **Consell:** Necessita mostrar retroactivament dins d'un bloc de codi? Vegeu [aquesta secció](../sintaxi-basica/escapament.md) per aprendre a escapar-los.

### Ressaltat de la sintaxi

Molts processadors Markdown admeten el ressaltat de sintaxi per a blocs de codi tancats. Aquesta característica permet afegir el ressaltat del color per a qualsevol idioma en què s'hagi escrit el codi. Per a afegir el ressaltat de la sintaxi, especifiqueu un idioma al costat de les rèpliques abans del bloc de codi tancat.

````
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "edat": 25
}
```
````

La sortida renderitzada es veu així:

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "edat": 25
}
```

## Vegeu també

[blocs de codi](../sintaxi-basica/codi.md/)

[Guia Markdown](../README.md)
