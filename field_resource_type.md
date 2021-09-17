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
	<td>Basic conceptual indication of the kind of object being described, using broad terms.</td>
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
			<li>This information should relate to the original object, not the digitized surrogate</li>
			<li>If more than one present, record each value in new field</li>
			<li>Expectation: one type is sufficient for most object, however specific collections may have more guidance on particular cases</li>
			<li>If a term does not fit, bring to Metadata Working Group</li>
			<li>Born-digital uses this field for theming</li>
			<li>IMI/work_type was describing physical object, but field_resource_type is using digital object</li>
			<li>Capitalize first work only</li>
			<li>NOT using image, ARE using still image</li>
			<li>This field has been reformatted in current spreadsheets as field_resource_type HOWEVER, there is still a field_work_type in Islandora 8. <b>Do not confuse with field_work_type</b></li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Absorbed content from IMI/type_of_work, Former name: IMI/work_type</td>
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
					<td>Reference Entity</td>
					<td>255 characters/ Limited (1)</td>
					<td>Taxonomy / Islandora Resource Type</td>
				</tr>
			</table>
</details>
<dd><b>Related Fields</b></dd>
	| <a href="mods.typeOfResource.md">MODS/typeOfResource</a> | <a href="rdf.dcterms.type.md">RDF/dcterms:type</a> |
</dl>
<p><i>Last Updated: </i>09/17/2021</p>
</body>
</html>