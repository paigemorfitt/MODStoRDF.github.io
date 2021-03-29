<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th>IMI Columns</th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="#">RDF Fields</a></th>
  </tr>
</table>

<h1>IMI/work_type</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins> Basic conceptual indication of the kind of object being described, using broad terms. </dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> No</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>Yes [Collection; Dataset; Image; Interactive Resource; Moving Image; Physical Object; Service; Software; Sound; Still Image; Text]</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>This information should relate to the original object, not the digitized surrogate</li>
		<li>If more than one present, record each value in new field</li>
		<li>Expectation: one type is sufficient for most object, however specific collections may have more guidance on particular cases</li>
		<li>If a term does not fit, bring to Metadata Working Group</li>
		<li>Born-digital uses this field for theming</li>
		<li>Newspaper generates field in TWIG</li>
		<li>We need this field in order to make our display work</li>
	</ul>
  </dd>
  <dd><font color="blue"><i>Field Changes: </i></font> Absorbed content from IMI/type_of_work</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
	<dd> <ins><font color="brown">MODS XPath </font></ins> /mods/typeOfResource </dd>
	<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/dcterms:type</dd>
	<dd> <ins><font color="brown">Solr Field(s)</font></ins>
		<ul>
			<li>mods_typeOfResource_ms: mods_typeOfResource_ms(string)</li>
			<li>mods_typeOfResource_displayLabel_ms: mods_typeOfResource_displayLabel_ms(string)</li>
		</ul>
	</dd>
	<p><font color="red"><i>Last Updated: </i></font>3/29/2021</p>
</dl>
<dl>
<dd><b>Related Fields</b></dd>
	<table>
		<td><a href="mods.typeOfResource.md">MODS/typeOfResource</a></td>
		<td><a href="rdf.type.md">RDF/dcterms:type</a></td>
	</table>
</dl>
</body>
</html>