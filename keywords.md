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
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Term(s) representing the primary topic(s) on which a work is focused</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Recommended</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Front-end Name:</font></ins>Subjects and Keywords</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free-text
  </dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>
		<ul>
			<li>Library of Congress Subject Headings (LCSH)</li>
			<li>Medical Subejct Headings (MeSH)</li>
			<li>Whitman College localized Subject list</li>
		</ul>
  </dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Field will be used within bounds of staff ability/size of collection</li>
		<li>Contains content from fromer fields: IMI/lc_subject, IMI/coverage_spatial, and IMI/subject_area.</li>
		<li>Contains HTML, accents, and special characters</li>
		<li>Subject headings will be input into IMI Spreadsheet with no space between separating symbol (either comma or semicolon)</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>Former name : IMI/keywords, contains partial absorption of IMI/coverage_spatial </dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins> /mods/subject/@displayLabel="Subject Headings"</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/dcterms:subject</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_subject_displayLabel_ms: mods_subject_displayLabel_ms(string)</li>
				<li>mods_subject_topic_ms: mods_subject_topic_ms(string)</li>
			</ul>
		</dd>
</dl>
<dl>
	<dt>IMI to MODS</dt>
		<dd>&lt;subject displayLabel="Subject Headings"&gt; 
&lt;topic&gt;{{jsonize(cells["keywords"].value).replace('null', '')}} 
&lt;/topic&gt;&lt;topic authority="lcsh"&gt;{{jsonize(cells["subject_keywords"].value).replace('null', '')}} 
&lt;/topic&gt;&lt;/subject&gt; </dd>
</dl>
<dl>
	<dt>IMI to RDF</dt>
		<dd>&lt;dcterms:subject&gt;{{jsonize(cells["subject_keywords"].value).replace('null', '')}}&lt;/dcterms:subject&gt;</dd>
</dl>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/11/2020</p>
</dl>
<dl>
<dd><b>Related Fields</b></dd>
	<table>
		<tr>
			<td><a href="mods.subject.topic.md">MODS/subject/topic</a></td>
			<td><a href="rdf.subject.md">RDF/dcterms:subject</a></td>
		</tr>
	</table>
</dl>
</body>
</html>