### Llista no ordenada

Per a crear una llista no ordenada, afegiu guions (`-`), asteriscs (`*`), o signes més (`+`) davant dels elements de línia. Sagna un o més elements per a crear una llista nidada.

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
           - Primer article<br/>
           - Segon article<br/>
           - Tercer article<br/>
           - Quart element
         </codi>
       </td>
       <td>
         <code>
           &lt;ul&gt;<br>
             &nbsp;&nbsp;&lt;li&gt;Primer element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Segon element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Tercer article&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Quart element&lt;/li&gt;<br/>
           &lt;/ul&gt;
         </codi>
       </td>
       <td>
         <ul>
           <li>Primer element</li>
           <li>Segon element</li>
           <li>Tercer element</li>
           <li>Quart element</li>
         </ul>
       </td>
     </tr>
     <tr>
       <td>
         <code>
           * Primer article<br/>
           * Segon article<br>
           * Tercer article<br/>
           * Quart element
         </codi>
       </td>
       <td>
         <code>
           &lt;ul&gt;<br>
             &nbsp;&nbsp;&lt;li&gt;Primer element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Segon element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Tercer article&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Quart element&lt;/li&gt;<br/>
           &lt;/ul&gt;
         </codi>
       </td>
       <td>
         <ul>
           <li>Primer element</li>
           <li>Segon element</li>
           <li>Tercer element</li>
           <li>Quart element</li>
         </ul>
       </td>
     </tr>
     <tr>
       <td>
         <code>
           + Primer element<br/>
           + Segon element<br/>
           + Tercer element<br/>
           + Quart element
         </codi>
       </td>
       <td>
         <code>
           &lt;ul&gt;<br>
             &nbsp;&nbsp;&lt;li&gt;Primer element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Segon element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Tercer article&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Quart element&lt;/li&gt;<br/>
           &lt;/ul&gt;
         </codi>
       </td>
       <td>
         <ul>
           <li>Primer element</li>
           <li>Segon element</li>
           <li>Tercer element</li>
           <li>Quart element</li>
         </ul>
       </td>
     </tr>
     <tr>
       <td>
         <code>
           - Primer article<br/>
           - Segon article<br/>
           - Tercer article<br/>
           &nbsp;&nbsp;&nbsp;&nbsp;- Element sagnat<br/>
           &nbsp;&nbsp;&nbsp;&nbsp;- Element sagnat<br/>
           - Quart element
         </codi>
       </td>
       <td>
         <code>
           &lt;ul&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Primer element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Segon element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Tercer article<br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&lt;ul&gt;<br/>
                 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Element sagnat&lt;/li&gt;<br/>
                 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Element sagnat&lt;/li&gt;<br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&lt;/ul&gt;<br/>
             &nbsp;&nbsp;&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Quart element&lt;/li&gt;<br/>
           &lt;/ul&gt;
         </codi>
       </td>
       <td>
         <ul>
           <li>Primer element</li>
           <li>Segon element</li>
           <li>Tercer element
             <ul>
               <li>Element sagnat</li>
               <li>Element sagnat</li>
             </ul>
           </li>
           <li>Quart element</li>
         </ul>
       </td>
     </tr>
   </tbody>
</table>

#### Iniciant elements de llista sense ordenar amb números

Si necessiteu iniciar un element de llista sense ordenar amb un número seguit d'un punt, podeu utilitzar una barra inversa («\») per a [escapar](#caracters-de-escape) el punt.

<table>
   <thead>
     <tr>
       <th>Markdown</th>
       <th>HTML</th>
       <th>Sortida representada</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>
         <code>
           - 1968\. Un gran any!<br/>
           - Crec que el 1969 va ser el segon millor.
         </codi>
       </td>
       <td>
         <code>
           &lt;ul&gt;<br>
             &nbsp;&nbsp;&lt;li&gt;1968. Un gran any!&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Crec que el 1969 va ser el segon millor.&lt;/li&gt;<br/>
           &lt;/ul&gt;
         </codi>
       </td>
       <td>
         <ul>
           <li>1968. Un gran any!</li>
           <li>Crec que el 1969 va ser el segon millor.</li>
         </ul>
       </td>
     </tr>
   </tbody>
</table>

#### Bones pràctiques de llista sense ordenar

Les aplicacions Markdown no estan d'acord en com gestionar diferents delimitadors a la mateixa llista. Per compatibilitat, no barregeu ni concordeu amb els delimitadors de la mateixa llista — trieu-ne un i hi apunteu.

<table>
   <thead>
     <tr>
       <th>✅&nbsp; Fes això</th>
       <th>❌&nbsp; No facis això</th>
     </tr>
   </thead>
   <tbody>
     <tr>
       <td>
         <code>
           - Primer article<br>
           - Segon article<br>
           - Tercer article<br>
           - Quart element
         </codi>
       </td>
       <td>
         <code>
           + Primer element<br>
           * Segon article<br>
           - Tercer article<br>
           + Quart element
         </codi>
       </td>
     </tr>
   </tbody>
</table>

## Vegeu també

[Guia Markdown](../README.md)
