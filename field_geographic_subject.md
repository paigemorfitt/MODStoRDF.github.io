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

<h1>field_geographic_subject</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Geographic subject headings</td>
</tr>
<tr>
	<th>Obligation</th>
	<td>Recommended, if applicable</td>
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
	<td>Geographic Subjects</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Free-text</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>LCSH, GNIS, Getty Geographic Names, MARC GAC, Local Geographic Names list</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Used in tandem with field_subject (partial absorption by field_subject)</li>
			<li>Geographic content is not a string / does not contain string terms ("--") however, there is an exception to local geographic terms which start with "Whitman College"</li>
			<li>Multiple values separated by pipe with no spaces between terms. </li>
			<li>Field does not require prefix</li>
			<li>We are not using the codes for this field. In lue of an Islandora reboot, codes would change.</li>
			<li>Islandora 8 vocabulary is not a controlled vocabulary, and terms can be deleted.</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>former name: IMI/coverage_spatial</td>
</tr>
</table>
	<details>
		<summary><b>Islandora 8 notes</b></summary>
			<li> Note: default field</li>
			<li>Type of field: Entity reference</li>
			<li>Max Length/Repeatability: Unlimited</li>
			<li>Type of Item Reference/Vocabulary: Taxonomy Term / Geographic Location </li>
	</details>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.subject_geographic.md">subject/geographic</a></td> |
		<a href="DrupalFields.md#geographic">Drupal Fields</a>
		<a href="rdf.dcterms_spatial.md">RDF/dcterms:spatial</a>|
</dl>
<p><i>Last Updated: </i>09/27/2021</p>
</body>
</html>
