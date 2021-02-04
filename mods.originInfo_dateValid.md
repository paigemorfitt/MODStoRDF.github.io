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
  <dd><ins><font color="brown">Definition: </font></ins>Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource. <a href="https://www.loc.gov/standards/mods/userguide/origininfo.md"> (resource)</a>
</dd>
  <dd><ins><font color="brown">Attributes: </font></ins>lang; xml:lang; script; transliteration; altrepGroup;displayLabel; eventType</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> place; publisher; dateIssued; dateCreated; dateCaptured; dateValid; dateModified; copyrightDate; dateOther; edition; issuance; frequency</dd>
<h2 id="dateValid">MODS/originInfo/dateValid</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition</font></ins>A date in which the content of a resource is valid.<a href="https://www.loc.gov/standards/mods/userguide/origininfo.md#datevalid">(resource)</a></dd>
  <dd><ins><font color="brown">Attributes</font></ins>encoding; point; keyDate; qualifier; calendar; lang; xml:lang; script; transliteration</dd>
  <dd><ins><font color="brown">Subelements:</font></ins>N/A</dd> 
  <dd><ins><font color="brown">IMI Columns</font></ins>
	<ul>
		<li>embargo_date</li>
		</ul>
	</dd>
</dl>
<dl>
	<p><font color="red"><i>Last Updated: </i></font>12/11/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="embargo_date.md">IMI/embargo_date</a></td>
			<td><a href="rdf.availabilityStarts.md">RDF/schema:avalibilityStarts</a></td>
		</table>
</dl>
</body>
</html>