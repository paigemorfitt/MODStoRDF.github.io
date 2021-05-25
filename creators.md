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

<h1>IMI/creators</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: identifies the entity/entities primarily responsible for making the resource </dd>
  <dd>Obligation: Required, if applicable</dd>
  <dd>Repeatable: Yes</dd>
  <dd>Public Field: Yes</dd>
  <dd>Public-facing name: Creator</dd>
  <dd>Syntax/Formatting:
	<ul>
		<li>Free text / RDA 19.2</li>
		<li>Personal name: LastName, FirstName MiddleName (or Initial)</li>
		<li>For multiple authors, separate with pipe with no space trailing.</li>
	</ul>
  </dd>
  <dd>Recommended Controlled Vocabulary: LCNAF, VIAF, my.whitman, local names</dd>
  <dd>Notes: 
		<ul>
			<li>Provide as much known information as possible (either provided on resource or found elsewhere)</li>
			<li>Separate repeated terms consistently (with pipe)</li>
			<li>If names are not found in a controlled vocabulary, format personal names as Lastname , Firstname according to RDA/DACS</li>
			<li>If name(s) of creator(s) is not known, see master spreadsheet guidelines for specific details</li>
			<li>No distinguishing between Private and Corporate creators</li>
			<li>Do birthdate or death date unless to disambiguate identical named individuals</li>
			<li>Contains html, accents, and/or special characters</li>
		</ul>
	</dd>
  <dd>Field Changes: 
	<ul>
		<li>previous name : authors</li>
		<li>content moving to field_linked_agent</li>
	</ul>
  </dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.name.md">MODS/name/namePart</a> | <a href="rdf.field_linked_agent.md">RDF/local:adv</a> |
</dl>
<p><i>Last Updated: </i>05/25/2021</p>
</body>
</html>