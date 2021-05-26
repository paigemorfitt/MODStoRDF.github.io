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
<h1>IMI/subject_keywords</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Term(s) representing the primary topic(s) on which a work is focused.</dd>
  <dd>Obligation: Recommended</dd>
  <dd>Repeatable: Yes</dd>
  <dd>Public Field: Yes</dd>
  <dd>Front-end Name: Subjects</dd>
  <dd>Syntax/Formatting: Free-text</dd>
  <dd>Recommended Controlled Vocabulary:
		<ul>
			<li>Library of Congress Subject Headings (LCSH)</li>
			<li>Medical Subejct Headings (MeSH)</li>
			<li>Whitman College localized Subject list</li>
		</ul>
  </dd>
  <dd>Notes: 
	<ul>
		<li>Field will be used within bounds of staff ability/size of collection</li>
		<li>Contains content from fromer fields: IMI/lc_subject, IMI/coverage_spatial, and IMI/subject_area.</li>
		<li>Contains, italics, bold, accents, and/or special characters</li>
		<li>Subject headings will be input into IMI Spreadsheet with no space between separating symbol (pipe)</li>
		<li>All terms must contain prefix of either “subject:”,”family:”,”person:”, or corporate_body</li>
		<li>Corporate_body is for non-string terms Any term that begins with a corporate_body and is a string, must be prefixed with “subject:”</li>
		<li>Geographic terms in this field will be prefixed with “subject:”. Non-string geographic terms can solely be used in IMI/coverage_spatial</li>
	</ul>
  </dd>
  <dd><i>Field Changes: </i>Former name : IMI/keywords, contains partial absorption of IMI/coverage_spatial; Will move to field_subject </dd>
</dl>
<dd><b>Related Fields</b></dd>
	|<a href="mods.subject.topic.md">MODS/subject/topic</a> | <a href="rdf.dcterms.subject.md">RDF/dcterms:subject</a> | 
<p><i>Last Updated: </i>05/26/2021</p>
</dl>
</body>
</html>