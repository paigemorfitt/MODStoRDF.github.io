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

<h1>IMI/date_sort</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Encoded date of creation or publication of the original object that strips out qualifiers and date ranges to allow us to sort on date in ARMINDA</dd>
  <dd>Obligation: Required, if applicable. </dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: No</dd>
  <dd>Syntax/Formatting: EDTF according to DateFormattingGuidelinesARMINDA </dd>
  <dd>Recommended Controlled Vocabulary: N/A</dd>
  <dd>Notes: Single digit months must be prefixed with a 0. 1955-5 fails, 1955-05 is fine.</dd>
  <dd>Field Changes: 
	<ul>
		<li>Previous name mods_date_created_keydate</li>
		<li>Machine name:field_edtf_date</li>
	</ul>
  </dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.originInfo.dateCreated.md">MODS/originInfo/dateCreated</a> | <a href="rdf.dcterms.date.md">dcterms:date</a> |
</dl>
<p><i>Last Updated: </i>06/18/2021</p>
</body>
</html>