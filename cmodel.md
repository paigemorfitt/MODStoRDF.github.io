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
  <dd>ARMINDA Use: Tells what content model the file is -- audio, image.etc;  tells what type of file for Islandora to expect. </dd>
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
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="rdf.pcdm_memberOf.md">RDF/pcdm:memberOf</a> |
</dl>
<p><i>Last Updated: </i>07/29/2021</p>
</body>
</html>