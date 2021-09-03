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



<h1>field_source</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>A related resource from which the described resource is derived</td>
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
	<td>Source</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Free-text</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>Local Standards</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Use when the resource is the result of digitization of non-digital originals. In these cases, sufficient information to identify and find the original resource is provided.For example, for archives: Whitman College and Northwest Archives, Communication Office Records, Box 12, Folder 5.</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Contains content previously from the following fields: IMI/accession_number, IMI/catalog_id, IMI/collection_name, IMI/image_source, IMI/record_series, IMI/series_id, IMI/source_publication, Former name: source</td>
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
					<td>text (plain)</td>
					<td>255 characters / Limited (1)</td>
					<td>N/A</td>
				</tr>
			</table>
</details>
<dl>
	<dt><b>Related Fields</b></dt>
		|<a href="mods.relatedItem.part.text.md">MODS/relatedIetm/part/text</a> | <a href="rdf.dcterms.source.md">RDF/dcterms:source</a>|
</dl>
<p><i>Last Updated: </i>09/03/2021</p>
</body>
</html>