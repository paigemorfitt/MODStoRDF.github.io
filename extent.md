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
<h1>IMI/extent</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Statement of the physical size or duration of the object, such as dimensions, number of items, pages, or running time.</dd>
  <dd><ins><font color="brown">Obligation:</font></ins>  Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Public-facing name:</font></ins>Extent</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  
	<dd><ins><font color="brown">Notes: </font></ins>
		<ul>
			<li>This is not applied to digital file sizes or dpi</li>
			<li>Provide both a number/numbers and a designation of the units being measured.</li>
			<li>Example: “1 photograph” rather than just “1.”</li>
			<li>Content from Maxey and Sheehan removed. Moving forward, that field will be required for them to fill out</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>New field. Comprised of IMI/pagecount, IMI/duration, IMI/artifact_number</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins> N/A</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/dc:extent</dd>
		<dd> <ins><font color="brown">MODS XPath </font></ins>
			<ul>
				<li>mods_physicalDescription_extent_ms: mods_physicalDescription_extent_ms(string)</li>
				<li>mods_physicalDescription_displayLabel_ms: mods_physicalDescription_displayLabel_ms(string)</li>
				<li>mods_physicalDescription_ms: mods_physicalDescription_ms(string)</li>
			</ul>
		</dd>
</dl>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>3/16/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.physicalDescription.md">MODS/physicalDescription/extent</a></td>
			<td><a href="rdf.dcterms.extent.md">RDF/dcterms:extent</a></td>
		</table>
</dl>
</body>
</html>