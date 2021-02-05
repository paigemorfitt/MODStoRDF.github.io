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

<h1>title</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins> Name given to the resource or supplied title if one is absent</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free text / ISBN Capitalization Standard*</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Transcribe the title as accurately as possible</li>
		<li>Avoid unnecessary punctuation (brackets, periods, quotations, etc)</li>
		<li>*Non-english titles conventions may vary</li>
		<li>If no title provided, provide content of item [see master spreadsheet guidelines for specific details]</li>
		<li>Contains HTML, and accents</li>
	</ul>
  </dd>
  <dd><font color="blue"><i>Field Changes: </i></font> N/A </dd>
  </dt>
</dl>
<dl>
    <dt><b>XPath</b></dt>
	  <dd> <ins><font color="brown">MODS XPath </font></ins> /mods/titleInfo/title</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/dc:title</dd>
</dl>
<dl>
	<dt>IMI to MODS</dt>
		<dd>&lt;titleInfo&gt;&lt;title&gt;{{jsonize(cells["title"].value).replace('null', '')}}&lt;/title&gt;&lt;/titleInfo&gt;</dd>
</dl>
<dl>
	<dt>IMI to RDF</dt>
		<dd>&lt;dc:title&gt;{{jsonize(cells["title"].value).replace('null', '')}}&lt;/dc:title&gt;</dd>
</dl>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>11/25/2020</p>
</dl>
</body>
</html>