<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th><a href="IMI.md">IMI Columns</a></th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="RDF.md">RDF Fields</a></th>
  </tr>>
</table>



<h1>MODS/Part</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: Numbering and type of designation of the part in relation to the host/parent.<a href="http://www.loc.gov/standards/mods/userguide/part.md#detail">(resource)</a></dd>
  <dd>Attributes:  lang; xml:lang; script; transliteration; altRepGroup; ID; displayLabel; type; order</dd>
  <dd>Subelements:  detail; extent; date; text</dd>
</dl>  
<h2>MODS/detail</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: A part of a resouce.<a href="http://www.loc.gov/standards/mods/userguide/part.md">(resource)</a></dd>
  <dd>Attributes:  type; level</dd>
  <dd>Subelements:  number; caption; title</dd>
</dl>
<h3>MODS/number</h3>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: The actual number within the part.
<a href="http://www.loc.gov/standards/mods/userguide/part.md#number">(resource)</a></dd>
  <dd>Attributes:  lang; xml:lang; script; transliteration</dd>
  <dd>Subelements: N/A</dd>
 <dl>
	<dt><b>Related Fields</b></dt>
		 <dd>| <a href="field_issue_num.md">field_issue_num</a> | <a href="rdf.schema.issueNumber.md">RDF/schema:issueNumberf</a> | </dd>
		  <dd>| <a href="volume_num.md">IMI/volume_num</a> | <a href="rdf.schema.volumeNumber.md">RDF/schema:volumeNumber</a> | </dd>

</dl>
<p><i>Last Updated: </i>08/27/2021</p>
</body>
</html>