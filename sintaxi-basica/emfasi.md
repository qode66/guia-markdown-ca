## Èmfasi

Podeu afegir èmfasi fent text en negreta o cursiva.

### Negreta

Per a un text en negreta, afegiu dos asteriscs o guions baixos abans i després d'una paraula o frase. Per a negreta la meitat d'una paraula per a l'èmfasi, afegiu dos asteriscs sense espais al voltant de les lletres.

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
      <td><code>Només m'encanta el **text negreta**.</code></td>
      <td><code>Només m'encanta el &lt;strong&gt;text negreta&lt;/strong&gt;.</code></td>
      <td>Només m'encanta el <strong>text negreta</strong>.</td>
    </tr>
    <tr>
      <td><code>Només m'encanta el __text negreta__.</code></td>
      <td><code>Només m'encanta el &lt;strong&gt;text negreta&lt;/strong&gt;.</code></td>
      <td>Només m'encanta el <strong>text negreta</strong>.</td>
    </tr>
    <tr>
      <td><code>L'amor**és**negreta</code></td> <td><code>L'amor&lt;strong&gt;és&lt;/strong&gt;negreta</code></td>
      <td>L'amor<strong>és</strong>negreta</td>
    </tr>
  </tbody>
</table>

#### Bones pràctiques en negreta

Les aplicacions Markdown no estan d'acord en com gestionar els subratllats enmig d'una paraula. Per compatibilitat, utilitzeu asteriscs per a negreta la meitat d'una paraula per a l'èmfasi.

<table>
  <thead>
    <tr>
      <th>✅&nbsp; Fes això</th>
      <th>❌&nbsp; No ho facis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>
          L'amor**és**negreta
        </code>
      </td>
      <td>
        <code>
          L'amor__és__negreta
        </code>
      </td>
    </tr>
  </tbody>
</table>

### Itàlica

Per a fer cursiva el text, afegiu un asterisc o subratllat abans i després d'una paraula o frase. Per a fer cursiva la meitat d'una paraula per a emfatitzar, afegiu un asterisc sense espais al voltant de les lletres.

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
      <td><code>El text en cursiva és el *miau del gat*.</code></td>
      <td><code>El text en cursiva és el &lt;em&gt;miau del gat&lt;/em&gt;.</code></td>
      <td>El text en cursiva és el <em>miau del gat</em>.</td>
    </tr>
    <tr>
      <td><code>El text en cursiva és el _miau del gat_.</code></td>
      <td><code>El text en cursiva és el &lt;em&gt;miau del gat&lt;/em&gt;.</code></td>
      <td>El text en cursiva és el <em>miau del gat</em>.</td>
    </tr>
    <tr>
      <td><code>Un *miau* de gat</code></td>
      <td><code>Un &lt;em&gt;miau&lt;/em&gt; de gat</code></td>
      <td>Un <em>miau</em> de gat</td>
    </tr>
  </tbody>
</table>

#### Bones pràctiques en cursiva

Les aplicacions de Markdown no estan d'acord sobre com gestionar els guions baixos al mig d'una paraula. Per a la compatibilitat, utilitzeu asteriscs per posar en cursiva el mig d'una paraula per emfatitzar.

<table>
  <thead>
    <tr>
      <th>✅&nbsp; Fes això</th>
      <th>❌&nbsp; No ho facis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>
          Un *miau* de gat
        </code>
      </td>
      <td>
        <code>
          Un _miau_ de gat
        </code>
      </td>
    </tr>
  </tbody>
</table>

### Negreta i cursiva

Per emfatitzar el text amb negreta i cursiva alhora, afegiu tres asteriscs o guions baixos abans i després d'una paraula o frase. Per posar en negreta i cursiva el mig d'una paraula per emfatitzar, afegiu tres asteriscs sense espais al voltant de les lletres.

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
      <td><code>Aquest text és ***molt important***.</code></td>
      <td><code>Aquest text és &lt;em&gt;&lt;strong&gt;molt important&lt;/strong&gt;&lt;/em&gt;.</code></td>
      <td>Aquest text és <em><strong>molt important</strong></em>.</td>
    </tr>
    <tr>
      <td><code>Aquest text és ___molt important___.</code></td>
      <td><code>Aquest text és &lt;em&gt;&lt;strong&gt;molt important&lt;/strong&gt;&lt;/em&gt;.</code></td>
      <td>Aquest text és <em><strong>molt important</strong></em>.</td>
    </tr>
    <tr>
      <td><code>Aquest text és __*molt important*__.</code></td>
      <td><code>Aquest text és &lt;em&gt;&lt;strong&gt;molt important&lt;/strong&gt;&lt;/em&gt;.</code></td>
      <td>Aquest text és <em><strong>molt important</strong></em>.</td>
    </tr>
    <tr>
      <td><code>Aquest text és **_molt important_**.</code></td>
      <td><code>Aquest text és &lt;em&gt;&lt;strong&gt;molt important&lt;/strong&gt;&lt;/em&gt;.</code></td>
      <td>Aquest text és <em><strong>molt important</strong></em>.</td>
    </tr>
    <tr>
      <td><code>Aquest text és molt***molt***important.</code></td>
      <td><code>Aquest text és molt&lt;em&gt;&lt;strong&gt;molt&lt;/strong&gt;&lt;/em&gt;important.</code></td>
      <td>Aquest text és molt <em><strong>molt</strong></em> important.</td>
    </tr>
  </tbody>
</table>

#### Bones pràctiques en negreta i cursiva

Les aplicacions de Markdown no estan d'acord sobre com gestionar els guions baixos al mig d'una paraula. Per a la compatibilitat, utilitzeu asteriscs en negreta i cursiva al mig d'una paraula per emfatitzar.

<table>
  <thead>
    <tr>
      <th>✅&nbsp; Fes això</th>
      <th>❌&nbsp; No ho facis</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>
          Aquest text és molt ***molt***important.
        </code>
      </td>
      <td>
        <code>
          Aquest text és molt ___molt___important.
        </code>
      </td>
    </tr>
  </tbody>
</table>

## Vegeu també

[Guia Markdown](../README.md)
