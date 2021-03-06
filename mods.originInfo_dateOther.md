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
  <dd>Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource. <a href="https://www.loc.gov/standards/mods/userguide/origininfo.html"> (resource)</a></dd>
  <dd>Attributes: lang; xml:lang; script; transliteration; altrepGroup;displayLabel; eventType</dd>
  <dd>Subelements:  place; publisher; dateIssued; dateCreated; dateCaptured; dateValid; dateModified; copyrightDate; dateOther; edition; issuance; frequency</dd>
</dl>

<h2>MODS/originInfo/dateOther</h2>
<dl>
  <dd>Definition: A date that does not fall into another category but is important to record. <a href="https://www.loc.gov/standards/mods/userguide/origininfo.html#dateother">(resource)</a></dd>
  <dd>Attributesencoding; point; keyDate; qualifier; lang; xml:lang; script; transliteration</dd>
  <dd>Subelements:N/A</dd>
</dl>

<dl>
	<dt><b>Related Fields</b></dt>
		<dd>| <a href="date.display.md">IMI/date_display</a> | <a href="rdf.rdau.p60527.md">rdau:P60527</a> | </dd>
		<dd>| <a href="date.encoded.md">IMI/date_encoded</a> | <a href="rdf.dcterms.created.md">RDF/dcterms:created</a> | </dd>
		<dd>| <a href="graduation_year.md">IMI/year_graduation</a> | <a href="rdf.rdau.p60514.md">RDF/rdau:p60514</a> | </dd>
</dl>
<p><i>Last Updated: </i>05/27/2021</p>
</body>
</html>