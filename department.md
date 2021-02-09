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
<h1>department</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins> College division in which the item is categorized</dd>
  <dd><ins><font color="brown">Obligation:</font></ins>  Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Front-end name:</font></ins> Major Department or Program</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font>In house: College catalog official names</dd>
  <dd><ins><font color="brown">Notes: </font></ins>Record information that is listed on Certificate of Approval </dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd></dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins>/mods/name/name/namePart</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/schema:department</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_name_corporate_role_roleTerm_text_ms: mods_name_corporate_role_roleTerm_text_ms(string)</li>
				<li>mods_name_corporate_displayLabel_ms: mods_name_corporate_displayLabel_ms(string)</li>
				<li>mods_name_corporate_major_department_or_program_displayLabel_ms: mods_name_corporate_major_department_or_program_displayLabel_ms(string)</li>
				<li>mods_name_corporate_major_department_or_program_ms: mods_name_corporate_major_department_or_program_ms(string)</li>
				<li>mods_name_corporate_major_department_or_program_namePart_ms: mods_name_corporate_major_department_or_program_namePart_ms(string)</li>
				<li>mods_name_corporate_major_department_or_program_role_roleTerm_ms: mods_name_corporate_major_department_or_program_role_roleTerm_ms(string)</li>
				<li>mods_name_corporate_namePart_ms: mods_name_corporate_namePart_ms(string)</li>
				<li>mods_name_corporate_role_roleTerm_ms: mods_name_corporate_role_roleTerm_ms(string)</li>
			</ul>
		</dd>
</dl>
<p><font color="red"><i>Last Updated: </i></font>2/9/2021</p>
</body>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.name.md">MODS/name/namePart</a></td>
			<td><a href="RDF.schema.department.md">RDF/schema:department</a></td>
		</table>
</dl>
</html>