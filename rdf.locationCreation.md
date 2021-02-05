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



<h1>schema:locationCreated</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>The location where the CreativeWork was created, which may not be the same as the location depicted in the CreativeWork.<a href="https://schema.org/locationCreated">(reference)</a></dd>
  <dd><ins><font color="brown">Comment: </font></ins>N/A</dd>
  <dd><ins><font color="brown">Label: </font></ins> N/A</dd>
  <dd><ins><font color="brown">Domain: </font></ins>CreativeWork</dd>
  <dd><ins><font color="brown">Range: </font></ins> Place</dd>
  <dd><ins><font color="brown">XPath:</font></ins>
	<ul>
		<li>/mods/originInfo/place/placeTerm</li>
		<li>/mods/originInfo/@displayLabel="City"</li>
	</ul>
  </dd>
  <dd><ins><font color="brown">IMI Columns: </font></ins>
	<ul>
		<li>N/A*</li>
		</ul>
	</dd>
	<p><font color="red"><i>Last Updated: </i></font>10/09/2020</p>
	<p>*Collection that utilized this does not have an IMI for this field. Field is generated in TWIG template</p>
</dl>

</body>
</html>