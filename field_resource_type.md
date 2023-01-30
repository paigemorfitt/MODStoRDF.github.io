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

<h1>field_resource_type</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Basic conceptual indication of the kind of object being described, using broad terms to aid in theming of Islandora 8. </td>
</tr>
<tr>
	<th>Obligation</th>
	<td>Required</td>
</tr>
<tr>
	<th>Repeatable</th>
	<td>No</td>
</tr>
<tr>
	<th>Public Field</th>
	<td>No</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Free-text</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>Islandora Resource Types</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>This information should relate to the original object, not the digitized 				surrogate</li>
			<li>Vender uses this field for theming -- field is a trigger that dictates 				viewer</li>
			<li>Due to the structure of Islandora 8, field_resource_type is a technical 				metadata field that has more to do with display of objects and less of the Type of 			Resource the object is - thus the definition, parameters and rules are different than 				other descriptive metadata fields.</li>
			<li>“work_type” was describing physical object, but field_resource_type is using 			digital object</li>
			<li>Capitalize first work only</li>
			<li>NOT using image, ARE using still image</li>
			<li>Do not confuse with <i>field</i>_work_type</li>
			<li>work_type transitioned into  field_resource_type</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Former name: work_type</td>
</tr>
</table>
<h3>Related fields</h3>
<table>
	<tr>
		<th>Drupal Field</th>
		<th>MODS</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td>
			<a href="DrupalFields.md#Resource-Type">Resource Type</a></a>
		</td>
		<td>
			<a href="mods.typeOfResource.md">typeOfResource</a></a>
		</td>
		<td>
			<a href="rdf.dcterms.type.md">dcters:type</a></a>
		</td>
	</tr>
</table>
<p><i>Last Updated: </i>01/30/2023</p>
</body>
</html>
