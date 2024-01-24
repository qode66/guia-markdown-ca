# Llistes de definicions

Alguns processadors Markdown permeten crear _llistes de definició_ dels termes i les seves definicions corresponents. Per a crear una llista de definicions, escriviu el terme a la primera línia. A la línia següent, escriviu els dos punts seguit d'un espai i la definició.

```text
Primer terme
:Aquesta és la definició del primer terme.

Segon terme
:Aquesta és una definició del segon terme.
:Aquesta és una altra definició del segon terme.
```

L'HTML es veu així:

```html
<dl>
  <dt>Primer terme</dt>
  <dd>Aquesta és la definició del primer terme.</dd>
  <dt>Segon terme</dt>
  <dd>Aquesta és una definició del segon terme.</dd>
  <dd>Aquesta és una altra definició del segon terme.</dd>
</dl>
```

La sortida renderitzada es veu així:

<dl>
  <dt>Primer terme</dt>
  <dd>Aquesta és la definició del primer terme.</dd>
  <dt>Segon terme</dt>
  <dd>Aquesta és una definició del segon terme.</dd>
  <dd>Aquesta és una altra definició del segon terme.</dd>
</dl>

## Vegeu també

[Guia Markdown](../README.md)
