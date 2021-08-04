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
			</li>Date issued needs to be displayed in order to work for newspapers</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>
		<li>former name: date_issued</li>
	</td>
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
					<td>Default</td>
					<td>EDTF</td>
					<td>128 Characters / Unlimited</td>
					<td>N/A</td>
				</tr>
			</table>
</details>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.originInfo_dateIssued.md">MODS/originInfo/dateIssued</a> | <a href="rdf.dcterms.issued.md">dcterms:issued</a> |
</dl>
<p><i>Last Updated: </i>08/04/2021</p>
</body>
</html>