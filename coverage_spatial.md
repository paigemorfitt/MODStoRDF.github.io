<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th><a href="IMI.md">IMI Column</a></th>
    <th><a href="MODS.md">MODS Field</a></th>
    <th><a href="RDF.md">RDF Field</a></th>
  </tr>
</table>



<h1>IMI/coverage_spatial</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins>ARMINDA Use: </ins>Geographic subject headings</dd>
  <dd><ins>Obligation: </ins> Recommended, if applicable</dd>
  <dd><ins>Repeatable: </ins> Yes</dd>
  <dd><ins>Public Field: </ins>Yes</dd>
  <dd><ins>Front-end name: </ins>Geographic Subject</dd>
  <dd><ins>Syntax/Formatting: </ins>Free-text</dd>
  <dd><ins>Recommended Controlled Vocabulary: </ins>LCSH, GNIS, Getty Geographic Names, MARC GAC, local geographic names list </dd>
  <dd><ins>Notes: </ins>
	<ul>
		<li>In tandem with IMI/keywords</li>
		<li>Geographic content is not a string</li>
		<li>Multiple values separated by pipe with no spaces between terms.</li>
		<li>Field does NOT require prefix</li>
		</ul>
	</dd>
  <dd><i>Field Changes: </i>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
	  <dd> <ins>MODS XPath </ins> /mods/subject/geographic</dd>
		<dd> <ins>RDF XPath</ins>/rdf:RDF/dc:spatial</dd>
		<dd> <ins>Solr Field(s)</ins>
			<ul>
				<li>mods_subject_displayLabel_ms</li>
				<li>mods_subject_geographic_ms</li>
			</ul>
		</dd>
</dl>
<dl>
	<p><i>Last Updated: </i>4/23/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.subject_geographic.md">MODS/subject/geographic</a></td>
			<td><a href="rdf.spatial.md">RDF/dcterms:spatial</a></td>
			<td><a href="workbench_field_geographic_subject.md">Machine Name/field_geographic_subject</a></td>
		</table>
</dl>
</body>
</html>