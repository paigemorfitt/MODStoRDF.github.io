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

<h1>IMI/issue</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Indicate issue number sequential order of volume</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>
	<ul>
		<li>Numeration</li>
	</ul>
  </dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Possibly required for newspaper module</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>XPath</b></dt>
	  <dd> <ins><font color="brown">MODS XPath </font></ins>
		<ul>
			<li>/mods/part/detail</li>
			<li>/mods/part/detail/@type="issue"</li>
		</ul>
	  </dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>
		<ul>
		<li>/rdf:RDF/dc:isPartOf</li>
		</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>11/25/2020</p>
</dl>

</body>
</html>