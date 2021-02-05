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

<h1>IMI/publication_date</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Item-level metadata of encoded date of creation or publication of the original object for newspapers </dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Front-end name:</font></ins>Publication Date</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>DateFormattingGuidelinesARMINDA</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Possibly required for module</li>
		<li>Ideally remove</li>
		<li>Do not confuse with Publication Date on Newspaper Collection -Level Metadata</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins> /mods/originInfo/dateOther </dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/dcterms:issued</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_originInfo_dateOther_ms: mods_originInfo_dateOther_ms(string)</li>
				<li>mods_originInfo_displayLabel_ms: mods_originInfo_displayLabel_ms(string)</li>
				<li>mods_originInfo_encoding_w3cdtf_type_publication_date_dateOther_ms: mods_originInfo_encoding_w3cdtf_type_publication_date_dateOther_ms(string)</li>
			</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/11/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.originInfo_dateOther.md">MODS/originInfo/dateOther</a></td>
			<td><a href="rdf.issued.md">RDF/dcterms:issued</a></td>
		</table>
</dl>
</body>
</html>