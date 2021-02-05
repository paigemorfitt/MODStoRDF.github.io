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



<h1>IMI/origin</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Provides place names associated with the creation or issuance of a resource. </dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> Yes, if applicable*</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>
	<ul>
		<li>Free text</li>
	</ul>
  </dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins> Library of Congress Subject Headings</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Field applies to Sheehan collection</li>
		<li>*Repeatability only for special cases in Sheehan Gallery Collection</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>XPath</b></dt>
	  <dd> <ins><font color="brown">MODS XPath </font></ins> /mods/part/extent/total</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/reg:p60550</dd>
<dl>
	<dt>IMI to MODS</dt>
		<dd>&lt;originInfo displayLabel=""Origin""&gt;&lt;place&gt;&lt;placeTerm&gt;%value%&lt;/placeTerm&gt;&lt;/place&gt;&lt;/originInfo&gt;"</dd>
</dl>
<dl>
	<dt>IMI to RDF</dt>
		<dd>&lt;reg:p60523&gt;{{jsonize(cells["origin"].value).replace('null', '')}}&lt;/reg:p60523&gt;</dd>
</dl>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>10/24/2020</p>
</dl>

</body>
</html>