<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th><a href="IMI.md">IMI Columns</a></th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="RDF.md">RDF Fields</a></th>
  </tr>
</table>

<h1>IMI/abstract</h1>
<p><a href="migration-questions.md">See migration questions</a></p>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins>ARMINDA Use:</font></ins>A summary of the resource, primarily used with scholarship objects</dd>
  <dd><ins>Obligation: </ins> Required, if applicable</dd>
  <dd><ins>Repeatable: </ins>No</dd>
  <dd><ins>Public Field: </ins>Yes</dd>
  <dd><ins>Public-facing name </ins>Abstract</dd>
  <dd><ins>Syntax/Formatting: </ins>Free-text</dd>
  <dd><ins>Recommended Controlled Vocabulary: </ins>N/A</dd>
  <dd><ins>Notes: </ins>
	<ul>
		<li>Use complete sentences</li>
		<li>Some contents moved to IMI/description</li>
		<li>Contains html, accents, and/or special characters</li>
	</ul>
	</dd>
  <dd><font><ins>Field Changes:</ins> Will rename to "field_abstract"</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
	 <dd> <ins>MODS XPath: </ins>/mods/abstract</dd>
	<dd> <ins>RDF XPath: </ins>/rdf:RDF/rdf:Description/dc:abstract</dd>
	<dd> <ins>Solr field: </ins>
		<ul>	
			<li>mods_abstract_html_displayLabel_ms: mods_abstract_html_displayLabel_ms(string)</li>
			<li>mods_abstract_html_ms: mods_abstract_html_ms(string)</li>
			<li>mods_abstract_ms: mods_abstract_ms(string)</li>
			<li>mods_abstract_abstract_displayLabel_ms: mods_abstract_abstract_displayLabel_ms(string)</li>
			<li>mods_abstract_abstract_ms: mods_abstract_abstract_ms(string)</li>
		</ul>
	</dd>
</dl>
	<p><i>Last Updated: </i>4/16/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.abstract.md">MODS/abstract</a></td>
			<td><a href="rdf.abstract.md">RDF/dcterms:abstract </a></td>
		</table>
</dl>
</body>
</html>