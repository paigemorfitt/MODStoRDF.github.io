<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th>IMI Columns</th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="RDF.md">RDF Fields</a></th>
  </tr>
</table>



<h1>MODS/subject</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>A term or phrase representing the primary topic(s) on which a work is focused <a href="https://www.loc.gov/standards/mods/userguide/subject.md">(reference)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins>authority; authorityURI; valueURI; lang; xml:lang; scrip; transliteration; altRepGroup; xlink:href; ID; displayLabel; usage</dd>
  <dd><ins><font color="brown">Subelements: </font></ins>topic; geographic; temporal; titleInfo; name; genre; hierarchicalGeographic; cartographic; geographicCode; occupation</dd>
<h2>MODS/topic</h2>
<dl>
  <dt><b>Description</b></dt>
 <dd><ins><font color="brown">Definition: </font></ins>Used as the tag for any topical subjects that are not appropriate in the :geographic:, :temporal:, :titleInfo:, :name:, :genre:, :hierarchicalGeographic:, or :occupation: subelements, or where the type is unknown<a href="https://www.loc.gov/standards/mods/userguide/subject.md#topic">(reference)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins>authority; authorityURI; valueURI; lang; xml:lang; script; transliteration</dd>
  <dd><ins><font color="brown">Subelements: </font></ins>N/A</dd>
  <dd><ins><font color="brown">IMI Columns: </font></ins>
	<ul>
		<li>subject_keywords</li>
		</ul>
	</dd>
	<p><font color="red"><i>Last Updated: </i></font>12/11/2020</p>
</dl>
<dd><b>Related Fields</b></dd>
	<table>
		<tr>
			<td><a href="keywords.md">IMI/subject_keywords</a></td>
			<td><a href="rdf.subject.md">RDF/dcterms:subject</a></td>
		</tr>
	</table>
</dl>
</body>
</html>