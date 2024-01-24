# ID d'encapçalament

Molts processadors Markdown admeten identificadors personalitzats per a [encapçalament](../sintaxi-basica/capçaleres.md) - alguns processadors Markdown els afegeixen automàticament. Afegir identificadors personalitzats us permet enllaçar directament als encapçalaments i modificar-los amb CSS. Per afegir un identificador d'encapçalament personalitzat, afegiu l'identificador personalitzat entre claus a la mateixa línia que l'encapçalament.

```text
### El meu gran títol {#id-personalitzat}
```

L'HTML té aquest aspecte:

```html
<h3 id="custom-id">El meu gran títol</h3>
```

## Enllaç als identificadors d'encapçalament

Podeu enllaçar als encapçalaments amb identificadors personalitzats al fitxer creant un [enllaç estàndard](../sintaxi-basica/enllaços.md) amb un coixinet (`#`) seguit de l'ID de l'encapçalament personalitzat. Aquests s'anomenen habitualment _enllaços d'ancoratge_.

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
       <td><code>[ID d'encapçalament](#heading-ids)</code></td>
       <td><code> &lt;a href="#heading-ids"&gt;IDs d'encapçalament&lt;/a&gt;</code></td>
       <td><a href="#heading-ids">Identificadors d'encapçalament</a></td>
     </tr>
   </tbody>
</table>

Altres llocs web poden enllaçar a l'encapçalament afegint l'ID de l'encapçalament personalitzat a l'URL complet de la pàgina web (p. ex., "[Identificadors d'encapçalament](https://www.qode66.xyz/markdown/sintaxi-estesa/id-encapçalament#id-encapçalament)").

## Vegeu també

[encapçalament](../sintaxi-basica/capçaleres.md)  
[Identificadors d'encapçalament](https://www.qode66.xyz/markdown/sintaxi-estesa/id-encapçalament#id-encapçalament)

[Guia Markdown](../README.md)
