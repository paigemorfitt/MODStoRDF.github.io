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



<h1>MODS/Part</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>Numbering and type of designation of the part in relation to the host/parent.
<a href="http://www.loc.gov/standards/mods/userguide/part.md#detail">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> lang; xml:lang; script; transliteration; altRepGroup; ID; displayLabel; type; order</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> detail; extent; date; text</dd>
</dl>  
<h2>MODS/detail</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>A part of a resouce.<a href="http://www.loc.gov/standards/mods/userguide/part.md">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> type; level</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> number; caption; title</dd>
</dl>
<h3>MODS/number</h3>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>The actual number within the part.
<a href="http://www.loc.gov/standards/mods/userguide/part.md#number">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins> lang; xml:lang; script; transliteration</dd>
  <dd><ins><font color="brown">Subelements: </font></ins>N/A</dd>
  <dd><ins><font color="brown">XPath:</font></ins>
	<ul>
		<li>/mods/part/detail/number</li>
		<li>/mods/part/detail/@type="volume"</li>
		<li>/mods/part/detail/@type="issue"</li>
	</ul>
  </dd>
  <dd><ins><font color="brown">SOLR:</font></ins>
	<ul>
		<li>mods_part_detail_volume_number_ms</li>
		<li>mods_part_detail_issue_number_ms</li>
	</ul>
  </dd>
  <dd><ins><font color="brown">IMI Columns: </font></ins>
	<ul>
		<li>volume</li>
		</ul>
	</dd>
	<p><font color="red"><i>Last Updated: </i></font>11/25/2020</p>
</dl>

</body>
</html>