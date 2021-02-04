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



<h1>MODS/relatedItem</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Information that identifies other resources related to the one being described <a href="http://www.loc.gov/standards/mods/userguide/relateditem.md">(resource)</a></dd>
  <dd><i>Comment: </i>A wrapper element that contains other MODS elemetns</dd>
  <dd><ins><font color="brown">Attributes: </font></ins>xlink:href; ID; displayLabel; type; otherType; otherTypeAUth; otherTypeAuthURI; otherTypeURI</dd>
  <dd><ins><font color="brown">Subelements: </font></ins>titleInfo; name; typeOfResource; genre; originInfo; language; physicalDescription; abstract; tableOfContents; targetAudience; note; subject; classification; relatedItem; identifier; location; accessCondition; part; extension; recordInfo</dd>
 </dl>
 <dl>
  <h2>MODS/relatedItem/part</h2>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>A part of a resouce.<a href="http://www.loc.gov/standards/mods/userguide/part.md">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins>lang; xml:lang; script; transliteration; altRepGroup; ID; displayLabel; type; order</dd>
  <dd><ins><font color="brown">Subelements: </font></ins>detail; extent; date; text</dd>
</dl>
<dl>
<h3>MODS/relatedItem/part/text</h3>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Unparsed information in textual form about the part. <a href="http://www.loc.gov/standards/mods/userguide/part.md#text">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins>lang; xml:lang; script; transliteration; displayLabel; type</dd>
  <dd><ins><font color="brown">Subelements: </font></ins>N/A</dd>
  <dd><ins><font color="brown">IMI Columns: </font></ins>
		<ul>
			<li>source</li>
			<li>[MODS/RecordSeries]</li>
		</ul>
	</dd>
	<p><font color="red"><i>Last Updated: </i></font>12/14/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<tr>
				<td><a href="source.md">IMI/source</a></td>
				<td><a href="rdf.dc.source.md">RDF/dcterms:source</a></td>
			</tr>
			<tr>
				<td><a href="MODS.recordseries.md">IMI/[MODS/RecordSeries]</a></td>
				<td><a href="rdf.rdau.p60101.md">RDF/rdau:P60101</a></td>
			</tr>
		</table>
</dl>
</body>
</html>