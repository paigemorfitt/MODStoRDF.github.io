<!DOCTYPE html>

 <h1>Arminda MODS information page</h1> 
 
|[IMI Columns](https://github.com/paigemorfitt/MODStoRDF.github.io/wiki/IMI.html)| |[MODS Fields](https://github.com/paigemorfitt/MODStoRDF.github.io/wiki/MODS.html)| [RDF Fields](https://github.com/paigemorfitt/MODStoRDF.github.io/wiki/RDF.html)|


|IMI Columns | MODS Field | RDF Field| Comments|
|---|---|---|---|
   <th>IMI Column</th>
    <th>MODS field</th>
    <th>RDF field</th>
  </tr>
  <tr>
    <td><a href="abstract.html">abstract</a> (not finished)</td>
    <td>abstract</td>
    <td>dc:abstract</td>
  </tr>
  <tr>
    <td><a href="abstract_format.html">abstract_format</a></td>
    <td>abstract</td>
    <td>N/A</td>
   </tr>
   <tr>
    <td><a href="access_condition.html">access_condition</a></td>
    <td>accessCondition</td>
    <td>dc:accessRights</td>
  </tr>
   <tr>
    <td><a href="IMI.advisor.html">advisor1*</a></td>
    <td>name/namePart</td>
    <td>relators:ths</td>
  </tr>
     <tr>
    <td><a href="authors.html">authors*</a></td>
    <td>name/namePart</td>
    <td>relators:aut</td>
  </tr>
  <tr>
    <td><a href="conference_year.html">conference_year*</a></td>
    <td>originInfo/dateOther</td>
    <td>rdau:P60526</td>
  </tr>
     <tr>
    <td><a href="context_key.html">context_key*</a></td>
    <td>identifier</td>
    <td>dc:identifier</td>
  </tr>
  <tr>
    <td><a href="contributors.html">contributor</a></td>
    <td>name/namePart</td>
    <td>relators:ctb</td>
  </tr>
  <tr>
    <td><a href="department.html">department</a></td>
    <td>name/namePart</td>
    <td>relators:ctb</td>
  </tr>
  <tr>
    <td><a href="extent.html">extent**</a></td>
    <td>physicalDescription/extent</td>
    <td>dc:extent</td>
  </tr>
  <tr>
    <td><a href="genre.html">genre**</a></td>
    <td>genre</td>
    <td>schema:genre</td>
  </tr>
  <tr>
    <td><a href="graduation_year.html">graduation_year*</a></td>
    <td>originInfo/dateOther</td>
    <td>rdau:P60514</td>
  </tr>
    <tr>
    <td>license_file</td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>issue</td>
    <td>relatedItem/note</td>
    <td>dc:isPartOf</td>
  </tr>
    <tr>
    <td><a href="keywords.html">keywords</a></td>
    <td>subject/topic</td>
    <td>dc:subject</td>
  </tr>
    <tr>
    <td><a href="language.html">language</a></td>
    <td>language/languageTerm</td>
    <td>dc:language</td>
  </tr>
  <tr>
    <td><a href="mods_date_created_keydate.html">mods_date_created_keydate*</a></td>
    <td>originInfo/dateCreated</td>
    <td>dc:created</td>
  </tr>
    <tr>
    <td><a href="mods_display_date.html">mods_display_date*</a></td>
    <td>originInfo/dateOther</td>
    <td>dc:date</td>
  </tr>
    <tr>
    <td><a href="nonenglish_title.html">nonenglish_title*</a></td>
    <td>titleInfo/title</td>
    <td>dc:alternative</td>
  </tr>
    <tr>
    <td><a href="oai_harvester_date.html">oai_harvester_date*</a></td>
    <td>originInfo/dateOther</td>
    <td>rdau:P60324</td>
  </tr>
   <tr>
    <td><a href="rights.html">rights*</a></td>
    <td>accessCondition</td>
    <td>dc:rights</td>
  </tr>
   <tr>
    <td><a href="rights_statement.html">rights_statement</a></td>
    <td>accessCondition</td>
    <td>schema:license</td>
  </tr>
  <tr>
    <td><a href="title.html">title</a></td>
    <td>titleInfo/title</td>
    <td>dc:title</td>
  </tr>
  <tr>
    <td><a href="work_type.html">work_type</a></td>
    <td>typeOfResource</td>
    <td>dc:type</td>
  </tr>
</table>
<p>*Column to be renamed ; ** New column</p>
</body>