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
			<li>In tandem with field_subject(Partial absorption by field_subject)</li>
			<li>Geographic content is not a string</li>
			<li>Multiple values separated by pipe with no spaces between termsField does NOT require prefix</li>
			<li>Does not contain string terms (contain ""--"") -- Exception are local terms which all start with ""Whitman College"</li>
			<li>We are NOT using the codes for this field. In lue of an Islandora reboot, codes would change.</li>
			<li>Islandora 8 Vocabulary is not a Controlled vocabulary</li>
			<li>Terms (taxonomy nodes) can be deleted from I8</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>
		<ul>
			<li>Partial absorption by: field_subject</li>
			<li>Former name: coverage_spatial</li>
		</ul>
	</td>
</tr>
</table>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.subject_geographic.md">subject/geographic</a></td> |
		<a href="DrupalFields.md#geographic-subject">Drupal Fields</a> | 
		<a href="rdf.dcterms_spatial.md">RDF/dcterms:spatial</a>|
</dl>
<p><i>Last Updated: </i>02/02/2022</p>
</body>
</html>
