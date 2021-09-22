<!DOCTYPE html>
<html>
<body>

<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th><a href="IMI.md">IMI Column</a></th>
    <th><a href="MODS.md">MODS Field</a></th>
	<th>Drupal Fields</th>
    <th><a href="RDF.md">RDF Field</a></th>
  </tr>
<table>
<h1>Drupal Field descriptions</h1>
<h2>Abstract</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Text (formatted, long)</td>
					<td>N/A / Limited (1)</td>
					<td>N/A</td>
					<td>field_abstract</td>
					<td>Custom field</td>
				</tr>
			</table>
	<dl>
			<dt><b>Related Fields</b></dt>
				| <a href="field_abstract.md">field_abstract</a> | <a href="mods.abstract.md">MODS/abstract</a> | <a href="rdf.dcterms.abstract.md">RDF/dcterms:abstract </a> |
		</dd>
	</dl>
<h2>field_access_terms</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Entity reference</td>
					<td>N/A / Unlimited</td>
					<td>Taxonomy term / Islandora Access</td>
					<td>field_access_terms</td>
					<td>Custom field?</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				<dd>| <a href="field_access_terms.md">field_access_terms</a> 
	</dl>
<dl>
<h2>field_limited_access</h2>
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
				| <a href="access_condition.md">access_condition</a> | <a href="mods.access_condition.md">accessCondition</a> | <a href="rdf.rdau.p60496.md">rdau:P60496</a> | 
		</dd>
	</dl>
<h2>field_linked_agent</h2>
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
				<dd>| <a href="advisor.md">advisors</a> | <a href="mods.name.md">name/namePart</a> | <a href="rdf.field_linked_agent.md">local:adv</a> | </dd>
				<dd>| <a href="contributors.md">contributors</a> | <a href="mods.name.md">name/namePart</a> | <a href="rdf.field_linked_agent.md">relators:ctb</a> | </dd>
	</dl>
<h2>field_model</h2>
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
				| <a href="cmodel.md">cmodel</a> | <a href="rdf.dcterms.provenance.md">pcdm:memberOf</a> | 
	</dl>
<p><i>Last Updated: </i>09/22/2021</p>
</body>
</html>