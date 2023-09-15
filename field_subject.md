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
			<li>Contains, italics, bold,  accents, and/or special characters</li>
			<li>Subject headings will be input into IMI Spreadsheet with no space between separating symbol (pipe)</li>
			<li>All terms must contain prefix of either “subject:”,”family:”,”person:”, or "corporate_body:" (Pulls from various vocabularies (subject, person, corporate body) which is why it needs prefixes)</li>
			<li>More guidance on for Names as Subject Headings, see field_linked_agent </li>
			<li>We are NOT using the codes for this field. In lue of an Islandora reboot, codes would change. </li>
			<li>NOTE Islandora 8 Vocabulary is not a Controlled vocabulary  and terms can be deleted from I8</li>
			<li>New terms are added to the taxonomy on ingest, as long as the .yml file says to create new terms. The exception is, you can't create new relators via Workbench, and you can't create new nested terms via Workbench (unless that was recently updated) taxonomy term. </li>
			<li>Terms can be deleted from I8</li>
			<li>Names in which there is a string are prefixed as "subject" not "person" </li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Former name: keywords, coverage_spatial; Former name: subject_keywords</td>
</tr>
</table>
<h3>Related fields</h3>
<table>
	<tr>
		<th>MODS</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="mods.subject.topic.md">subject/topic</a></td> 
		<td><a href="DrupalFields.md#subject">Subject</a></td>
		<td><a href="rdf.dcterms.subject.md">dcterms:subject</a></td>
	</tr>
</table>
<p><i>Last Updated: </i>09/15/2023</p>
</dl>
</body>
</html>
