<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th><a href="IMI.md">IMI Column</a></th>
    <th><a href="MODS.md">MODS Field</a></th>
    <th><a href="RDF.md">RDF Field</a></th>
  </tr>
</table>



<h1>IMI/coverage_spatial</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Geographic subject headings</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Recommended, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Front-end name:</font></ins>Coverage</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free-text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>LCSH, GNIS, Getty Geographic Names, MARC GAC, local geographic names list </dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>In tandem with IMI/keywords</li>
		<li>Revisit when know more about islandora 8 entities/taxonomies work / when have more guidance</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
	  <dd> <ins><font color="brown">MODS XPath </font></ins> /mods/subject/geographic</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/dc:spatial</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_subject_displayLabel_ms: mods_subject_displayLabel_ms(string)</li>
				<li>mods_subject_geographic_ms: mods_subject_geographic_ms(string)</li>
			</ul>
		</dd>
</dl>
<dl>
	<p><font color="red"><i>Last Updated: </i></font>2/1/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.subject_geographic.md">MODS/subject/geographic</a></td>
			<td><a href="rdf.spatial.md">RDF/dcterms:spatial</a></td>
		</table>
</dl>
</body>
</html>