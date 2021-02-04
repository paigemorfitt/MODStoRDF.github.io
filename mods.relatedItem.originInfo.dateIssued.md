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
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Information that identifies other resources related to the one being described.<a href="www.loc.gov/standards/mods/userguide/relateditem.md">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> xlink:href; ID; displayLabel; type; otherType; otherTypeAuth; otherTypeAuthURI; otherTypeURI</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> titleInfo, name, typeOfResoruce, genre, originInfo, language, physicalDescription, abstract, tableOfContents, targetAudience, note, subject, classification, relatedItem, identifier, location, accessCondition, part, extension, recordInfo</dd>
</dl>
<h2>MODS/relatedItem/originInfo</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.<a href="http://www.loc.gov/standards/mods/userguide/origininfo.md">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> lang; xml:lang; script; transliteration; altRepGroup; displayLabel; eventType</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> place, publisher, dateIssued, dateCreated, dateCaptured, dateValid, dateModified, copyrightDatse, dateOther, edition, issuance, frequency</dd>
</dl>
<h3>MODS/relatedItem/originInfo/dateIssued</h3>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>The date that the resource was published, released, or issued.<a href="http://www.loc.gov/standards/mods/userguide/origininfo.md#dateissued">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> lang; xml:lang; script; transliteration; encoding; point; keyDate; qualifier; calendar</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> N/A</dd>
</dl>
<dl>
	<p><font color="red"><i>Last Updated: </i></font>12/17/2020</p>
	<dd><b>Related Fields</b></dd>
		<table>
			<tr>
				<td><a href="MODS.dateIssued.Start.md">IMI/[MODS/dateIssued.Start]</a></td>
				<td><a href="rdf.schemal.startdate.md">RDF/schema:startDate</a></td>
			</tr>
			<tr>
				<td><a href="MODS.dateIssued.End.md">IMI/[MODS/dateIssued.End]</a></td>
				<td><a href="rdf.schema.endDate.md">RDF/schema:endDate</a></td>
			</tr>
		</table>
</dl>
</body>
</html>