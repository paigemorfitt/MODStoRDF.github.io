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



<h1>IMI/source</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use: </font></ins>A related resource from which the described resource is derived.</dd>
  <dd><ins><font color="brown">Obligation: </font></ins>Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable: </font></ins>No</dd>
  <dd><ins><font color="brown">Public Field: </font></ins>Yes</dd>
  <dd><ins><font color="brown">Syntax/Formatting: </font></ins>
	<ul>
		<li>Free text</li>
	</ul>
  </dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>Local Standards</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Use when the resource is the result of digitization of non-digital originals. In these cases, sufficient information to identify and find the original resource is provided.</li>
		<li>
For example, for archives: Whitman College and Northwest Archives, Communication Office Records, Box 12, Folder 5.</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>XPath</b></dt>
	  <dd> <ins><font color="brown">MODS XPath </font></ins>
		<li>/mods/relatedItem/part/text</li>
		<li>/mods/relatedItem/@type="host"</li>
	  </dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/dc:source</dd>
<dl>
	<dt>IMI to MODS</dt>
		<dd>&lt;relatedItem type="host" displayLabel="Source"&gt;
&lt;part&gt;&lt;text&gt;{{jsonize(cells["sponsor"].value).replace('null', '')}} 
&lt;/text&gt;&lt;/part&gt;
&lt;/relatedItem&gt;</dd>
</dl>
<dl>
	<dt>IMI to RDF</dt>
		<dd>&lt;dc:source&gt;{{jsonize(cells["source"].value).replace('null', '')}}&lt;/dc:source&gt;</dd>
</dl>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>10/05/2020</p>
</dl>

</body>
</html>