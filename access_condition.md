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

<h1>[here]</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Field that indicates item may be accessed by only current Whitman affiliates (netID holders).</dd>
  <dd>Obligation: Required, if applicable</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: Yes</dd>
  <dd>Public-facing name: Limited Access</dd>
  <dd>Syntax/Formatting:
	<ul>
		<li>Free-text</li>
	</ul>
  </dd>
  <dd>Recommended Controlled Vocabulary:In-house standard statement</dd>
  <dd>Notes: 
	<ul>
		<li>Limited Access: “The author(s) chose to restrict access to this thesis to current Whitman students, faculty, and staff. Please log in to view it.”</li>
		<li>Opt-Out: “Thesis is opt-out and not available for public view. Submission for Honors requirements only. Accessible to library staff only.”</li>
		</ul>
	</dd>
  <dd>Field Changes: will be renamed to field_limited_access</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
	  <dd> <ins>MODS XPath </ins>/mods/accessCondition</dd>
		<dd> <ins>RDF XPath</ins>/rdf:RDF/rdf:Description/reg:p60496</dd>
		<dd> <ins>SOLR field(s)</ins>
			<ul>
				<li>mods_accessCondition_Access_Statement_ms</li>
				<li>mods_accessCondition_ms</li>
			</ul>
		</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.access_condition.md">MODS/accessCondition</a> | <a href="rdf.rdau.p60496.md">RDF/rdau:P60496</a> |
</dl>
<p><i>Last Updated: </i>[here]</p>
</body>
</html>