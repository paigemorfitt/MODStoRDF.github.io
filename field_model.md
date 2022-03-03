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

<h1>field_model</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>Obligation: Required</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: No</dd>
  <dd>Public-facing name:N/A</dd>
  <dd>Syntax/Formatting: Free-text</dd>
  <dd>Recommended Controlled Vocabulary: Islandora Model terms</dd>
  <dd><b>Notes:</b>
	<li>Necessary for Islandora. Necessary for Islandora. This is the "type" of resource, this does affect how it is displayed/viewed.</li>
	</dd>
  <dd>Field Changes: 
	<li>Repurpose. Strip terms for Controlled Terms.</li>
	<li>former name IMI/cmodel</li>
	</dd>
	<details>
		<summary><b>Islandora 8 notes</b></summary>
			<li> Note: default field</li>
			<li>Type of field: Entity Reference</li>
			<li>Max Length/Repeatability: Limited (1)</li>
			<li>Type of Item Reference/Vocabulary: Taxonomy Term / Islandora Models</li>
	</details>
</dl>
<h1>[field]</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Tells what content model the file is -- audio, image.etc;  tells what type of file for Islandora to expect. </td>
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
	<td>Islandora Models</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Also referred to as System Model</li>
			<li>Necessary for Islandora, this is the "type" of resource that affects how items are displayed/viewed.</li>
			<li>repurposed, from former field, terms converted to conform to Islandora Models terms</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Former name: cmodel</td>
</tr>
</table>

<dl>
	<dt><b>Related Fields</b></dt>
	| 	<a href="DrupalFields.md">Drupal Fields</a> || <a href="rdf.pcdm_memberOf.md">RDF/pcdm:memberOf</a> |
</dl>
<p><i>Last Updated: </i>03/03/2022</p>
</body>
</html>