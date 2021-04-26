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
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: A summary of the resource, primarily used with scholarship objects</dd>
  <dd>Obligation: Required, if applicable</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field:Yes</dd>
  <dd>Public-facing name: Abstract</dd>
  <dd>Syntax/Formatting:free-text
  </dd>
  <dd>Recommended Controlled Vocabulary:N/A</dd>
  <dd>Notes: 
	<ul>
		<li>Use complete sentences<li>
		<li>Some content moved to IMI/description<li>
		<li>Contains html, accents, and/or special characters<li>
	</ul>
	</dd>
  <dd>Field Changes: will be renamed to field_abstract </dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins>MODS XPath: </ins>/mods/abstract</dd>
		<dd> <ins>RDF XPath: </ins>/rdf:RDF/rdf:Description/dc:abstract</dd>
		<dd> <ins>Solr field: </ins>
			<ul>	
				<li>mods_abstract_html_displayLabel_ms</li>
				<li>mods_abstract_html_ms</li>
				<li>mods_abstract_ms</li>
				<li>mods_abstract_abstract_displayLabel_ms</li>
				<li>mods_abstract_abstract_ms</li>
			</ul>
		</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		|<a href="mods.abstract.md">MODS/abstract</a> |<a href="rdf.abstract.md">RDF/dcterms:abstract </a>|
</dl>
<p><i>Last Updated: </i>[here]</p>
</body>
</html>