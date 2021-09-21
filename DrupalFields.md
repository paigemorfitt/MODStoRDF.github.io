<!DOCTYPE html>
<html>
<head>

</head>
<body>

<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th><a href="IMI.md">IMI Columns</a></th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="RDF.md">RDF Fields</a></th>
  </tr>
</table>
<h1>Islandora 8 Machine Names</h1>
<h2>Abstract</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
				</tr>
				<tr>
					<td>[here]</td>
					<td>[here]</td>
					<td>[here]</td>
					<td>[here]</td>
				</tr>
			</table>
	<dl>
			<dt><b>Related Fields</b></dt>
				| <a href="abstract.md">IMI/abstract</a> | <a href="mods.abstract.md">MODS/abstract</a> | <a href="rdf.abstract.md">RDF/dcterms:abstract </a> |
		</dd>
	</dl>
<dl>
<h2>field_limited_access</h2>
	<dl>
		<dd>Type of Field: [unchecked]</dd>
		<dd>Label: Limited Access</dd>
		<dd>Max Length/Repeatability: [unchecked]</dd>
		<dd>
			<dt><b>Related Fields</b></dt>
				| <a href="access_condition.md">access_condition</a> | <a href="mods.access_condition.md">accessCondition</a> | <a href="rdf.rdau.p60496.md">rdau:P60496</a> | 
		</dd>
	</dl>
<h2>field_linked_agent</h2>
	<dl>
		<dd>Type of Field: [unchecked]</dd>
		<dd>Label: 
				<ul>
					<li>Advisor</li>
					<li>Contributor</li>
				</ul>
		</dd>
		<dd>Max Length/Repeatability: [unchecked]</dd>
	</dl>
	<dl>
		<dt><b>Related Fields</b></dt>
				<dd>| <a href="advisor.md">advisors</a> | <a href="mods.name.md">name/namePart</a> | <a href="rdf.field_linked_agent.md">local:adv</a> | </dd>
				<dd>| <a href="contributors.md">contributors</a> | <a href="mods.name.md">name/namePart</a> | <a href="rdf.field_linked_agent.md">relators:ctb</a> | </dd>
	</dl>
<h2>field_model</h2>
	<dl>
		<dd>Type of Field: [unchecked]</dd>
		<dd>Label: Model</dd>
		<dd>Max Length/Repeatability: [unchecked]</dd>
	</dl>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="cmodel.md">cmodel</a> | <a href="rdf.dcterms.provenance.md">pcdm:memberOf</a> | 
	</dl>
<p><i>Last Updated: </i>4/26/2021</p>
</body>
</html>