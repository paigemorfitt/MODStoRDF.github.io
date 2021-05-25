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
  <dd>Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource. <a href="https://www.loc.gov/standards/mods/userguide/origininfo.md"> (resource)</a>
</dd>
  <dd>Attributes: lang; xml:lang; script; transliteration; altrepGroup;displayLabel; eventType</dd>
  <dd>Subelements:  place; publisher; dateIssued; dateCreated; dateCaptured; dateValid; dateModified; copyrightDate; dateOther; edition; issuance; frequency</dd>
<h2 id="dateValid">MODS/originInfo/dateValid</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd>DefinitionA date in which the content of a resource is valid.<a href="https://www.loc.gov/standards/mods/userguide/origininfo.md#datevalid">(resource)</a></dd>
  <dd>Attributesencoding; point; keyDate; qualifier; calendar; lang; xml:lang; script; transliteration</dd>
  <dd>Subelements:N/A</dd> 
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="embargo_date.md">IMI/embargo_date</a></td>
			<td><a href="rdf.schema.availabilityStarts.md">RDF/schema:avalibilityStarts</a></td>
		</table>
</dl>
<p><i>Last Updated: </i></font>05/25/2021</p>
</body>
</html>