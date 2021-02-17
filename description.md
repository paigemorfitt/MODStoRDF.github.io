<!DOCTYPE html>
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

<h1>IMI/description</h1>
<p><a href="migration-questions.md">See migration questions</a></p>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>An account of the resource, primarily used for archival objects
</dd>
  <dd><ins><font color="brown">Obligation: </font></ins> Required</dd>
  <dd><ins><font color="brown">Repeatable: </font></ins>No</dd>
  <dd><ins><font color="brown">Public Field: </font></ins>Yes</dd>
  <dd><ins><font color="brown">Public-facing name:</font></ins>Description</dd>
  <dd><ins><font color="brown">Syntax/Formatting: </font></ins>Free-text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary: </font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Use complete sentences</li>
		<li>Some content moved from IMI/abstract</li>
		<li>Contains html, accents, and/or special characters</li>
	</ul>
	</dd>
  <dd><font><ins>Field Changes:</ins> </font>Contains content from IMI/abstract</dd>
</dl>
<dl>
    <dt><b>locations:</b></dt>
	  <dd> <ins><font color="brown">MODS XPath: </font>/mods/abstract</dd>
	<dd> <ins><font color="brown">RDF XPath: </font>/rdf:RDF/rdf:Description/dcterms:description</dd>
	<dd>
		<ul>
			<li>mods_abstract_displayLabel_ms: mods_abstract_displayLabel_ms(string)</li>
			<li>mods_abstract_ms: mods_abstract_ms(string)</li>
			<li>mods_abstract_abstract_displayLabel_ms: mods_abstract_abstract_displayLabel_ms(string)</li>
			<li>mods_abstract_description_displayLabel_ms: mods_abstract_description_displayLabel_ms(string)</li>
			<li>mods_abstract_description_ms: mods_abstract_description_ms(string)</li>
		</ul>
	</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>2/17/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.abstract.md">MODS/abstract</a></td>
			<td><a href="RDF.description.md">RDF/dcterms:description</a></td>
		</table>
</dl>
</body>
</html>