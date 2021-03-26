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
  <dd><ins><font color="brown">ARMINDA Use:</font></ins> A person under whose supervision a student develops and/or presents an acadinsic paper or project, including theses and capstone projects.</dd>
  <dd><ins><font color="brown">Obligation:</font></ins>  Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Front-end Name:</font></ins>Advisor(s)</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>
	<ul>
		<li>Free text : RDA 19.2</li>
		<li>Personal name: LastName, FirstName MiddleName (or Initial)</li>
		<li>for multiple authors, separate with pipe with no space trailing</li>
		<li>Add to <a href="field_linked_agent.md">field_linked_agent</a> in form:
			<ul>
				<li>relator:ths:person:Dumas, Alexandre</li> 
				<li>relator:ths:person:Dumas, Alexandre|relator:ths:person:Chadwick, Elizabeth</li>
			</ul>
		</ul>
	</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins> LCNAF, VIAF, my.whitman, local names list</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Provide as much known information as possible (either provided on resource or found elsewhere)</li>
		<li>Separate repeated terms consistently (with pipe)</li>
		<li>If names are not found in a controlled vocabulary, format personal names as Lastname , Firstname according to RDA/DACS</li>
		<li>If name(s) of creator(s) is not known, see specific Master Sheet guidance.</li>
		<li>Do not use birthdate or death dates unless to disambiguate identically named individuals</li>
		<li>Specific roles are added in parentheses if needed/desired</li>
		<li>Contains html, accents, and/or special characters</li>
	</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>Previous name: advisor1; content pipped into field_linked_agent</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
		 <dd> <ins><font color="brown">MODS XPath </font></ins>
			<ul>
				<li>/mods/name/namePart</li>
				<li>/mods/name/role/roleTerm</li>
			</ul>
		 </dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/madsrdf:ths</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_name_personal_advisor(s)_displayLabel_ms: mods_name_personal_advisor(s)_displayLabel_ms(string)</li>
				<li>mods_name_personal_advisor(s)_ms: mods_name_personal_advisor(s)_ms(string)</li>
				<li>mods_name_personal_advisor(s)_namePart_ms: mods_name_personal_advisor(s)_namePart_ms(string)</li>
				<li>mods_name_personal_advisor(s)_role_roleTerm_ms: mods_name_personal_advisor(s)_role_roleTerm_ms(string)</li>
				<li>mods_name_personal_role_roleTerm_ms: mods_name_personal_role_roleTerm_ms(string)</li>
				<li>mods_name_personal_thesis_advisor_authority_marcrelator_ms: mods_name_personal_thesis_advisor_authority_marcrelator_ms(string)</li>
				<li>mods_name_personal_thesis_advisor_authority_marcrelator_role_roleTerm_text_authority_marcrelator_ms: mods_name_personal_thesis_advisor_authority_marcrelator_role_roleTerm_text_authority_marcrelator_ms(string)</li>
				<li>mods_name_personal_thesis_advisor_authority_marcrelator_role_roleTerm_text_ms: mods_name_personal_thesis_advisor_authority_marcrelator_role_roleTerm_text_ms(string)</li>
				<li>mods_name_personal_thesis_advisor_ms: mods_name_personal_thesis_advisor_ms(string)</li>
				<li>mods_name_personal_thesis_advisor_role_roleTerm_text_authority_marcrelator_ms: mods_name_personal_thesis_advisor_role_roleTerm_text_authority_marcrelator_ms(string)</li>
				<li>mods_name_personal_thesis_advisor_role_roleTerm_text_ms: mods_name_personal_thesis_advisor_role_roleTerm_text_ms(string)</li>
			</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>3/26/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.name.md">MODS/name/namePart</a></td>
			<td><a href="rdf.relators.ths.md">RDF/dcterms:contributor/relators:ths</a></td>
		</table>
</dl>
</body>
</html>