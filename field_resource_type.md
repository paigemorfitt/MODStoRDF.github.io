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
<dd><b>Related Fields</b></dd>
	| <a href="mods.typeOfResource.md">MODS/typeOfResource</a> | 
	<a href="DrupalFields.md#Resource-Type">Drupal Field</a> | 
	<a href="rdf.dcterms.type.md">RDF/dcterms:type</a> |
</dl>
<p><i>Last Updated: </i>01/30/2023</p>
</body>
</html>
