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
<h1>IMI/date_display</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use : </font></ins> Date of creation or publication of original object in human readable format for public viewing</dd>
  <dd><ins><font color="brown">Obligation : </font></ins>  Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable: </font></ins> No</dd>
  <dd><ins><font color="brown">Public Field : </font></ins> Yes</dd>
  <dd><ins><font color="brown">Front-end name : </font></ins> Date</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>EDTF according to Date Formatting Guidelines ARMINDA<dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>Contains html, accents, and/or special characters</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>former IMI field name: mods_display_date</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
	<dd> <ins><font color="brown">MODS XPath : </font></ins> /mods/originInfo/dateOther</dd>
	<dd> <ins><font color="brown">RDF XPath : </font></ins>/rdf:RDF/rdf:Description/dcterms:date</dd>
	<dd> <ins><font color="brown">Solr Field(s)</font></ins>
		<ul>
			<li>mods_originInfo_dateOther_ms: mods_originInfo_dateOther_ms(string)</li>
			<li>mods_originInfo_type_mods_display_date_dateOther_ms: mods_originInfo_type_mods_display_date_dateOther_ms(string)</li>
			<li>mods_originInfo_displayLabel_ms: mods_originInfo_displayLabel_ms(string)</li>
			<li>mods_originInfo_type_date_display_dateOther_ms: mods_originInfo_type_date_display_dateOther_ms(string)</li>
		</ul>
	</dd>
</dl>
<dl>
	<p><font color="red"><i>Last Updated: </i></font>2/3/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.originInfo_dateOther.md">MODS/originInfo/dateOther</a></td>
			<td><a href="rdf.dcterms.date.md">RDF/dcterms:date</a></td>
		</table>
</dl>
</body>
</html>