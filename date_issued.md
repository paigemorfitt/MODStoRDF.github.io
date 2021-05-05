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

<h1>IMI/date_issued</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Issue date of the newspaper</dd>
  <dd>Obligation: Required</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: Yes</dd>
  <dd>Public-facing name: Publication Date</dd>
  <dd>Syntax/Formatting: DateFormattingGuidelinesARMINDA</dd>
  <dd>Recommended Controlled Vocabulary: N/A</dd>
  <dd>Notes: Required for newspaper module</dd>
  <dd>Field Changes: Machine name : field_edtf_date_issued</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> MODS XPath:   /mods/originInfo/dateIssued</dd>
		<dd> RDF XPath/rdf:RDF/rdf: Description/dc:valid</dd>
		<dd> Solr Field(s)
			<ul>
				<li>mods_originInfo_dateIssued_ms: mods_originInfo_dateIssued_ms(string)</li>
				<li>mods_originInfo_displayLabel_ms: mods_originInfo_displayLabel_ms(string)</li>
				<li>mods_originInfo_keyDate_yes_dateIssued_ms: mods_originInfo_keyDate_yes_dateIssued_ms(string)</li>
			</ul>
		</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.originInfo_dateIssued.md">MODS/originInfo/dateIssued</a> | <a href="rdf.dcterms.issued.md">dcterms:issued</a> |
</dl>
<p><i>Last Updated: </i>05/05/2021</p>
</body>
</html>