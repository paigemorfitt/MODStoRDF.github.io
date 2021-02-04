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

<h1>IMI/[MODS/Publication Date Start]</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>[start date of range associated with publication of item]</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> No</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>EDTF</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
		<ul>
			<li>Possible requirement for newspaper module.</li>
			<li>Potential required field for newspapers.</li>
			<li>Unsure how content added to.</li>
			<li>MODS: collection-level metadata</li>
			<li>For necessary purposes, in the case that no remediation / reingest of Newspapers happens, the majority of Newspaper fields will be treated as new fields. </li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>This field is not an official IMI field. It will not become an official IMI field until approved by Metadata Working Group</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins> /mods/originInfo/dateIssued</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/reg:P60998</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_originInfo_dateIssued_ms: mods_originInfo_dateIssued_ms(string)</li>
				<li>mods_originInfo_displayLabel_Publication_Date_encoding_w3cdtf_point_end_dateIssued_ms: mods_originInfo_displayLabel_Publication_Date_encoding_w3cdtf_point_end_dateIssued_ms(string)</li>
				<li>mods_originInfo_displayLabel_Publication_Date_encoding_w3cdtf_point_start_dateIssued_ms: mods_originInfo_displayLabel_Publication_Date_encoding_w3cdtf_point_start_dateIssued_ms(string)</li>
				<li>mods_originInfo_displayLabel_ms: mods_originInfo_displayLabel_ms(string)</li>
				<li>mods_originInfo_encoding_w3cdtf_type_publication_date_dateOther_ms: mods_originInfo_encoding_w3cdtf_type_publication_date_dateOther_ms(string)</li>
			</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/18/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.originInfo.dateIssued.md">MODS/originInfo/dateIssued</a></td>
			<td><a href="rdf.p60998.md">RDF/rdau:P60998</a></td>
		</table>
</dl>
</body>
</html>