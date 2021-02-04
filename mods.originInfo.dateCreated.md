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
  <dd><ins><font color="brown">Definition: </font></ins>Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource. <a href="https://www.loc.gov/standards/mods/userguide/origininfo.md"> (resource)</a></dd>
  <dd><ins><font color="brown">Attributes: </font></ins>lang; xml:lang; script; transliteration; altrepGroup;displayLabel; eventType</dd>
  <dd><ins><font color="brown">Subelements: </font></ins> place; publisher; dateIssued; dateCreated; dateCaptured; dateValid; dateModified; copyrightDate; dateOther; edition; issuance; frequency</dd>
</dl>
<h2 id="dateOther">MODS/originInfo/dateCreated</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition</font></ins>The date of creation of the resource.<a href="https://www.loc.gov/standards/mods/userguide/origininfo.md#datecreated">(resource)</a>
</dd>
  <dd><ins><font color="brown">Attributes</font></ins>encoding; point; keyDate; qualifier; lang; xml:lang; script; transliteration</dd>
  <dd><ins><font color="brown">Subelements:</font></ins>N/A</dd>
</dl>
<dl>
	<p><font color="red"><i>Last Updated: </i></font>12/22/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="imi.date.sort.md">IMI/date_sort</a></td>
			<td><a href="imi.mods_date_created_keydate.md">IMI/[MODS/mods_date_created_keydate]</a></td>
			<td><a href="rdf.dcterms.created.md">RDF/dcterms:created</a></td>
		</table>
</dl>
</body>
</html>