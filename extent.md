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
<h1>IMI/extent</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use:Statement of the physical size or duration of the object, such as dimensions, number of items, pages, or running time.</dd>
  <dd>Obligation:  Required, if applicable</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: Yes</dd>
  <dd>Public-facing name:Extent</dd>
  <dd>Syntax/Formatting:Free text</dd>
  <dd>Recommended Controlled Vocabulary:N/A</dd>
	<dd>Notes: 
		<ul>
			<li>This is not applied to digital file sizes or dpi</li>
			<li>Provide both a number/numbers and a designation of the units being measured.</li>
			<li>Example: “1 photograph” rather than just “1.”</li>
			<li>Content from Maxey and Sheehan removed. Moving forward, that field will be required for them to fill out</li>
		</ul>
	</dd>
  <dd><i>Field Changes: </i></font>New field. Comprised of IMI/pagecount, IMI/duration, IMI/artifact_number; Will move to field_extent</dd>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.physicalDescription.md">MODS/physicalDescription/extent</a></td>
			<td><a href="rdf.dcterms.extent.md">RDF/dcterms:extent</a></td>
		</table>
</dl>
<p><i>Last Updated: </i></font>05/25/2021</p>
</body>
</html>