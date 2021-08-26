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

<h1>field_genre</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>A more detailed sub-type refining the broader Work Type element; provides a specific characterization of the nature or style of the original content source</td>
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
	<td>Genre</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Free-text</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>AAT, COAR, and Whitman College local genre list </td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Caution: do not confuse with the more general type category or with format/physical description.</li>
			<li>Capitalize words</li>
			<li>Content from Maxey and Sheehan removed. Moving forward, that field will be required for them to fill out</li>
			<li>We are NOT using the codes for this field. In lue of an Islandora reboot, codes would change.</li>
			<li>NOTE Islandora 8 Vocabulary is not a Controlled vocabulary and terms can be deleted from I8</li>
			<li>Our mapping is NOT the default mapping</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Former name : IMI/genre; MODS/genre</td>
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
					<td>Default Field (changed the RDF mapping from dc:type to schema:genre)</td>
					<td>Entity Reference</td>
					<td>Unlimited</td>
					<td>Taxonomy Term / Genre</td>
				</tr>
			</table>
</details>
<dl>
	<dt><b>Related Fields</b></dt>
		|<td><a href="mods.genre.md" >MODS/genre</a> | <a href="rdf.schema.genre.md" >RDF/schema:genre</a>|
</dl>
<p><i>Last Updated: </i>08/26/2021</p>
</body>
</html>
