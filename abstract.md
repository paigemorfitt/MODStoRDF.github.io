git branch -m IMI <BRANCH>
git fetch origin
git branch -u origin/<BRANCH> <BRANCH>
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
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>A summary of the resource, primarily used with scholarship objects</dd>
  <dd><ins><font color="brown">Obligation: </font></ins> Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable: </font></ins>No</dd>
  <dd><ins><font color="brown">Public Field: </font></ins>Yes</dd>
  <dd><ins><font color="brown">Public-facing name </font></ins>Abstract</dd>
  <dd><ins><font color="brown">Syntax/Formatting: </font></ins>Free-text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary: </font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Use complete sentences</li>
		<li>Some contents moved to IMI/description</li>
		<li>Contains html, accents, and/or special characters</li>
	</ul>
	</dd>
  <dd><font><ins>Former field name:</ins> </font>N/A</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
	 <dd> <ins><font color="brown">MODS XPath: </font></ins>/mods/abstract</dd>
	<dd> <ins><font color="brown">RDF XPath: </font></ins>/rdf:RDF/rdf:Description/dc:abstract</dd>
	<dd> <ins><font color="brown">Solr field: </font></ins>
		<ul>	
			<li>mods_abstract_html_ms</li>
		</ul>
	</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>1/21/2021</p>
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