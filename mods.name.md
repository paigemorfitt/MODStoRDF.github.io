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
  <dd><ins><font color="brown">Definition</font></ins>The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource <a href="https://www.loc.gov/standards/mods/userguide/name.md"> (resources)<a/></dd>
  <dd><ins><font color="brown">Attributes</font></ins> type; authority; authorityURI; valueURI; usage; displayLabel; nameTitleGroup; altRepGroup; xlink; ID; lang; xml:lang; script; transliteration; etal</dd>
  <dd><ins><font color="brown">Subelements:</font></ins>namePart,nameIdentifier,displayForm,affiliation,role,description,etal</dd>
<dl>
<h2>MODS/name/namePart</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition</font></ins>The individual parsed parts that together make up the full name.<a href="https://www.loc.gov/standards/mods/userguide/name.md#namepart"> (resources)<a/></dd>
  <dd><ins><font color="brown">Attributes</font></ins>lang; xml:lang; script; transliteration; altRepGroup; displayLabel; type</dd>
  <dd><ins><font color="brown">Subelements:</font></ins>N/A</dd>
</dl>
<h2>MODS/name/role</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition</font></ins>Designates the relationship (role) of the entity recorded in name to the resource described in the record.<a href="https://www.loc.gov/standards/mods/userguide/name.md#role"> (resources)<a/></dd>
  <dd><ins><font color="brown">Attributes</font></ins>N/A</dd>
  <dd><ins><font color="brown">Subelements:</font></ins>roleTerm</dd>
</dl>
<h3>MODS/name/role/roleTerm</h3>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition</font></ins>Contains the textual or coded form of a relator/role.<a href="https://www.loc.gov/standards/mods/userguide/name.md#roleterm"> (resources)<a/></dd>
  <dd><ins><font color="brown">Attributes</font></ins>authority; authorityURI; valueURI; lang; xml:lang; script; transliteration; type</dd>
  <dd><ins><font color="brown">Subelements:</font></ins>N/A</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>2/9/2021</p>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<tr>
				<td><a href="IMI.advisor.md">IMI/advisors</a></td>
				<td><a href="rdf.field_linked_agent.md">field_linked_agent / local:adv</a></td>
			</tr>
			<tr>
				<td><a href="contributors.md">IMI/contributors</a></td>
				<td><a href="rdf.relators.ctb.md">RDF/dcterms:contributor/ relators:ctb</a></td>
			</tr>
			<tr>
				<td><a href="creators.md">IMI/creators</a></td>
				<td><a href="rdf.relators_aut_cre.md">RDF/dcterms:contributor/ relators:aut OR relators:cre </a></td>
			</tr>
			<tr>
				<td><a href="department.md">IMI/department</a></td>
				<td><a href="RDF.schema.department.md">RDF/schema:department</a></td>
			</tr>
			<tr>
				<td><a href="funding_sources.md">IMI/funding_sources</a></td>
				<td><a href="rdf.p60451.md">RDF/rdau:P60451</a></td>
			</tr>
	</table>
</dl>
</body>
</html>