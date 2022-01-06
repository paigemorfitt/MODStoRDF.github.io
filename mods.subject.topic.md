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

<dd><b>Related Fields</b></dd>
	| <a href="field_subject.md">field_subject</a> | 
	<a href="DrupalFields.md#subject">Drupal Field</a> | 
	<a href="rdf.dcterms.subject.md">RDF/dcterms:subject</a> |
<p><i>Last Updated: </i>01/06/2022</p>
</body>
</html>