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

<h1>MODS/originInfo</h1>
<table>
<tr>
	<th>Definition</th>
	<td>Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource. <a href="https://www.loc.gov/standards/mods/userguide/origininfo.html"> (resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>lang; xml:lang; script; transliteration; altrepGroup;displayLabel; eventType</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>place; publisher; dateIssued; dateCreated; dateCaptured; dateValid; dateModified; copyrightDate; dateOther; edition; issuance; frequency</td>
</tr>
</table>
<h2>MODS/originInfo/dateOther</h2>
<table>
<tr>
	<th>Definition</th>
	<td>A date that does not fall into another category but is important to record. <a href="https://www.loc.gov/standards/mods/userguide/origininfo.html#dateother">(resource)</td>
</tr>
<tr>
	<th>Attributes</th>
	<td>encoding; point; keyDate; qualifier; lang; xml:lang; script; transliteration</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>N/A</td>
</tr>
</table>
<table>
	<tr>
		<th>Spreadsheet</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="field_date_display.md">field_date_display</a></td> 
		<td><a href="DrupalFields.md#Date">Date</a></td> 
		<td><a href="rdf.rdau.p60527.md">rdau:P60527</a></td> 
	</tr>
</table>
<table>
	<tr>
		<th>Spreadsheet</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="field_edtf_date_created.md">field_edtf_date_created</a></td> 
		<td><a href="DrupalFields.md#Date-Created-(EDTF)">Date Created (EDTF)</a></td> 
		<td><a href="rdf.dcterms.created.md">RDF/dcterms:created</a></td> 
	</tr>
</table>
<table>
	<tr>
		<th>Spreadsheet</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="field_graduation_year.md">field_graduation_year</a></td> 
		<td><a href="DrupalFields.md#graduation-year">Graduation Year</a></td> 
		<td><a href="rdf.rdau.p60514.md">RDF/rdau:p60514</a></td> 
	</tr>
</table>
<p><i>Last Updated: </i>06/29/2022</p>
</body>
</html>

