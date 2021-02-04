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
  <dd><ins><font color="brown">Definition: </font></ins>Information that identifies other resources related to the one being described.<a href="http://www.loc.gov/standards/mods/userguide/relateditem.md">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> xlink:href; ID; displayLabel; type; otherType; otherTypeAuth; otherTypeAuthURI; otherTypeURI</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> titleInfo; name; typeOfResource; genre; originInfo; language; physicalDescription; abstract; tableOfContents; targetAudience; note; subject; classification; relatedItem; identifiers; location; accessCondition; part; extension; recordInfo</dd>
</dl>
<h2>MODS/relatedItem/originInfo</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.<a href="http://www.loc.gov/standards/mods/userguide/origininfo.md">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> lang; xml:lang; script; transliteration; altRepGroup; dislayLabel; eventType</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> place; publisher; dateIssued; dateCreated; dateCaptured; dateValid; dateModified; copyrightDate; dateOther; edition; issuance; frequency</dd>
</dl>
<h3>MODS/relatedItem/originInfo/issuance</h3>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>A term that designates how the resource is issued.<a href="http://www.loc.gov/standards/mods/userguide/origininfo.md#issuance">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> N/A</dd>
  <dd><ins><font color="brown">Subelements: </font></ins>N/A</dd>
  <dd><ins><font color="brown">Comments: </font></ins>may use one of the following vallows: monograph, single unit, multipart monograph, continuing, serial, integrating resource</dd>
</dl>
<dl>
<p><font color="red"><i>Last Updated: </i></font>12/15/2020</p>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="MODS.succeedingIssuance.md">IMI/[MODS/relatedItem/originInfo/issuance]</a></td>
			<td><a href="rdf.rdau.p60051.md">RDF/rdau:P60051</a></td>
		</table>
</dl>
</body>
</html>