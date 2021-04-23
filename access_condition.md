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

<h1>IMI/access_condition</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins>ARMINDA Use: </ins>Field that indicates item may be accessed by only current Whitman affiliates (netID holders).</dd>
  <dd><ins>Obligation: </ins>Required, if applicable</dd>
  <dd><ins>Repeatable: </ins>No</dd>
  <dd><ins>Public Field: </ins>Yes</dd>
  <dd><ins>Public-facing name: </ins>Limited Access</dd>
  <dd><ins>Syntax/Formatting: </ins>Free-text</dd>
  <dd><ins>Recommended Controlled Vocabulary: </ins> In-house standard Statement</dd>
  <dd><ins>Notes: </ins>
	<ul>
		<li>Limited Access: "The author(s) chose to restrict access to this thesis to current Whitman students, faculty, and staff. Please log in to view it."</li>
		<li>Opt-Out: "Thesis is opt-out and not available for public view. Submission for Honors requirements only. Accessible to library staff only."</li>
		</ul>
	</dd>
  <dd><i>Field Changes: </i>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
	  <dd> <ins>MODS XPath </ins>/mods/accessCondition</dd>
		<dd> <ins>RDF XPath</ins>/rdf:RDF/rdf:Description/reg:p60496</dd>
		<dd> <ins>SOLR field(s)</ins>
			<ul>
				<li>mods_accessCondition_Access_Statement_ms: mods_accessCondition_Access_Statement_ms(string)</li>
				<li>mods_accessCondition_ms: mods_accessCondition_ms(string) </li>
			</ul>
		</dd>
</dl>
	<p><i>Last Updated: </i>4/23/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.access_condition.md">MODS/accessCondition</a></td>
			<td><a href="rdf.rdau.p60496.md">RDF/rdau:P60496</a></td>
			<td><a href="workbench_field_limited_access.md">Machine Name/field_limited_access</a></td>
		</table>
</dl>
</body>
</html>