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

  
<h1>MODS/relatedItem</h1>
<table>
<tr>
	<th>Definition</th>
	<td>Information that identifies other resources related to the one being described <a href="http://www.loc.gov/standards/mods/userguide/relateditem.html">(resource)</a></td>
</tr>
<tr>
	<th>Comment</th>
	<td>A wrapper element that contains other MODS elemetns</td>
</tr>
<tr>
	<th>Attributes</th>
	<td>xlink:href; ID; displayLabel; type; otherType; otherTypeAUth; otherTypeAuthURI; otherTypeURI</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>Subelements: titleInfo; name; typeOfResource; genre; originInfo; language; physicalDescription; abstract; tableOfContents; targetAudience; note; subject; classification; relatedItem; identifier; location; accessCondition; part; extension; recordInfo</td>
</tr>
</table>
<h2>MODS/relatedItem/part</h2>
<table>
<tr>
	<th>Definition</th>
	<td>A part of a resouce.<a href="http://www.loc.gov/standards/mods/userguide/part.html">(resource)</a></td>
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
<h1>MODS/relatedItem/part/text</h1>
<table>
<tr>
	<th>Definition</th>
	<td>Unparsed information in textual form about the part. <a href="http://www.loc.gov/standards/mods/userguide/part.html#text">(resource)</a></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>lang; xml:lang; script; transliteration; displayLabel; type</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>N/A</td>
</tr>
</table>

<dl>
	<dd><b>Related Fields</b></dd>
		| <a href="field_source.md">field_source</a> 
		| <a href="DrupalFields.md#Source">Drupal</a>
		| <a href="rdf.dcterms.source.md">RDF/dcterms:source</a> |
</dl>
<p><i>Last Updated: </i>01/05/2022</p>
</body>
</html>