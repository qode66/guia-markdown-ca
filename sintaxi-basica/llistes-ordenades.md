### Llistes ordenades

Per a crear una llista ordenada, afegiu elements de línia amb números seguits de punts. Els números no han d'estar en ordre numèric, però la llista hauria de començar amb el número u.

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
         1. Primer element<br/>
         2. Segon element<br/>
         3. Tercer article<br/>
         4. Quart ítem
       </codi>
     </td>
     <td>
       <code>
         &lt;ol&gt;<br>
           &nbsp;&nbsp;&lt;li&gt;Primer element&lt;/li&gt;<br/>
           &nbsp;&nbsp;&lt;li&gt;Segon element&lt;/li&gt;<br/>
           &nbsp;&nbsp;&lt;li&gt;Tercer article&lt;/li&gt;<br/>
           &nbsp;&nbsp;&lt;li&gt;Quart element&lt;/li&gt;<br/>
         &lt;/ol&gt;
       </codi>
     </td>
     <td>
       <ol>
         <li>Primer element</li>
         <li>Segon element</li>
         <li>Tercer element</li>
         <li>Quart element</li>
       </ol>
     </td>
     </tr>
     <tr>
       <td>
         <code>
           1. Primer element<br/>
           1. Segon element<br/>
           1. Tercer article<br/>
           1. Quart element
         </codi>
       </td>
       <td>
         <code>
           &lt;ol&gt;<br>
             &nbsp;&nbsp;&lt;li&gt;Primer element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Segon element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Tercer article&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Quart element&lt;/li&gt;<br/>
           &lt;/ol&gt;
         </codi>
       </td>
       <td>
         <ol>
           <li>Primer element</li>
           <li>Segon element</li>
           <li>Tercer element</li>
           <li>Quart element</li>
         </ol>
       </td>
     </tr>
     <tr>
       <td>
         <code>
           1. Primer element<br/>
           8. Segon element<br/>
           3. Tercer article<br/>
           5. Quart ítem
         </codi>
       </td>
       <td>
         <code>
           &lt;ol&gt;<br>
             &nbsp;&nbsp;&lt;li&gt;Primer element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Segon element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Tercer article&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Quart element&lt;/li&gt;<br/>
           &lt;/ol&gt;
         </codi>
       </td>
       <td>
         <ol>
           <li>Primer element</li>
           <li>Segon element</li>
           <li>Tercer element</li>
           <li>Quart element</li>
         </ol>
       </td>
     </tr>
     <tr>
       <td>
         <code>
           1. Primer element<br/>
           2. Segon element<br/>
           3. Tercer article<br/>
           &nbsp;&nbsp;&nbsp;&nbsp;1. Element sagnat<br/>
           &nbsp;&nbsp;&nbsp;&nbsp;2. Element sagnat<br/>
           4. Quart ítem
         </codi>
       </td>
       <td>
         <code>
           &lt;ol&gt;<br>
             &nbsp;&nbsp;&lt;li&gt;Primer element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Segon element&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Tercer article<br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&lt;ol&gt;<br>
                 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Element sagnat&lt;/li&gt;<br/>
                 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;Element sagnat&lt;/li&gt;<br/>
               &nbsp;&nbsp;&nbsp;&nbsp;&lt;/ol&gt;<br/>
             &nbsp;&nbsp;&lt;/li&gt;<br/>
             &nbsp;&nbsp;&lt;li&gt;Quart element&lt;/li&gt;<br/>
           &lt;/ol&gt;
         </codi>
       </td>
       <td>
         <ol>
           <li>Primer element</li>
           <li>Segon element</li>
           <li>Tercer element
             <ol>
               <li>Element sagnat</li>
               <li>Element sagnat</li>
             </ol>
           </li>
           <li>Quart element</li>
         </ol>
       </td>
     </tr>
   </tbody>
</table>

#### Llista ordenada, bones pràctiques

El CommonMark i alguns altres llenguatges de marcat lleugers permeten utilitzar un parèntesi (`)`) com a delimitador (p. ex., `1) Primer element`), però no totes les aplicacions Markdown ho admeten, de manera que no és una gran opció des d'una perspectiva de compatibilitat. Per compatibilitat, utilitza només els punt.

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
           1. Primer element<br>
           2. Segon article
         </codi>
       </td>
       <td>
         <code>
           1) Primer article<br>
           2) Segon article
         </codi>
       </td>
     </tr>
   </tbody>
</table>

## Vegeu també

[Guia Markdown](../README.md)
