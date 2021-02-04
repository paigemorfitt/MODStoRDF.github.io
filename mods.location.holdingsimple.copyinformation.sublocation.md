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



<h1>MODS/location</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Identifies the institution or repository holding the resource, the physical location of the resource, and/or the electronic location in the form of the digital resource in the form of a URL.<a href="https://www.loc.gov/standards/mods/userguide/location.md#sublocation">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> lang; xml:lang; script; transliteration; altRepGroup; displayLabel</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> physicalLocation; shelfLocator; url; holdingSimple; holdingExternal</dd>
</dl>
<h2>MODS/location/holdingSimple</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Additional specific summary holdings information about the item.<a href="https://www.loc.gov/standards/mods/userguide/location.md#holdingsimple">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> N/A</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> copyInformation</dd>
</dl>
<h3>MODS/location/holdingSimple/copyInformation</h3>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Information about a specific tangible instance of a resource or set comprised of one or more pieces.<a href="https://www.loc.gov/standards/mods/userguide/location.md#copyinformation">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> N/A</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> form; subLocation; shelfLocation; electronicLocator; note; enumerationAndChronology; itemIdentifier</dd>
</dl>
<h4>MODS/location/holdingSimple/copyInformation/subLocation</h4>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Department, division, or section of an institution holding a copy of the resource.<a href="https://www.loc.gov/standards/mods/userguide/location.md#sublocation">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> lang; xml:lang; script; transliteration</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> N/A</dd>
</dl>
 <dd><ins><font color="brown">IMI Columns: </font></ins>
	<ul>
		<li>[MODS/RecordSeriesID]</li>
		</ul>
	</dd>
	<p><font color="red"><i>Last Updated: </i></font>12/15/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="MODS.recordseriesid.md">IMI/[MODS/RecordSeriesID]</a></td>
			<td><a href="rdf.rdau.P60348.md">RDF/rdau:P60348</a></td>
		</table>
</dl>
</body>
</html>