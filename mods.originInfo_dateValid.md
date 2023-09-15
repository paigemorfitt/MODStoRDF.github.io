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
	<td>Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource. <a href="https://www.loc.gov/standards/mods/userguide/origininfo.md"> (resource)</td>
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
<h2>MODS/originInfo/dateValid</h2>
<table>
<tr>
	<th>Definition</th>
	<td>A date in which the content of a resource is valid.<a href="https://www.loc.gov/standards/mods/userguide/origininfo.md#datevalid">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>encoding; point; keyDate; qualifier; calendar; lang; xml:lang; script; transliteration<</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>N/A</td>
</tr>
</table> 

<h3>Related fields</h3>
<table>
	<tr>
		<th>Spreadsheet</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="field_embargo_date.md">field_embargo_date</a></td> 
		<td><a href="DrupalFields.md#Embargoed-Until">Embargoed Until</a></td>
		<td><a href="rdf.schema.availabilityStarts.md">schema:avalibilityStarts</a></td>
	</tr>
</table>
<p><i>Last Updated: </i></font>09/15/2022</p>
</body>
</html>
