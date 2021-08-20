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
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: "Values contain field location of fields that are used to create Drupal Media"<a href="https://mjordan.github.io/islandora_workbench_docs/fields/">Workbench"</a></dd>
  <dd>Obligation: Required, if applicable</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: No</dd>
  <dd>Public-facing name: No</dd>
  <dd>Syntax/Formatting: Relative, Absolute, or URL</dd>
  <dd>Recommended Controlled Vocabulary: N/A</dd>
  <dd>Notes: 
	<ul>
		<li>Not a field in Islandora 8</li>
		<li>Not mapped</li>
		<li>Workbench field</li>
		<li>It can create more than one (depends on what media you want to pull over)</li>
		<li>Type of media is determined by identifying in your configuration file a value from “Islandora Media Use” vocabulary (terms to define how a media object is to be used) </li>
		<li>Relative, absolute and URL file locations can exist within the same CSV</li>
		<li>By default, if value is empty Workbench will show “error” </li>
		<li>Workbench downloads files identified by URLS and safes them to directory. Files identified by URLS must be accessible by Workbench script, and cannot point to a wrapper, or password protected page (firewalls are ok so long as computer running Workbench is allowed to retrieve files upon authentication) </li>
		</ul>
	</dd>
  <dd>Field Changes: Parallel field : obj_file (removed)</dd>
</dl>
<p><i>Last Updated: </i>08/20/2021</p>
</body>
</html>