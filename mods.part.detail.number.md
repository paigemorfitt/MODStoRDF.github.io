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


<h1>MODS/part</h1>
<table>
<tr>
	<th>Definition</th>
	<td>Numbering and type of designation of the part in relation to the host/parent.<a href="http://www.loc.gov/standards/mods/userguide/part.html#detail">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>lang; xml:lang; script; transliteration; altRepGroup; ID; displayLabel; type; order</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>detail; extent; date; text</td>
</tr>
</table>
<h2>MODS/detail</h2>
<table>
<tr>
	<th>Definition</th>
	<td>A part of a resouce.<a href="http://www.loc.gov/standards/mods/userguide/part.html">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>type; level</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>detail; extent; date; text</td>
</tr>
</table>
<h3>MODS/number</h3>
<table>
<tr>
	<th>Definition</th>
	<td>The actual number within the part.<a href="http://www.loc.gov/standards/mods/userguide/part.html#number">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>lang; xml:lang; script; transliteration</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>N/A</td>
</tr>
</table>
	<dt><b>Related Fields</b></dt>
<table>
	<tr>
		<th>Spreadsheet</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="field_issue_num.md">field_issue_num</a></td>
		<td><a href="DrupalFields.md#issue">Issue</a></td>
		<td><a href="rdf.schema.issueNumber.md">schema:issueNumber</a></td>
	</tr>
	<tr>
		<td><a href="field_volume_num.md">field_volume_num</a></td>
		<td><a href="DrupalFields.md#volume">Volume</a></td>
		<td><a href="rdf.schema.volumeNumber.md">schema:volumeNumber</a></td>
	</tr>
</table>
<p><i>Last Updated: </i>10/13/2022</p>
</body>
</html>
