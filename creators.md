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
<h1>IMI/creators</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>  Identifies the entity/entities primarily responsible for making the resource</dd>
  <dd><ins><font color="brown">Obligation:</font></ins>  Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Front-end name:</font></ins>Creator(s)</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>
	<ul>
		<li>Free text /  RDA 19.2</li>
		<li>Personal name: LastName, FirstName MiddleName (or Initial)</li>
		<li>for multiple authors, separate with pipe with no space trailing</li>
		<li>Add to <a href="field_linked_agent.md">field_linked_agent</a> in form:
			<ul>
				<li>relator:aut:person:Dumas, Alexandre</li> 
				<li>relator:aut:person:Dumas, Alexandre|relator:aut:person:Chadwick, Elizabeth</li>
			</ul>
		</ul>
	</dd>
  </dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins> LCNAF, VIAF, my.whitman, local names</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Provide as much known information as possible (either provided on resource or found elsewhere)</li>
		<li>Separate repeated terms consistently (with semicolon)</li>
		<li>If names are not found in a controlled vocabulary, format personal names Renamed field. - Renamed from authors to creatorsas  Lastname , Firstname according to RDA/DACS</li> 
		<li>If name(s) of creator(s) is not known, see master spreadsheet guidelines for specific details </li>
		<li>No distinguishing between Private and Corporate creators</li>
		<li>Do birthdate or death date unless to disambiguate identical named individuals </li>
		<li>Specific roles are added in parentheses if needed/desired</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>Former IMI field name: authors</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins> /mods/name/@displayLabel="Creator(s)"</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>[dcterms:contributor]/[relators:aut]</dd>
		<dd> <ins><font color="brown">Solr Fields</font></ins>
			<ul>
				<li>mods_name_personal_author_ms: mods_name_personal_author_ms(string)</li>
				<li>mods_name_personal_author_role_roleTerm_text_ms: mods_name_personal_author_role_roleTerm_text_ms(string)</li>
				<li>mods_name_personal_creator(s)_displayForm_ms: mods_name_personal_creator(s)_displayForm_ms(string)</li>
				<li>mods_name_personal_creator(s)_displayLabel_ms: mods_name_personal_creator(s)_displayLabel_ms(string)</li>
				<li>mods_name_personal_creator(s)_ms: mods_name_personal_creator(s)_ms(string)</li>
				<li>mods_name_personal_creator(s)_role_roleTerm_ms: mods_name_personal_creator(s)_role_roleTerm_ms(string)</li>
				<li>mods_name_personal_creator(s)_role_roleTerm_text_ms: mods_name_personal_creator(s)_role_roleTerm_text_ms(string)</li>
				<li>mods_name_personal_displayLabel_ms: mods_name_personal_displayLabel_ms(string)</li>
				<li>mods_name_personal_namePart_ms: mods_name_personal_namePart_ms(string)</li>
				<li>mods_name_personal_role_roleTerm_ms: mods_name_personal_role_roleTerm_ms(string)</li>
			</ul>
	</dd>
</dl>
<dl>
	<p><font color="red"><i>Last Updated: </i></font>2/3/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.name.md">MODS/name/namePart</a></td>
			<td><a href="rdf.relators-aut.md">RDF/dcterms:contributor/ relators:aut OR relators:cre</a></td>
		</table>
</dl>
</body>
</html>