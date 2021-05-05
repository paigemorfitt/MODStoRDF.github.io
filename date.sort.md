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

<h1>IMI/date_sort</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Encoded date of creation or publication of the original object that strips out qualifiers and date ranges to allow us to sort on date in ARMINDA</dd>
  <dd>Obligation: Required, if applicable. </dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: No</dd>
  <dd>Syntax/Formatting: EDTF according to DateFormattingGuidelinesARMINDA </dd>
  <dd>Recommended Controlled Vocabulary: N/A</dd>
  <dd>Notes: N/A</dd>
  <dd>Field Changes: 
	<ul>
		<li>Previous name mods_date_created_keydate</li>
		<li>Machine name:field_edtf_date</li>
	</ul>
  </dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> MODS XPath /mods/originInfo/dateCreated</dd>
		<dd> RDF XPath/rdf:RDF/rdf:Description/dcterms:created</dd>
		<dd> Solr Field(s)
			<ul>
				<li>  mods_originInfo_dateCreated_ms: mods_originInfo_dateCreated_ms(string)</li>
				<li>  mods_originInfo_displayLabel_ms: mods_originInfo_displayLabel_ms(string)</li>
				<li>  mods_originInfo_encoding_edtf_keyDate_yes_dateCreated_ms: mods_originInfo_encoding_edtf_keyDate_yes_dateCreated_ms(string)</li>
				<li>  mods_originInfo_encoding_w3cdtf_keyDate_yes_dateCreated_ms: mods_originInfo_encoding_w3cdtf_keyDate_yes_dateCreated_ms(string)</li>
				<li>  mods_originInfo_keyDate_yes_dateCreated_ms: mods_originInfo_keyDate_yes_dateCreated_ms(string)</li>
				<li>  mods_originInfo_type_date_created_dateOther_ms: mods_originInfo_type_date_created_dateOther_ms(string)</li>
				<li>  mods_originInfo_encoding_etdf_keyDate_yes_dateCreated_ms: mods_originInfo_encoding_etdf_keyDate_yes_dateCreated_ms(string)</li>
			</ul>
		</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.originInfo.dateCreated.md">MODS/originInfo/dateCreated</a> | <a href="rdf.dcterms.created.md">RDF/dcterms:created</a>|
</dl>
<p><i>Last Updated: </i>05/05/2021</p>
</body>
</html>