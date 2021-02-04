<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th>IMI Columns</th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="#">RDF Fields</a></th>
  </tr>
</table>

<h1>IMI/access_condition</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>Field that indicates item may be accessed by only current Whitman affiliates (netID holders).</dd>
  <dd><ins><font color="brown">Obligation:</font></ins>Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins>No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Public-facing name: </font></ins>Access Information</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free-text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins> In-house standard Statement</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>Limited Access: "The author(s) chose to restrict access to this thesis to current Whitman students, faculty, and staff. Please log in to view it."</li>
		<li>Opt-Out: "Thesis is opt-out and not available for public view. Submission for Honors requirements only. Accessible to library staff only."</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
	  <dd> <ins><font color="brown">MODS XPath </font></ins>/mods/accessCondition</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/reg:p60496</dd>
		<dd> <ins><font color="brown">SOLR field(s)</font></ins>
			<ul>
				<li>mods_accessCondition_Access_Statement_ms: mods_accessCondition_Access_Statement_ms(string)</li>
				<li>mods_accessCondition_ms: mods_accessCondition_ms(string) </li>
			</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>1/20/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.access_condition.md">MODS/accessCondition</a></td>
			<td><a href="rdf.rdau.p60496.md">RDF/rdau:P60496</a></td>
		</table>
</dl>
</body>
</html>