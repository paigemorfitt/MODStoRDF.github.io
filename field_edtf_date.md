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

<h1>field_edtf_date</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Encoded date of creation or publication of the original object that strips out qualifiers and date ranges to allow us to sort on date in ARMINDA</td>
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
	<td>No</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>EDTF according to DateFormattingGuidelinesARMINDA </td>
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
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Former name: mods_date_created_keydate , Former name: IMI/date_sort</td>
</tr>
</table>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.originInfo.dateCreated.md">MODS/originInfo/dateCreated</a> | <a href="DrupalFields.md">Drupal field</a> | <a href="rdf.dcterms.date.md">dcterms:date</a> |
</dl>
<p><i>Last Updated: </i>09/23/2021</p>
</body>
</html>