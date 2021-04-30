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
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource <a href="https://www.loc.gov/standards/mods/userguide/name.md"> (resources)<a/></dd>
  <dd>Attributes:  type; authority; authorityURI; valueURI; usage; displayLabel; nameTitleGroup; altRepGroup; xlink; ID; lang; xml:lang; script; transliteration; etal</dd>
  <dd>Subelements: namePart,nameIdentifier,displayForm,affiliation,role,description,etal</dd>
<dl>
<h2>MODS/name/namePart</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: The individual parsed parts that together make up the full name.<a href="https://www.loc.gov/standards/mods/userguide/name.md#namepart"> (resources)<a/></dd>
  <dd>Attributes: lang; xml:lang; script; transliteration; altRepGroup; displayLabel; type</dd>
  <dd>Subelements: N/A</dd>
</dl>
<h2>MODS/name/role</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: Designates the relationship (role) of the entity recorded in name to the resource described in the record.<a href="https://www.loc.gov/standards/mods/userguide/name.md#role"> (resources)<a/></dd>
  <dd>Attributes: N/A</dd>
  <dd>Subelements: roleTerm</dd>
</dl>
<h3>MODS/name/role/roleTerm</h3>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: Contains the textual or coded form of a relator/role.<a href="https://www.loc.gov/standards/mods/userguide/name.md#roleterm"> (resources)<a/></dd>
  <dd>Attributes: authority; authorityURI; valueURI; lang; xml:lang; script; transliteration; type</dd>
  <dd>Subelements: N/A</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		<dd>| <a href="advisor.md">IMI/advisors</a> | <a href="rdf.field_linked_agent.md">field_linked_agent / local:adv</a> |</dd>
		<dd>| <a href="contributors.md">IMI/contributors</a> | <a href="rdf.field_linked_agent.md">RDF/dcterms:contributor/ relators:ctb</a> |</dd>
		<dd>| <a href="creators.md">IMI/creators</a> | <td><a href="rdf.field_linked_agent.md">field_linked_agent/ relators:cre </a> |</dd>
		<dd>| <a href="department.md">IMI/department</a> | <a href="ield_linked_agent.md">RDF/schema:department</a> |</dd>
		<dd>| <a href="funding_sources.md">IMI/funding_sources</a> | <a href="rdf.p60451.md">RDF/rdau:P60451</a> |</dd>
</dl>
<p><i>Last Updated: </i>04/30/2021</p>
</body>
</html>