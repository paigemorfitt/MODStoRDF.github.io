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
			<li>Contains date of items that are under embargo. When embargo date passes, information will stay.</li>
			<li>Do not add encoding to field in IMI spreadsheet (ex: “||edtf||”)</li>
			<li>Single digit months must be prefixed with a 0. 1955-5 fails, 1955-05 is fine.</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Former name : embargo_date</td>
</tr>
</table>
<table>
	<tr>
		<th>MODS</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="mods.originInfo_dateValid.md">originInfo/dateValid</a></td> 
		<td><a href="DrupalFields.md#Embargoed-Until">Embargoed Until</a></td>
		<td><a href="rdf.schema.availabilityStarts.md">schema:avalibilityStarts</a></td>
	</tr>
</table>
<p><i>Last Updated: </i></font>07/29/2022</p>
</body>
</html>
