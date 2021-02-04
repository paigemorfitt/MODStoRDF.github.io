<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th>IMI Columns</th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="#">RDF Fields</a></th>
  </tr>
</table>



<h1>IMI/date_issued</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Issue date of the newspaper</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Public-facing name:</font></ins>Publication Date</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>DateFormattingGuidelinesARMINDA</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>EDTF</dd>
  <dd><ins><font color="brown">Notes: </font></ins>Possibly required for newspaper module</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins> /mods/originInfo/dateIssued</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/dc:valid</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_originInfo_dateIssued_ms: mods_originInfo_dateIssued_ms(string)</li>
				<li>mods_originInfo_displayLabel_ms: mods_originInfo_displayLabel_ms(string)</li>
				<li>mods_originInfo_keyDate_yes_dateIssued_ms: mods_originInfo_keyDate_yes_dateIssued_ms(string)</li>
			</ul>
		</dd>
	<p><font color="red"><i>Last Updated: </i></font>2/4/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.originInfo_dateIssued.md">MODS/originInfo/dateIssued</a></td>
			<td><a href="rdf.valid.md">RDF/dcterms:valid</a></td>
		</table>
</dl>
</body>
</html>