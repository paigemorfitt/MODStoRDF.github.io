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

<h1>field_limited_access</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Field that indicates item may be accessed by only current Whitman affiliates (netID holders). </td>
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
	<td>Limited Access</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Free-text</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>In-house standard statement</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>There are two Access Condition fields. One is a taxonomy, one is a text field. This is for the text field. Taxonomy terms have do to with solr indexing and how queries are made. More insight is needed for them. </li>
			<li>Use terms not codes</li>
			<li>Only used for restricted access NOT embargoed content due to the space the message would take up on the page</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>
		<li>Former name: access_condition</li>
		<li>Prior to Islandora 8 limited access items were contained in a different bucket than open access items. For BePress that information can be seen in document_type and issue</li>
	</td>
</tr>
</table>
<h3>Related fields</h3>
<table>
	<tr>
		<th>MODS</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="mods.access_condition.md">accessCondition</a> </td>
		<td><a href="DrupalFields.md#limited-access">Limited Access</a> </td>
		<td><a href="rdf.rdau.p60496.md">rdau:P60496</a></td>
	</tr>
</table>
<p><i>Last Updated: </i>01/31/2023</p>
</body>
</html>
