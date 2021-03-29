<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th>IMI Columns</th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="RDF.md">RDF Field</a></th>
  </tr>
</table>

<h1>IMI/filepath</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Used in ARMIDNA as the filename of object; often times includes in ingest path for field - filename is in path  -- a place holder field that keeps track of where items are, and helps us distinguish between individual objects along with unique_identifier</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>No</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>See specific Master Sheets for convention guidance</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Compound objects excluded</li>
		<li>If object has not been uploaded through IMI, this field may contain only the filename, not the file path including name</li>
		<li>Reflects metadata associated with objects from BePress for majority of collections</li>
		<li>Field's purpose is not fully fleshed out (as is hybrid location/identifier)</li>
		</ul>
	</dd>
		<dd><font color="blue"><i>Field Changes: </i></font>Field will undergo remediation in the future to reflect a reorganization of Islandora storage </dd>
	</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd><ins><font color="brown">MODS XPath </font></ins>/mods/identifier/</dd>
		<dd><ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdau:P61166</dd>
		<dd><ins><font color="brown">Solr Fields</font></ins>mods_identifier_filepath_ms: mods_identifier_filepath_ms(string)</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>3/29/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.identifier.md">MODS/identifier</a></td>
		</table>
</dl>
</body>
</html>