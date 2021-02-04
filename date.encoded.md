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
<h1>IMI/date_encoded</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins> Encoded date of creation or publication of the original object with qualifiers and date ranges when applicable</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> No</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>EDTF according to DateFormattingGuidelinesARMINDA </dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>Currently this is maintained in order to have an encoded date that is as granular as possible within edtf</dd>
  <dd><font color="blue"><i>Field Changes: </i></font> Previous name:  oai_harvester_date</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins>  /mods/originInfo/dateOther</dd>
		<dd> <ins><font color="brown">RDF XPath: </font></ins>/rdf:RDF/rdf:Description/reg:P60527</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_originInfo_dateOther_ms: mods_originInfo_dateOther_ms(string)</li>
				<li>mods_originInfo_encoding_edtf_type_oai_harvester_date_dateOther_ms: mods_originInfo_encoding_edtf_type_oai_harvester_date_dateOther_ms(string)</li>
				<li>mods_originInfo_displayLabel_ms: mods_originInfo_displayLabel_ms(string)</li>
			</ul>
		</dd>
</dl>
<p><font color="red"><i>Last Updated: </i></font>12/3/2021</p>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="imi.mods_oai_harvester_date.md">IMI/[MODS/oai_harvester_date]</a></td>
			<td><a href="mods.originInfo_dateOther.md">MODS/originInfo/dateOther</a></td>
			<td><a href="rdf.rdau.p60527.md">RDF/rdau:P60527</a></td>
		</table>
</dl>
</body>
</html>