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

<h1>MODS/subject</h1>
<table>
<tr>
	<th>Definition</th>
	<td>A term or phrase representing the primary topic(s) on which a work is focused <a href="https://www.loc.gov/standards/mods/userguide/subject.html">(reference)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>authority; authorityURI; valueURI; lang; xml:lang; scrip; transliteration; altRepGroup; xlink:href; ID; displayLabel; usage</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>topic; geographic; temporal; titleInfo; name; genre; hierarchicalGeographic; cartographic; geographicCode; occupation</td>
</tr>
</table>
<h2>MODS/subject/topic</h2>
<table>
<tr>
	<th>Definition</th>
	<td>Used as the tag for any topical subjects that are not appropriate in the :geographic:, :temporal:, :titleInfo:, :name:, :genre:, :hierarchicalGeographic:, or :occupation: subelements, or where the type is unknown<a href="https://www.loc.gov/standards/mods/userguide/subject.html#topic">(reference)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>authority; authorityURI; valueURI; lang; xml:lang; script; transliteration</td>
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
		<td><a href="field_subject.md">field_subject</a> </td> 
		<td><a href="DrupalFields.md#subject">Subject</a></td>
		<td><a href="rdf.dcterms.subject.md">dcterms:subject</a></td>
	</tr>
</table>
<p><i>Last Updated: </i>09/15/2023</p>
</body>
</html>