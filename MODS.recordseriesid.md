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

<h1>[MODS/RecordSeriesID]</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>identification number of item to the original collection a resource belonged to </dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Front-end name:</font></ins>Record Series ID</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>Local Standards</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Potential required field for newspapers</li>
		<li>Parellel field to IMI/series_id</li>
		<li>For necessary purposes, in the case that no remediation / reingest of Newspapers happens, the majority of Newspaper fields will be treated as new fields. </li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>This field is not an official IMI field. It will not become an official IMI field until approved by Metadata Working Group</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins> /mods/location/holdingSimple/copyInformation/subLocation </dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/reg:P60348</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_location_displayLabel_ms: mods_location_displayLabel_ms(string)</li>
				<li>mods_location_holdingSimple_copyInformation_subLocation_ms: mods_location_holdingSimple_copyInformation_subLocation_ms(string)</li>
			</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/15/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.location.holdingsimple.copyinformation.sublocation.md">MODS/location/holdingSimple/copyInformation/subLocation</a></td>
			<td><a href="rdf.rdau.P60348.md">RDF/rdau:P60348</a></td>
		</table>
</dl>
</body>
</html>