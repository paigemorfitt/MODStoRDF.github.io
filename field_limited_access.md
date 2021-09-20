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

<h1>field_limited_access</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Field that indicates item may be accessed by only current Whitman affiliates (netID holders). </td>
</tr>
<tr>
	<th>Obligation</th>
	<td>Required, if applicable</td>
</tr>
<tr>
	<th>Repeatable</th>
	<td>No</td>
</tr>
<tr>
	<th>Public Field</th>
	<td>Yes</td>
</tr>
<tr>
	<th>Public-facing name</th>
	<td>Limited Access</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Free-text</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>In-house standard statement</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>There are two Access Condition fields.The other is field_access_terms</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Former name: IMI/access_condition</td>
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
					<td>Custom field</td>
					<td>Entity reference</td>
					<td>Unlimited</td>
					<td>Taxonomy Terms / Islandora Access</td>
				</tr>
			</table>
</details>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.access_condition.md">MODS/accessCondition</a> | <a href="rdf.rdau.p60496.md">RDF/rdau:P60496</a> |
</dl>
<p><i>Last Updated: </i>09/20/2021</p>
</body>
</html>