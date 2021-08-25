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



<h1>field_embargo_date</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Date when item is released for public viewing.</td>
</tr>
<tr>
	<th>Obligation</th>
	<td>Required, if applicable</td>
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
	<td>Embargoed Until</td>
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
			<li>[name will not change in order to allow this field to stand out from other date fields]</li>
			<li>Do not add encoding to field in IMI spreadsheet (ex: “||edtf||”)</li>
			<li>Single digit months must be prefixed with a 0. 1955-5 fails, 1955-05 is fine.</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Former name : IMI/embargo_date</td>
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
					<td>Custom field</td>
					<td>EDTF</td>
					<td>255 characters / Limited (1)</td>
					<td>N/A</td>
				</tr>
			</table>
</details>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.originInfo_dateValid.md">MODS/originInfo/dateValid</a></td>
			<td><a href="rdf.schema.availabilityStarts.md">RDF/schema:avalibilityStarts</a></td>
		</table>
</dl>
<p><i>Last Updated: </i></font>08/25/2021</p>
</body>
</html>