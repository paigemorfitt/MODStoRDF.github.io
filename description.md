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
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>An account of the resource, primarily used for archival objects</dd>
  <dd><ins><font color="brown">Obligation: </font></ins> Required</dd>
  <dd><ins><font color="brown">Repeatable: </font></ins>No</dd>
  <dd><ins><font color="brown">Public Field: </font></ins>Yes</dd>
  <dd><ins><font color="brown">Syntax/Formatting: </font></ins>
	<ul>
		<li>Free-text</li>
	</ul>
  </dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary: </font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Use complete sentences</li>
		<li>Some contents moved to IMI/abstract</li>
		<li>contains html</li>
	</ul>
	</dd>
  <dd><font><ins>Field Changes:</ins> </font>N/A</dd>
</dl>
<dl>
    <dt><b>XPath</b></dt>
	  <dd> <ins><font color="brown">MODS XPath: </font></ins>
		<li>/mods/abstract</li>
		<li>/mods/abstract/@displayLabel="Description"</li>
	  </dd>
		<dd> <ins><font color="brown">RDF XPath: </font></ins>
		<li>/rdf:RDF/rdf:Description/dc:description</li>
		</dd>
</dl>
<dl>
	<dt>IMI to MODS</dt>
		<dd>&lt;abstract displayLabel="Description" type="html"&gt;	{{jsonize(cells["description"].value).replace('null', '')}}&lt;/abstract&gt;</dd>
</dl>
<dl>
	<dt>IMI to RDF</dt>
		<dd>&lt;dc:abstract&gt;{{jsonize(cells["description"].value).replace('null', '')}}	&lt;/dc:abstract&gt;</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>11/24/2020</p>
</dl>
</body>
</html>