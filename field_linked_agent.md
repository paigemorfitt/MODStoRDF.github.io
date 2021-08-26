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

<h1>field_linked_agent</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Label of a field instance populated by taxonomy terms from Corporate Body, Family and Person vocabularies</td>
</tr>
<tr>
	<th>Obligation</th>
	<td>Required, if applicable</td>
</tr>
<tr>
	<th>Repeatable</th>
	<td>Yes</td>
</tr>
<tr>
	<th>Public Field</th>
	<td>Yes</td>
</tr>
<tr>
	<th>Public-facing name</th>
	<td>Linked Agent</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Typed relation/Taxonomy</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>Prefixes: Yes ; Terms: LCNAF, VIAF, my.whitman, local names</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Specific Agent roles are indicated with prefixes (Islandora taxonomy pulls from various vocabularies and the metadata needs prefixes to indicate what vocabulary that term goes to/comes from)</li>
			<li>Assigning body (person, family, or corporate body) and Relationship type (Role) must be specified.</li>
			<li>Personal name: LastName, FirstName MiddleName (or Initial)</li>
			<li>For multiple authors, separate with pipe with no space trailing.</li>
			<li>Provide as much known information as possible (either provided on resource or found elsewhere)</li>
			<li>Separate repeated terms consistently (with pipe)</li>
			<li>If names are not found in a controlled vocabulary, format personal names as Lastname , Firstname according to RDA/DACS</li>
			<li>If name(s) of creator(s) is not known, see specific Master Sheet guidance.</li>
			<li>We are NOT using the codes for this field. In lue of an Islandora reboot, codes would change.</li>
			<li>(migration) New terms are added to the taxonomy on ingest, as long as the .yml file says to create new terms. The exception is, you can't create new relators via Workbench, and you can't create new nested terms via Workbench (unless that was recently updated)</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Includes the following fields: IMI/advisor, IMI/creator, IMI/contributor, and IMI/publisher</td>
</tr>
</table>
<details>
		<summary><b>Islandora 8 notes</b></summary>
			<table>
				<tr>
					<th><i>Note</i>
					<th><i>Type of field</i>
					<th><i>Max Length/Repeatability</i>
					<th><i>Type of Item Reference/Vocabulary</i>
				</tr>
				<tr>
					<td>Default field</td>
					<td>Typed Relation</td>
					<td>Unlimited</td>
					<td>Taxonomy Term [corporate body, family, person]</td>
				</tr>
			</table>
</details>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.name.md">MODS/name/namePart</a> | RDF/[Undetermined. See<a href="rdf.field_linked_agent.md">RDF/field_linked_agent</a>] |
</dl>
<p><i>Last Updated: </i>08/26/2021</p>
</body>
</html>