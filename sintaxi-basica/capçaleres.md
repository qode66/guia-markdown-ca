## Capçaleres

Per a crear una capçalera, afegiu coixinets (#) davant d'una paraula o frase. El nombre de coixinets que utilitzeu hauria de correspondre al nivell de l'encapçalament. Per exemple, per crear un nivell d'encapçalament tres (`<h3>`), utilitzeu tres coixinets (p. ex., ### La meva capçalera).

<style>
table, th, td {
	border: 1px solid white;
        border-collapse: collapse;
}
td {
        font-size: 0.8em;
        padding-left: 1em;
        padding-right: 1em;
}
</style>
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
      <td><code># Capçalera 1</code></td>
      <td><code>&lt;h1&gt;Capçalera 1&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip>Capçalera 1</h1></td>
    </tr>
    <tr>
      <td><code>## Capçalera 2</code></td>
      <td><code>&lt;h2&gt;Capçalera 2&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip>Capçalera 2</h2></td>
    </tr>
    <tr>
      <td><code>### Capçalera 3</code></td>
      <td><code>&lt;h3&gt;Capçalera 3&lt;/h3&gt;</code></td>
      <td><h3 class="no-anchor" data-toc-skip>Capçalera 3</h3></td>
    </tr>
    <tr>
      <td><code>#### Capçalera 4</code></td>
      <td><code>&lt;h4&gt;Capçalera  4&lt;/h4&gt;</code></td>
      <td><h4 class="no-anchor">Capçalera 4</h4></td>
    </tr>
    <tr>
      <td><code>##### Capçalera 5</code></td>
      <td><code>&lt;h5&gt;Capçalera 5&lt;/h5&gt;</code></td>
      <td><h5 class="no-anchor">Capçalera 5</h5></td>
    </tr>
    <tr>
      <td><code>###### Capçalera 6</code></td>
      <td><code>&lt;h6&gt;Capçalera 6&lt;/h6&gt;</code></td>
      <td><h6 class="no-anchor">Capçalera 6</h6></td>
    </tr>
  </tbody>
</table>

### Sintaxi alternativa

Alternativament, a la línia de sota del text, afegiu qualsevol nombre de caràcters == per al nivell d'encapçalament 1 o -- caràcters per al nivell d'encapçalament 2.

<style>
table, th, td {
	border: 1px solid white;
        border-collapse: collapse;
}
td {
        font-size: 0.8em;
        padding-left: 1em;
        padding-right: 1em;
}
</style>
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
      <td><code>Capçalera 1<br/>===============</code></td>
      <td><code>&lt;h1&gt;Capçalera 1&lt;/h1&gt;</code></td>
      <td><h1 class="no-anchor" data-toc-skip>Capçalera 1</h1></td>
    </tr>
    <tr>
      <td><code>Capçalera 2<br/>---------------</code></td>
      <td><code>&lt;h2&gt;Capçalera 2&lt;/h2&gt;</code></td>
      <td><h2 class="no-anchor" data-toc-skip>Capçalera 2</h2></td>
    </tr>
  </tbody>
</table>

### Bones pràctiques d'encapçalament

Les aplicacions Markdown no estan d'acord en com gestionar un espai que manca entre els signes numèrics (`#`) i el nom de la capçalera. Per compatibilitat, posa sempre un espai entre els signes numèrics i el nom de la capçalera.

<table>
  <thead>
    <tr>
      <th>✅&nbsp; Fes aixó</th>
      <th>❌&nbsp; No ho facis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>
          # Aquí hi ha una capçalera
        </code>
      </td>
      <td>
        <code>
          #Aquí hi ha una capçalera
        </code>
      </td>
    </tr>
  </tbody>
</table>

També hauríeu de posar línies en blanc abans i després d'una capçalera per compatibilitat.

<style>
table, th, td {
	border: 1px solid white;
        border-collapse: collapse;
}
td {
        font-size: 0.8em;
        padding-left: 1em;
        padding-right: 1em;
}
</style>

<table>
  <thead>
    <tr>
      <th>✅&nbsp; Fes aixó</th>
      <th>❌&nbsp; No ho facis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>
        Intenteu posar una línia en blanc abans...<br><br>
        # Capçalera<br><br>
        ...i després d'una capçalera.
        </code>
      </td>
      <td>
        <code>
        Sense línies en blanc, això podria no semblar correcte.<br>
        # Capçalera<br>
        No ho facis!
        </code>
      </td>
    </tr>
  </tbody>
</table>

## Vegeu també

[Guia Markdown](../README.md)
