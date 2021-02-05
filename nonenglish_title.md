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
<h1>title_alternative</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>An alternative title of the described resource including abbreviations and translations </dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
		<ul>
			<li>An alternative title of the described resource including abbreviations and translations</li>
			<li>Contains HTML, and accents</li>
		</ul>
  </dd>
  <dd><font color="blue"><i>Field Changes: </i></font> Previous name : nonenglish_title</dd>
  </dt>
</dl>
<dl>
    <dt><b>XPath</b></dt>
	  <dd> <ins><font color="brown">MODS XPath </font></ins> /mods/titleInfo/@type="alternative"</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/dc:alternative</dd>
</dl>
<dl>
	<dt>IMI to MODS</dt>
		<dd>&lt;titleInfo type="alternative"&gt;&lt;title lang="eng"&gt;{{jsonize(cells["title_alternative"].value).replace('null', '')}} &lt;/title&gt;&lt;/titleInfo&gt;</dd>
</dl>
<dl>
	<dt>IMI to RDF</dt>
		<dd>&lt;dc:alternative&gt;{{jsonize(cells["title_alternative"].value).replace('null', '')}} &lt;/dc:alternative&gt;</dd>
</dl>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>11/25/2020</p>
</dl>
</body>
</html>