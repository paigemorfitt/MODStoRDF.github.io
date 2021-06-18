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
  <dd>ARMINDA Use: identifies the entity or entities that made contributions to the creation of the resource but whose contributions are secondary to any person or organization specified in the creator(s) field. </dd>
  <dd>Obligation: Required, if applicable</dd>
  <dd>Repeatable: Yes</dd>
  <dd>Public Field: Yes</dd>
  <dd>Public-facing name: Contributor</dd>
  <dd>Syntax/Formatting:
	<ul>
		<li>Free text / RDA 19.2</li>
		<li>Personal name: LastName, FirstName MiddleName (or Initial)</li>
		<li>For multiple authors, separate with pipe  with no space trailing.</li>
		<li>All names prefaced with "realtors:ctb:"</li>
		<li>This field is being added to field_linked_agent for Islandora 8 ingest</li>
	</ul>
  </dd>
  <dd>Recommended Controlled Vocabulary:  LCNAF, VIAF, my.whitman, local names</dd>
  <dd>Notes: 
	<ul>
		<li>Advisor to be handled as a special case of Contributor with its own column name, same rules apply.</li>
		<li>Current policy: only advisor is specific field besides creator(s) and contributor(s) at present. Going forward, if a collection has a contributor (or creator) role that requires its own label in order to be adequately faceted and searched, the metadata committee will consult on adding an additional field or fields for these roles</li>
		<li>Provide as much known information as possible (either provided on resource or found elsewhere)</li>
		<li>Separate repeated terms consistently (with pipes)</li>
		<li>If names are not found in a controlled vocabulary, format personal names as Lastname , Firstname according to RDA/DACS</li>
		<li>If name(s) of creator(s) is not known, see specific Master Sheet guidance.</li>
		<li>Distinguishing between Private and Corporate creators is found in prefacing by either "relators:ctb:person" or "relators:ctb:corporate_body"</li>
		<li>Do birthdate or death date unless to disambiguate identical named individuals</li>
		<li>Specific roles are added in parentheses if needed/desired</li>
		<li>Contains html, accents, and/or special characters</li>
		</ul>
	</dd>
  <dd>Field Changes: 
		<ul>
			<li>Content will be moved to field_linked_agent</li>
			<li>Being removed. Non-mapped fields are being removed.</li>
		</ul>
	</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.name.md">MODS/name/namePart</a> | <a href="rdf.field_linked_agent.md">RDF/relators:ctb</a> |
</dl>
<p><i>Last Updated: </i>06/16/2021</p>
</body>
</html>