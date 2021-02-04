<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th>IMI Columns</th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="#">RDF Fields</a></th>
  </tr>
</table>



<h1>MODS/originInfo</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.<a href="http://www.loc.gov/standards/mods/userguide/origininfo.md">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> lang; xml:lang; script; transliteration; altRepGroup; displayLabel; eventType</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> place; publisher; dateIssued; dateCreated; dateCaptured; dateValid; dateModified; copyrightDate; dateOther; edition; issuance; frequenc</dd>
</dl>
<h2>MODS/originInfo/place</h2>
<dl>
  <dt><b>Description</b></dt>
    <dd><ins><font color="brown">Definition: </font></ins>Name of a place associated with the event.<a href="www.loc.gov/standards/mods/userguide/origininfo.md#place">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> supplied</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> placeTerm</dd>
</dl>
<h3>MODS/originInfo/place/placeTerm</h3>
<dl>
  <dt><b>Description</b></dt>
    <dd><ins><font color="brown">Definition: </font></ins>Used to express place in a textual or coded form.<a href="www.loc.gov/standards/mods/userguide/origininfo.md#placeterm">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> authority; authorityURI; valueURI; lang; xml:lang; script; transliteration; type</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> N/A</dd>
	<p><font color="red"><i>Last Updated: </i></font>12/15/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="MODS.marccounty.md">[MODS/@authority="marccounty"]</a></td>
			<td><a href="rdf.rdau.p60163.md">rdau:P60163</a></td>
		</table>
</dl>
</body>
</html>