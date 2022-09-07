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

<h1>field_extent</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Statement of the physical size or duration of the object, such as dimensions, number of items, pages, or running time. </td>
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
	<td>Extent</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Free-text</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>N/A</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>This is not applied to digital file sizes or dpi</li>
			<li>Provide both a number/numbers and a designation of the units being measured.</li>
			<li>Example: “1 photograph” rather than just “1.”</li>
			<li>Content from Maxey and Sheehan removed. Moving forward, that field will be required for them to fill out</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>
		<ul>
			<li>Absorbed: pagecount</li>
			<li>Absorbed: duration</li>
			<li>Absorbed: artifact_number</li>
			<li>Former name: extent</li>
		</ul>
	</td>
</tr>
</table>
<table>
	<tr>
		<th>MODS</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="mods.physicalDescription.extent.md">physicalDescription/extent </a></td> 
		<td><a href="DrupalFields.md#Extent">Extent</a></td>
		<td><a href="rdf.dcterms.extent.md">dcterms:extent</a></td>
	</tr>
</table>
<p><i>Last Updated: </i></font>09/07/2022</p>
</body>
</html>
