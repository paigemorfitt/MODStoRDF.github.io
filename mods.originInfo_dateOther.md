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
	<td>Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource. <a href="https://www.loc.gov/standards/mods/userguide/origininfo.html"> (resource)</a><</td>
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
<dl>
	<dt><b>Related Fields</b></dt>
		<dd>| <a href="field_date_display.md">field_date_display</a> | <a href="DrupalFields.md">Drupal Field</a> | <a href="rdf.rdau.p60527.md">rdau:P60527</a> | </dd>
		<dd>| <a href="date.encoded.md">field_edtf_date_created</a> | <a href="DrupalFields.md">Drupal Field</a> |<a href="rdf.dcterms.created.md">RDF/dcterms:created</a> | </dd>
		<dd>| <a href="field_graduation_year.md">field_graduation_year</a> | <a href="DrupalFields.md">Drupal Field</a> |<a href="rdf.rdau.p60514.md">RDF/rdau:p60514</a> | </dd>
</dl>
<p><i>Last Updated: </i>09/22/2021</p>
</body>
</html>

