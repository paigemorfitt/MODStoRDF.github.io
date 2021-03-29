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

<h1>IMI/funding_sources</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Indicates institution or program that helped to fund research project</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Public-facing name:</font></ins>Funding</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free text, Recommended statement structures in local documents.</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>Used for national research grants such as NSF, NIH, NEH, as well as local grants such as Perry or departmental funds</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>Contains content from IMI/grant_information</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd><ins><font color="brown">MODS XPath </font></ins> /mods/name/name/namePart</dd>
		<dd><ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/madsrdf:spn</dd>
		<dd><ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_name_corporate_role_roleTerm_text_ms: mods_name_corporate_role_roleTerm_text_ms(string)</i>
				<li>mods_name_corporate_displayLabel_ms: mods_name_corporate_displayLabel_ms(string)</i>
				<li>mods_name_corporate_namePart_ms: mods_name_corporate_namePart_ms(string)</i>
				<li>mods_name_corporate_research_funding_source_or_ocs_program_displayLabel_ms: mods_name_corporate_research_funding_source_or_ocs_program_displayLabel_ms(string)</i>
				<li>mods_name_corporate_research_funding_source_or_ocs_program_ms: mods_name_corporate_research_funding_source_or_ocs_program_ms(string)</i>
				<li>mods_name_corporate_research_funding_source_or_ocs_program_namePart_ms: mods_name_corporate_research_funding_source_or_ocs_program_namePart_ms(string)</i>
				<li>mods_name_corporate_research_funding_source_or_ocs_program_role_roleTerm_ms: mods_name_corporate_research_funding_source_or_ocs_program_role_roleTerm_ms(string)</i>
				<li>mods_name_corporate_role_roleTerm_ms: mods_name_corporate_role_roleTerm_ms(string)</i>
			</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>3/29/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
				<td><a href="mods.name.md">MODS/name/namePart</a></td>
				<td><a href="rdf.p60451.md">RDF/rdau:P60451</a></td>
		</table>
</dl>
</body>
</html>