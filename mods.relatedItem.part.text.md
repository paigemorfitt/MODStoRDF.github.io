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
  <dd>Definition: Information that identifies other resources related to the one being described <a href="http://www.loc.gov/standards/mods/userguide/relateditem.md">(resource)</a></dd>
  <dd><i>Comment: </i>A wrapper element that contains other MODS elemetns</dd>
  <dd>Attributes: xlink:href; ID; displayLabel; type; otherType; otherTypeAUth; otherTypeAuthURI; otherTypeURI</dd>
  <dd>Subelements: titleInfo; name; typeOfResource; genre; originInfo; language; physicalDescription; abstract; tableOfContents; targetAudience; note; subject; classification; relatedItem; identifier; location; accessCondition; part; extension; recordInfo</dd>
 </dl>
 <dl>
  <h2>MODS/relatedItem/part</h2>
  <dt><b>Description</b></dt>
  <dd>Definition: A part of a resouce.<a href="http://www.loc.gov/standards/mods/userguide/part.md">(resource)</a></dd>
  <dd>Attributes: lang; xml:lang; script; transliteration; altRepGroup; ID; displayLabel; type; order</dd>
  <dd>Subelements: detail; extent; date; text</dd>
</dl>
<dl>
<h3>MODS/relatedItem/part/text</h3>
  <dt><b>Description</b></dt>
  <dd>Definition: Unparsed information in textual form about the part. <a href="http://www.loc.gov/standards/mods/userguide/part.md#text">(resource)</a></dd>
  <dd>Attributes: lang; xml:lang; script; transliteration; displayLabel; type</dd>
  <dd>Subelements: N/A</dd>
<dl>
	<dd><b>Related Fields</b></dd>
		| <a href="source.md">IMI/source</a> | <a href="rdf.dc.source.md">RDF/dcterms:source</a> |
</dl>
<p><i>Last Updated: </i>05/25/2021</p>
</body>
</html>