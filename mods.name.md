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

<h1>MODS/name</h1>
<table>
<tr>
	<th>Definition</th>
	<td>The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource <a href="https://www.loc.gov/standards/mods/userguide/name.html"> (resources)<a/></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>type; authority; authorityURI; valueURI; usage; displayLabel; nameTitleGroup; altRepGroup; xlink; ID; lang; xml:lang; script; transliteration; etal</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>namePart,nameIdentifier,displayForm,affiliation,role,description</td>
</tr>
</table>
<h2>MODS/name/namePart</h2>
<table>
<tr>
	<th>Definition</th>
	<td>The individual parsed parts that together make up the full name.<a href="https://www.loc.gov/standards/mods/userguide/name.html#namepart"> (resources)<a/></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>lang; xml:lang; script; transliteration; altRepGroup; displayLabel; type</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>N/A</td>
</tr>
</table>
<h2>MODS/role</h2>
<table>
<tr>
	<th>Definition</th>
	<td>Designates the relationship (role) of the entity recorded in name to the resource described in the record.<a href="https://www.loc.gov/standards/mods/userguide/name.html#role"> (resources)<a/></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>N/A</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>roleTerm</td>
</tr>
</table>
<h3>MODS/role/roleTerm</h3>
<table>
<tr>
	<th>Definition</th>
	<td>Contains the textual or coded form of a relator/role.<a href="https://www.loc.gov/standards/mods/userguide/name.html#roleterm"> (resources)<a/></td>
</tr>
<tr>
	<th>Attributes</th>
	<td>authority; authorityURI; valueURI; lang; xml:lang; script; transliteration; type</td>
</tr>
<tr>
	<th>Subelements</th>
	<td>N/A</td>
</tr>
</table>
<dl>
	<dt><b>Related Fields</b></dt>
		<dd>| 
			<a href="advisor.md">IMI/advisors</a> | 
			<a href="DrupalFields.md">Drupal Fields</a> |
			<a href="rdf.field_linked_agent.md">field_linked_agent / local:adv</a> |
		</dd>
		<dd>|
			<a href="contributors.md">IMI/contributors</a> | 
			<a href="DrupalFields.md">Drupal Fields</a> |
			<a href="rdf.field_linked_agent.md">RDF/dcterms:contributor/ relators:ctb</a> |
		</dd>
		<dd>| 
			<a href="creators.md">IMI/creators</a> | 
			<a href="DrupalFields.md">Drupal Fields</a> |
			<td><a href="rdf.field_linked_agent.md">field_linked_agent/ relators:cre </a> |
		</dd>
		<dd>
			| <a href="department.md">IMI/department</a> | 
			<a href="DrupalFields.md">Drupal Fields</a> |
			<a href="rdf.field_linked_agent.md">RDF/local:dpt</a> |
		</dd>
		<dd>
			| <a href="field_funding_sources.md">field_funding_sources</a> | 
			<a href="DrupalFields.md">Drupal Fields</a> |				
			<a href="rdf.rdau.p60451.md">rdau:P60451</a> |
		</dd>
</dl>
<p><i>Last Updated: </i>09/27/2021</p>
</body>
</html>

