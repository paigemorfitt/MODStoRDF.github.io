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

<h1>IMI/coverage_spatial</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Geographic subject headings</dd>
  <dd>Obligation: Recommended, if applicable</dd>
  <dd>Repeatable: Yes</dd>
  <dd>Public Field: Yes</dd>
  <dd>Public-facing name: Geographic Subjects</dd>
  <dd>Syntax/Formatting: Free-text</dd>
  <dd>Recommended Controlled Vocabulary: LCSH, GNIS, Getty Geographic Names, MARC GAC  , local geographic names list </dd>
  <dd>Notes: 
	<ul>
		<li>In tandem with IMI/subject_keywords (Partial absorption by IMI/subject_keywords)</li>
		<li>Geographic content is not a string</li>
		<li>Multiple values separated by pipe with no spaces between termsField does NOT require prefix</li>
		<li>Does not contain string terms (contain ""--"")</li>
		<li>Exception are local terms which all start with ""Whitman College"</li>
	</ul>
	</dd>
  <dd>Field Changes: partial absorption by IMI/subject-keywords, will be renamed to field_geographic_subject</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <td><a href="mods.subject_geographic.md">subject/geographic</a></td> | <a href="rdf.dcterms_spatial.md">RDF/dcterms:spatial</a>|
</dl>
<p><i>Last Updated: </i>06/17/2021</p>
</body>
</html>