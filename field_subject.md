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
  <table>
  
  
<h1>field_subject</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Term(s) representing the primary topic(s) on which a work is focused. </td>
</tr>
<tr>
	<th>Obligation</th>
	<td>Recommended</td>
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
	<td>Subjects</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Free-text (see ARMINDA taxonomy vocabulary terms)  </td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>LCSH, MeSH, Whitman College localized Subject list</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Field will be used within bounds of staff ability/size of collection</li>
			<li>Contains content from fromer fields: IMI/lc_subject, IMI/coverage_spatial, and IMI/subject_area.</li>
			<li>Contains, italics, bold, accents, and/or special characters</li>
			<li>Subject headings will be input into IMI Spreadsheet with no space between separating symbol (pipe)</li>
			<li>All terms must contain prefix of either “subject:”,”family:”,”person:”, or corporate_body</li>
			<li>corporate_body is for non-string terms Any term that begins with a corporate_body and is a string, must be prefixed with “subject:”</li>
			<li>Geographic terms in this field will be prefixed with “subject:”. Non-string geographic terms can solely be used in IMI/coverage_spatial</li>
			<li>We are NOT using the codes for this field. In lue of an Islandora reboot, codes would change.</li>
			<li>NOTE Islandora 8 Vocabulary is not a Controlled vocabulary and terms can be deleted from I8</li>
			<li>New terms are added to the taxonomy on ingest, as long as the .yml file says to create new terms. The exception is, you can't create new relators via Workbench, and you can't create new nested terms via Workbench (unless that was recently updated) taxonomy term.</li>
			<li>Pulls from various vocabularies (subject, person, corporate body) which is why it needs prefixes</li>
			<li>Terms can be deleted from I8</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Contains partial absorption of, IMI/coverage_spatial, Previous name : keywords, Former name: subject_keywords</td>
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
					<td>Entity Reference</td>
					<td>Unlimited</td>
					<td>Taxonomy term / corporate body, family, geographic location, person, subject</td>
				</tr>
			</table>
</details>
<dd><b>Related Fields</b></dd>
	|<a href="mods.subject.topic.md">MODS/subject/topic</a> | <a href="rdf.dcterms.subject.md">RDF/dcterms:subject</a> | 
<p><i>Last Updated: </i>09/03/2021</p>
</dl>
</body>
</html>
