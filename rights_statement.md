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

<h1>IMI/rights_statement</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>URL that indicates copyright and/or creative commons status supplemented with optional explanatory text. Can include free-text explanation of rights.  </dd>
  <dd><ins><font color="brown">Obligation:</font></ins>Required</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins>No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
  <dd><ins><font color="brown">Front-end Name:</font></ins>Rights Statement</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free-text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>Must contain a url from  RightsStatements.org or CreativeCommons.org</dd>
  <dd><ins><font color="brown">Notes: </font></ins>
		<ul>
			<li>At minimum, provide, link.</li>
			<li>Standardized statement varies from collection to collection. For specific use case, see Mastersheet guidelines</li>
		</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins>/mods/accessCondition</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/reg:P60339</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_accessCondition_displayLabel_ms: mods_accessCondition_displayLabel_ms(string)</li>
				<li>mods_accessCondition_ms: mods_accessCondition_ms(string)</li>
				<li>mods_accessCondition_Rights_Statement_ms: mods_accessCondition_Rights_Statement_ms(string)</li>
			</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/17/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="rights_statement.md">IMI/rights_statement</a></td>
			<td><a href="mods.access_condition.md">MODS/accessCondition</a></td>
			<td><a href="rdf.rdau.P60339.md">RDF/rdau:P60339</a></td>
		</table>
</dl>
</body>
</html>