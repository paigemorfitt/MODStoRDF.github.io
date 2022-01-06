<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th>Main page</th>
	<th><a href="IMI.md">IMI Column</a></th>
    <th><a href="MODS.md">MODS Field</a></th>
    <th><a href="RDF.md">RDF Field</a></th>
  </tr>
</table>

<h1>filepath</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Used in ARMIDNA as the filename of object; often times includes in ingest path for field - filename is in path  -- a place holder field that keeps track of where items are, and helps us distinguish between individual objects along with unique_identifier)</dd>
  <dd>Obligation: Required, if applicable</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field:No</dd>
  <dd>Syntax/Formatting:See specific Master Sheets for convention guidance</dd>
  <dd>Recommended Controlled Vocabulary:N/A</dd>
  <dd>Notes: 
	<ul>
		<li>Compound objects excluded</li>
		<li>If object has not been uploaded through IMI, this field may contain only the filename, not the file path including name</li>
		<li>Reflects metadata associated with objects from BePress for majority of collections</li>
		<li>Field's purpose is not fully fleshed out (as is hybrid location/identifier)</li>
		</ul>
	</dd>
		<dd><i>Field Changes: </i>
			<ul>
				<li>Field will undergo remediation in the future to reflect a reorganization of Islandora storage</li>
				<li>Field Not being ingested into Islandora 8</li>
			</ul>
		</dd>
	</dl>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="identifier.md">MODS/identifier</a></td>
		</table>
</dl>
<p><i>Last Updated: </i>05/25/2021</p>

</body>
</html>