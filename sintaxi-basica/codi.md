## Codi

Per indicar una paraula o frase com a codi, tanqueu-la entre els accents greus (`` ` ``).

<table>
   <thead>
     <tr>
       <th>Markdown</th>
       <th>HTML</th>
       <th>Renderitzat</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td><code>A l'indicador d'ordres, escriviu `nano`.</code></td>
       <td><code>A l'indicador d'ordres, escriviu &lt;code&gt;nano&lt;/code&gt;. </code></td>
       <td>A l'indicador d'ordres, escriviu <code>nano</code>.</td>
     </tr>
   </tbody>
</table>

### Escapant els accents greus

Si la paraula o frase que voleu indicar com a codi inclou un o més accents greus, podeu escapar-ne tancant la paraula o frase en dos backticks (<code>``</code>).

<table>
   <thead>
     <tr>
       <th>Markdown</th>
       <th>HTML</th>
       <th>Renderitzat</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td><code>``Utilitzeu `codi` al vostre fitxer Markdown.``</code></td>
       <td><code>&lt;code&gt;Utilitzeu `codi` al vostre fitxer Markdown.&lt;/code&gt;</code></td>
       <td><code>Utilitzeu `codi` al vostre fitxer Markdown.</code></td>
     </tr>
   </tbody>
</table>

### Blocs de codi

Per crear blocs de codi, sagneu cada línia del bloc almenys quatre espais o una pestanya.

```text
     <html>
       <cap>
       </cap>
     </html>
```

La sortida renderitzada té aquest aspecte:

```text
<html>
   <cap>
   </cap>
</html>
```

> <strong>Nota:</strong> per crear blocs de codi sense sagnar línies, utilitzeu blocs de codi tancats

## Vegeu també

[Guia Markdown](../README.md)
