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
<h1>IMI/contributors</h1>  
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins> identifies the entity or entities that made contributions to the creation of the resource but whose contributions are secondary to any person or organization specified in the creator(s) field</dd>
  <dd><ins><font color="brown">Obligation:</font></ins>  Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Front-end Name: </font></ins> Contributor(s)</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>
	<ul>
		<li>Free text /  RDA 19.2</li>
		<li>Personal name: LastName, FirstName MiddleName (or Initial)</li>
		<li>For multiple authors, separate with semicolon with no space trailing.</li>
	</ul>
</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>LCNAF, VIAF, my.whitman, local names</dd>
  
  <dd><ins><font color="brown">Notes: </font></ins>
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
  <dd><font color="blue"><i>Field Changes: </i></font>former IMI field name : contributor</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
	  <dd> <ins><font color="brown">MODS XPath </font></ins>/mods/name/namePart</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/[dcterms:contributor]/[relators:ctb]</dd>
		<dd> <ins><font color="brown">Solr field(s) </font></ins>
			<ul>
				<li>mods_name_personal_contributor(s)_displayLabel_ms: mods_name_personal_contributor(s)_displayLabel_ms(string)</li>
				<li>mods_name_personal_contributor(s)_namePart_ms: mods_name_personal_contributor(s)_namePart_ms(string)</li>
				<li>mods_name_personal_contributor(s)_role_roleTerm_ms: mods_name_personal_contributor(s)_role_roleTerm_ms(string)</li>
				<li>mods_name_personal_displayLabel_ms: mods_name_personal_displayLabel_ms(string)</li>
				<li>mods_name_personal_namePart_ms: mods_name_personal_namePart_ms(string)</li>
				<li>mods_name_personal_role_roleTerm_ms: mods_name_personal_role_roleTerm_ms(string)</li>
			</ul>
		</dd>
</dl>
<dl>
	<p><font color="red"><i>Last Updated: </i></font>2/1/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.name.md">MODS/name/namePart</a></td>
			<td><a href="rdf.relators.ctb.md">RDF/dcterms:contributor/ relators:ctb</a></td>
		</table>
</dl>
</body>
</html>