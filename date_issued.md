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

<h1>IMI/date_issued</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Issue date of the newspaper</dd>
  <dd>Obligation: Required</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: Yes</dd>
  <dd>Public-facing name: Publication Date</dd>
  <dd>Syntax/Formatting: DateFormattingGuidelinesARMINDA</dd>
  <dd>Recommended Controlled Vocabulary: N/A</dd>
  <dd>Notes: 
		<ul>
			<li>Single digit months must be prefixed with a 0. 1955-5 fails, 1955-05 is fine.</li>
			</li>Date issued needs to be displayed in order to work for newspapers</li>
		</ul>
  </dd>
  <dd>Field Changes: Machine name : field_edtf_date_issued</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.originInfo_dateIssued.md">MODS/originInfo/dateIssued</a> | <a href="rdf.dcterms.issued.md">dcterms:issued</a> |
</dl>
<p><i>Last Updated: </i>06/18/2021</p>
</body>
</html>