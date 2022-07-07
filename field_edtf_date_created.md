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

<h1>field_edtf_date_created</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Encoded date of creation or publication of the original object with qualifiers and date ranges when applicable</td>
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
	<th>Public-facing name</th>
	<td>N/A</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>EDTF according to DateFormattingGuidelinesARMINDA</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>N/A</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Currently this is maintained in order to have an encoded date that is as granular as possible within edtf</li>
			<li>Single digit months must be prefixed with a 0. 1955-5 fails, 1955-05 is fine.</li>
			<li>For Google Scholar, this field is being used for Publication Date</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field changes</th>
	<td>
		<ul>
		<li>Former name: oai_harvester_date</li>
		<li>Former name: date_encoded</li>
		<li>Absorbed: broad_creation_date</li>
		<li>Absorbed: broad_date</li>
		</ul>
	</td>
</tr>
</table>
<table>
	<tr>
		<th>MODS</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="mods.originInfo_dateOther.md">originInfo/dateOther</a></td> 
		<td><a href="DrupalFields.md#Date">Date Created (EDTF)</a></td>
		<td><a href="rdf.dcterms.created.md">dcterms:created</a></td>
	</tr>
</table>
<p><i>Last Updated: </i>07/07/2022</p>
</body>
</html>
