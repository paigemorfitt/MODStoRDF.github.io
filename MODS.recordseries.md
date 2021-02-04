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

<h1>IMI/[MODS/RecordSeries]</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>the original collection that a resource belonged to</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Front-facing Name:</font></ins> Record Series</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>Local Standards</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Potential required field for newspapers</li>
		<li>Parallel field to IMI/record_series</li>
		<li>For necessary purposes, in the case that no remediation / reingest of Newspapers happens, the majority of Newspaper fields will be treated as new fields.</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>This field is not an official IMI field. It will not become an official IMI field until approved by Metadata Working Group</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins> /mods/relatedItem/part/text</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/reg:p60101</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_relatedItem__displayLabel_ms: mods_relatedItem__displayLabel_ms(string)</li>
				<li>mods_relatedItem__part_text_ms: mods_relatedItem__part_text_ms(string)</li>
				<li>mods_relatedItem_displayLabel_ms: mods_relatedItem_displayLabel_ms(string)</li>
				<li>mods_relatedItem_host_displayLabel_ms: mods_relatedItem_host_displayLabel_ms(string)</li>
				<li>mods_relatedItem_host_part_text_ms: mods_relatedItem_host_part_text_ms(string)</li>
			</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/14/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.relatedItem.part.text.md">MODS/relatedItem/part/text</a></td>
			<td><a href="rdf.rdau.p60101.md">RDF/rdau:P60101</a></td>
		</table>
</dl>
</body>
</html>