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
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.<a href="http://www.loc.gov/standards/mods/userguide/origininfo.md">(resource)</a></dd>
  <dd>Attributes:  lang; xml:lang; script; transliteration; altRepGroup; displayLabel; eventType</dd>
  <dd>Subelements:  place; publisher; dateIssued; dateCreated; dateCaptured; dateValid; dateModified; copyrightDate; dateOther; edition; issuance; frequenc</dd>
</dl>
<h2>MODS/originInfo/place</h2>
<dl>
  <dt><b>Description</b></dt>
    <dd>Definition: Name of a place associated with the event.<a href="www.loc.gov/standards/mods/userguide/origininfo.md#place">(resource)</a></dd>
  <dd>Attributes:  supplied</dd>
  <dd>Subelements:  placeTerm</dd>
</dl>
<h3>MODS/originInfo/place/placeTerm</h3>
<dl>
  <dt><b>Description</b></dt>
    <dd>Definition: Used to express place in a textual or coded form.<a href="www.loc.gov/standards/mods/userguide/origininfo.md#placeterm">(resource)</a></dd>
  <dd>Attributes:  authority; authorityURI; valueURI; lang; xml:lang; script; transliteration; type</dd>
  <dd>Subelements:  N/A</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="origin.md">IMI/origin</a> | <a href="rdf.rdau.p60523.md">RDF/rdau:p60523</a> |
</dl>
<p><i>Last Updated: </i>05/25/2021</p>
</body>
</html>