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

<h1>MODS/titleInfo</h1>
<table>
<tr>
	<th>Definition</th>
	<td>A word, phrase, character, or group of characters, normally appearing in a resource, that names it or the work contained in it.<a href="https://www.loc.gov/standards/mods/userguide/titleinfo.html">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>authority; authorityURI; valueURI; lang; xml:lang; script; transliteration;altRepGroup; nameTitleGroup; xlink:href; ID; displayLabel; altFormat; contentType; usage; supplied; type; otherType</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>title; subTitle; partNumber; partName; nonSort</td>
</table>
<table>
<h2>MODS/title</h2>
<table>
<tr>
	<th>Definition</th>
	<td>A word, phrase, character, or group of characters that constitutes the chief title of a resource, i.e., the title normally used when citing the resource.<a href="https://www.loc.gov/standards/mods/userguide/titleinfo.html#title">(resource)</a></td>
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
<table>
	<tr>
		<th>Spreadsheet</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="title.md">title</a></td>
		<td><a href="DrupalFields.md#Title">Title</a></td>
		<td><a href="rdf.dcterms.title.md">dcterms:title</a></td>
	</tr>
</table>
<table>
	<tr>
		<th>Spreadsheet</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="field_alternative_title.md">field_alternative_title</a></td>
		<td><a href="DrupalFields.md#Alternative-Title">Alternative Title</a></td>
		<td><a href="rdf.dcterms.alternative.md">dcterms:alternative</a></td>
	</tr>
</table>
<p><i>Last Updated: </i>06/28/2022</p>
</body>
</html>
