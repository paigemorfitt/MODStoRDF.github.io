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
<h2>MODS/originInfo/dateCreated</h2>
<table>
<tr>
	<th>Definition</th>
	<td>The date of creation of the resource.<a href="https://www.loc.gov/standards/mods/userguide/origininfo.html#datecreated">(resource)</a></td>
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
		<td><a href="field_edtf_date.md">field_edtf_date</a</td> 
		<td><a href="DrupalFields.md"Date>Date (EDFT)</a></td>
		<td><a href="rdf.dcterms.date.md">dcterms:date</a></td>
	</tr>
</table>
<p><i>Last Updated: </i>09/23/2021</p>
</body>
</html>

