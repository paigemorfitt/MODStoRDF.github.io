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



<h1>MODS/location</h1>
<table>
<tr>
	<th>Definition</th>
	<td>Identifies the institution or repository holding the resource, the physical location of the resource, and/or the electronic location in the form of the digital resource in the form of a URL.<a href="https://www.loc.gov/standards/mods/userguide/location.html">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>lang; xml:lang; script; transliteration; altRepGroup; displayLabel</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>physicalLocation; shelfLocator; url; holdingSImple; holdingExternal</td>
</tr>
</table>
<h2>MODS/location/url</h2>
<table>
<tr>
	<th>Definition</th>
	<td>Contains the Uniform Resource Location of the resource. <a href="https://www.loc.gov/standards/mods/userguide/location.html#url">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>displayLabel; usage; dateLastAccessioned; note; access</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>N/A</td>
</tr>
</table>
</table>
	<h3>Related fields</h3>
<table>
	<tr>
		<th>Spreadsheet</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="field_url_external.md">field_url_external</a></td>
		<td><a href="DrupalFields.md#view-item">View Item</a></td>
		<td><a href="rdf.schema.url.md">schema:url</a></td>
	</tr>
</table>
<p><i>Last Updated: </i>01/31/2023</p>
</body>
</html>
