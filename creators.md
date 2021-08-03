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

<h1>IMI/creators</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>identifies the entity/entities primarily responsible for making the resource</td>
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
	<td>Creator</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>
		<ul>
			<li>Free text / RDA 19.2</li>
			<li>Personal name: LastName, FirstName MiddleName (or Initial)</li>
			<li>For multiple authors, separate with pipe with no space trailing.</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>LCNAF, VIAF, my.whitman, local names</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Provide as much known information as possible (either provided on resource or found elsewhere)</li>
			<li>Separate repeated terms consistently (with pipe)</li>
			<li>If names are not found in a controlled vocabulary, format personal names as Lastname , Firstname according to RDA/DACS</li>
			<li>If name(s) of creator(s) is not known, see master spreadsheet guidelines for specific details</li>
			<li>No distinguishing between Private and Corporate creators</li>
			<li>Do birthdate or death date unless to disambiguate identical named individuals</li>
			<li>Contains html, accents, and/or special characters</li>
		</ul>
	</td>
</tr>
</table>
<details>
		<summary><b>Islandora 8 notes</b></summary>
			<table>
				<tr>
					<th><i>Note</i>
				</tr>
				<tr>
					<td>Content moving to field_linked_agent</td>
				</tr>
			</table>
</details>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.name.md">MODS/name/namePart</a> | <a href="rdf.field_linked_agent.md">RDF/local:adv</a> |
</dl>
<p><i>Last Updated: </i>06/17/2021</p>
</body>
</html>