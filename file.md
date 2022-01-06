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

<h1>file</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Values contain field location of field that are used to create Drupal Media <a href="https://mjordan.github.io/islandora_workbench_docs/fields/">Islandora Workbench</a></td>
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
	<td>Relative, Absolute, URL (See Handbook for spreadsheet formula)</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>N/A</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Not a field in Islandora 8</li>
			<li>Not mapped</li>
			<li>Workbench field</li>
			<li>It can create more than one (depends on what media you want to pull over)</li>
			<li>Type of media is determined by identifying in your configuration file a value from “Islandora Media Use” vocabulary (terms to define how a media object is to be used)</li>
			<li>Relative, absolute and URL file locations can exist within the same CSV</li>
			<li>By default, if value is empty Workbench will show “error”</li>
			<li>Workbench downloads files identified by URLS and safes them to directory. Files identified by URLS must be accessible by Workbench script, and cannot point to a wrapper, or password protected page (firewalls are ok so long as computer running Workbench is allowed to retrieve files upon authentication)</li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>Parallel field : obj_file (removed)</td>
</tr>
</table>
</dl>
<p><i>Last Updated: </i>01/06/2022</p>
</body>
</html>