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

<h1>IMI/advisors</h1>  
<dl>
  <dt><b>Description</b></dt>
  <dd><ins>ARMINDA Use:</ins> A person under whose supervision a student develops and/or presents an acadinsic paper or project, including theses and capstone projects.</dd>
  <dd><ins>Obligation:</ins>  Required, if applicable</dd>
  <dd><ins>Repeatable:</ins> Yes</dd>
  <dd><ins>Public Field:</ins>Yes</dd>
  <dd><ins>Front-end Name:</ins>Advisor</dd>
  <dd><ins>Syntax/Formatting:</ins>
	<ul>
		<li>Free text : RDA 19.2</li>
		<li>Personal name: LastName, FirstName MiddleName (or Initial)</li>
		<li>for multiple advisors, separate with pipe with no space trailing</li>
		<li>Add to <a href="field_linked_agent.md">field_linked_agent</a> in form:
			<ul>
				<li>local:adv:person:Philippe, Louis</li> 
				<li>locas:adv:person:Philippe, Louis|local:adv:person:Hayden, Viola</li>
			</ul>
		</ul>
	</dd>
  <dd><ins>Recommended Controlled Vocabulary:</ins> LCNAF, VIAF, my.whitman, local names list</dd>
  <dd><ins>Notes: </ins>
	<ul>
		<li>Provide as much known information as possible (either provided on resource or found elsewhere)</li>
		<li>Separate repeated terms consistently (with pipe)</li>
		<li>If names are not found in a controlled vocabulary, format personal names as Lastname , Firstname according to RDA/DACS</li>
		<li>If name(s) of creator(s) is not known, see specific Master Sheet guidance.</li>
		<li>Do not use birthdate or death dates unless to disambiguate identically named individuals</li>
		<li>Contains html, accents, and/or special characters</li>
	</ul>
	</dd>
  <dd><i>Field Changes: </i>Previous name: advisor1</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
		 <dd> <ins>MODS XPath </ins>
			<ul>
				<li>/mods/name/namePart</li>
				<li>/mods/name/role/roleTerm</li>
			</ul>
		 </dd>
		<dd> <ins>RDF XPath</ins>/rdf:RDF/rdf:Description/madsrdf:ths</dd>
		<dd> <ins>Solr Field(s)</ins>
			<ul>
				<li>mods_name_personal_advisor(s)_displayLabel_ms</li>
				<li>mods_name_personal_advisor(s)_ms</li>
				<li>mods_name_personal_advisor(s)_namePart_ms</li>
				<li>mods_name_personal_advisor(s)_role_roleTerm_ms</li>
				<li>mods_name_personal_role_roleTerm_ms</li>
				<li>mods_name_personal_thesis_advisor_authority_marcrelator_ms</li>
				<li>mods_name_personal_thesis_advisor_authority_marcrelator_role_roleTerm_text_authority_marcrelator_ms</li>
				<li>mods_name_personal_thesis_advisor_authority_marcrelator_role_roleTerm_text_ms</li>
				<li>mods_name_personal_thesis_advisor_ms</li>
				<li>mods_name_personal_thesis_advisor_role_roleTerm_text_authority_marcrelator_ms</li>
				<li>mods_name_personal_thesis_advisor_role_roleTerm_text_ms</li>
			</ul>
		</dd>
</dl>
	<p><i>Last Updated: </i>4/23/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.name.md">MODS/name/namePart</a></td>
			<td><a href="rdf.field_linked_agent.md">field_linked_agent / local:adv</a></td>
			<td><a href="workbench_field_linked_agent.md">Machine Name/field_linked_agent</a></td>
		</table>
</dl>
</body>
</html>