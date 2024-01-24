## Salts de línia

Per a crear un salt de línia o una nova línia (`<br>`), finalitzeu una línia amb dos o més espaés, i després escriviu retorn.

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
      <td>
        <code>
          Aquesta és la primera línia. <br>
          I aquesta és la segona línia.
        </code>
      </td>
      <td>
        <code>&lt;p&gt;Aquesta és la primera línia.&lt;br&gt;<br />
        I aquesta és la segona línia.&lt;/p&gt;</code>
      </td>
      <td>
        <p>Aquesta és la primera línia.<br />   
        I aquesta és la segona línia.</p>
      </td>
    </tr>
  </tbody>
</table>

### Bones pràctiques del salt de línia

Podeu utilitzar dos o més espaés (comunament anomenats «espaés en blanc de rastreig») per als salts de línia en gairebé totes les aplicacions Markdown, però és controvertit. És difícil veure els espaés en blanc finals en un editor, i moltes persones accidentalment o intencionadament posen dos espaés després de cada frase. Per aquesta raó, és possible que vulgueu utilitzar alguna cosa més que els espaés en blanc finals per als salts de línia. Si la vostra aplicació Markdown admet HTML, podeu utilitzar l'etiqueta HTML `<br>`.

Per compatibilitat, utilitzeu espaés en blanc finals o l'etiqueta HTML `<br>` al final de la línia.

Hi ha altres dues opcions que no recomano utilitzar. El CommonMark i alguns altres llenguatges de marcat lleugers permeten escriure una barra inversa (`\`) al final de la línia, però no totes les aplicacions Markdown ho admeten, de manera que no és una gran opció des d'una perspectiva de compatibilitat. I com a mínim un parell de llenguatges de marcat lleugers no requereixen res al final de la línia — només cal que escriviu retorn i crearan un salt de línia.

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
          Primera línia amb dos espaés després. <br>I la següent línia. <br><br>Primera línia amb l'etiqueta HTML després de &lt;br&gt; <br> I la següent línia.<br><br>
        </code>
      </td>
      <td>
        <code>
        Primera línia després de la barra inversa.\<br>
        I la següent línia.<br><br>
        Primera línia sense res després.<br>
        I la següent línia.<br><br>
        </code>
      </td>
    </tr>
  </tbody>
</table>

## Vegeu també

[Guia Markdown](../README.md)
