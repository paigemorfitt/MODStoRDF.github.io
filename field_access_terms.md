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
<h1>field_access_terms</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>“Terms used to limit, restrict or coordinate access” - Islandora 8</td>
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
	<td>Entity Reference/Taxonomy</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>Islandora Access</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Field must be used in conjunction with field_access_terms with IMI/access_condition</li>
			<li>[This I8 field will not be mapped to RDF as it reproduces information in IMI/access_condition]</li>
			<li>Taxonomy terms have to do with how solr index is or how queries are made.</li>
			<li>We are NOT using the codes for this field. In lue of an Islandora reboot, codes would change. Keeping the terms will make it easier to keep track of access.</li>
			<li>Production and Staging codes may differ</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>N/A</td>
</tr>
</table>
<dl>
	<dt><b>Related Fields</b></dt>
		 <a href="DrupalFields.md#access-control">Drupal Fields</a>
</dl>
</dl>
<p><i>Last Updated: </i>06/29/2023</p>
</body>
</html>
