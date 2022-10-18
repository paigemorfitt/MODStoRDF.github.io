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
	<dt>Related fields</dt>
<table>
	<tr>
		<th>Spreadsheet</th>
		<th>Drupal Field</th>
		<th>RDF</th>
	</tr>
	<tr>
		<td><a href="advisor.md">advisors</a></td>
		<td><a href="DrupalFields.md#Linked-Agent">Linked Agent</a></td>
		<td><a href="rdf.relators.md#localadv">local:adv</a></td>
	</tr>
	<tr>
		<td><a href="contributors.md">contributors</a></td> 
		<td><a href="DrupalFields.md#Linked-Agent">Linked Agent</a></td>
		<td><a href="rdf.relators.md#relatorsctb">relators:ctb</a></td>
	</tr>
	<tr>
		<td><a href="creators.md">creators</a></td>
		<td><a href="DrupalFields.md#Linked-Agent">Linked Agent</a></td>
		<td><a href="rdf.relators.md#relatorscre">relators:cre</a></td>
	</tr>
	<tr>
		<td><a href="department.md">department</a></td>
		<td><a href="DrupalFields.md#Linked-Agent">Linked Agent</a></td>
		<td><a href="rdf.relators.md#localdpt">local:dpt</a></td>
	</tr>
	<tr>
		<td><a href="field_funding_sources.md">field_funding_sources</a></td>
		<td><a href="DrupalFields.md#Funding">Funding</a></td>	
		<td><a href="rdf.rdau.p60451.md">rdau:P60451</a></td>
	</tr>
</table>


<p><i>Last Updated: </i>10/18/2022</p>
</body>
</html>

