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

<h1>field_edtf_date_issued</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Issue date of the newspaper</td>
</tr>
<tr>
	<th>Obligation</th>
	<td>Required</td>
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
	<td>Publication Date</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>DateFormattingGuidelinesARMINDA</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>N/A</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Single digit months must be prefixed with a 0. 1955-5 fails, 1955-05 is fine.</li>
			<li>Date issued needs to be displayed in order to work for newspapers</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>
		<li>Former name: date_issued</li>
	</td>
</tr>
</table>
<dt><b>Related Fields</b></dt>
<table>
	<tr>
		<th>MODS</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="mods.originInfo_dateIssued.md">MODS/originInfo/dateIssued</a></td>
		<td><a href="DrupalFields.md#Date-issued-edtf">Drupal Fields</a></td>
		<td><a href="rdf.dcterms.issued.md">RDF/dcterms:issued</a> </td>
	</tr>
</table>
<p><i>Last Updated: </i>08/31/2023</p>
</body>
</html>
