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
	<td>Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.<a href="https://www.loc.gov/standards/mods/userguide/origininfo.html">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>lang; xml:lang; script; transliteration; altRepGroup; displayLabel; eventType</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>place; publisher; dateIssued; dateCreated; dateCaptured; dateValid; dateModified; copyrightDate; dateOther; edition; issuance; frequency</td>
</tr>
</table>
<h2>MODS/originInfo/place</h2>
<table>
<tr>
	<th>Definition</th>
	<td>name of a place associated with the event <a href="https://www.loc.gov/standards/mods/userguide/origininfo.html#place">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>supplied</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>placeTerm</td>
</tr>
</table>
<h3>MODS/originInfo/place/placeTerm</h3>
<table>
<tr>
	<th>Definition</th>
	<td>used to express place in a textual or coded form <a href="https://www.loc.gov/standards/mods/userguide/origininfo.html#placeterm">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>authority; authorityURI; valueURI; lang; xml:lang; script; transliteration; type</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>N/A</td>
</tr>
</table>

<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="field_origin.md">field_origin</a> |
		<a href-"DrupalFields.md">Drupal Field</a> | 
		<a href="rdf.rdau.p60523.md">RDF/rdau:p60523</a> |
</dl>
<p><i>Last Updated: </i>11/05/2021</p>
</body>
</html>