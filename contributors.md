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
<h1>IMI/contributors</h1>  
<dl>
  <dt><b>Description</b></dt>
  <dd><ins>ARMINDA Use:</ins> identifies the entity or entities that made contributions to the creation of the resource but whose contributions are secondary to any person or organization specified in the creator(s) field</dd>
  <dd><ins>Obligation:</ins>  Required, if applicable</dd>
  <dd><ins>Repeatable:</ins> Yes</dd>
  <dd><ins>Public Field:</ins> Yes</dd>
  <dd><ins>Front-end Name: </ins> Contributor(s)</dd>
  <dd><ins>Syntax/Formatting:</ins>
	<ul>
		<li>Free text /  RDA 19.2</li>
		<li>Personal name: LastName, FirstName MiddleName (or Initial)</li>
		<li>For multiple contributors, separate with pipe with no space trailing.</li>
				<li>Add to <a href="field_linked_agent.md">field_linked_agent</a> in form:
			<ul>
				<li>relator:ctb:person: Grisier, Augustin</li> 
				<li>relator:ctb:person:Grisier, Augustin|relator:ctb:corporate_body:Regia Anglorum</li>
			</ul>
		</ul>
	</dd>
	</ul>
</dd>
  <dd><ins>Recommended Controlled Vocabulary:</ins>LCNAF, VIAF, my.whitman, local names</dd>
  
  <dd><ins>Notes: </ins>
	<ul>
		<li>Particular roles to be elaborated in parentheses after the name (copy from creator(s) card)</li>
		<li>Advisor to be handled as a special case of Contributor with its own column name, same rules apply</li>
		<li> Current policy: only advisor is specific field besides creator(s) and contributor(s) at present. Going forward, if a collection has a contributor (or creator) role that requires its own label in order to be adequately faceted and searched, the metadata committee will consult on adding an additional field or fields for these roles</li>
		<li>Provide as much known information as possible (either provided on resource or found elsewhere)</li>
		<li>Separate repeated terms consistently (with semicolon)</li>
		<li>If names are not found in a controlled vocabulary, format personal names as  Lastname , Firstname according to RDA/DACS </li>
		<li>If name(s) of creator(s) is not known, see specific Master Sheet guidance</li>
		<li>No distinguishing between Private and Corporate creators</li>
		<li>Do birthdate or death date unless to disambiguate identical named individuals </li>
		<li>Specific roles are added in parentheses if needed/desired</li>
		</ul>
	</dd>
  <dd><i>Field Changes: </i>former IMI field name : contributor</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
	  <dd> <ins>MODS XPath </ins>/mods/name/namePart</dd>
		<dd> <ins>RDF XPath</ins>/[dcterms:contributor]/[relators:ctb]</dd>
		<dd> <ins>Solr field(s) </ins>
			<ul>
				<li>mods_name_personal_contributor(s)_displayLabel_ms</li>
				<li>mods_name_personal_contributor(s)_namePart_ms</li>
				<li>mods_name_personal_contributor(s)_role_roleTerm_ms</li>
				<li>mods_name_personal_displayLabel_ms</li>
				<li>mods_name_personal_namePart_ms</li>
				<li>mods_name_personal_role_roleTerm_ms</li>
			</ul>
		</dd>
</dl>
<dl>
	<p><i>Last Updated: </i>4/23/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.name.md">MODS/name/namePart</a></td>
			<td><a href="rdf.field_linked_agent.md">RDF/relators:ctb</a></td>
			<td><a href="workbench_field_linked_agent.md">Machine Name/field_linked_agent</a></td>
		</table>
</dl>
</body>
</html>