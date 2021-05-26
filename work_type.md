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

<h1>IMI/work_type</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Basic conceptual indication of the kind of object being described, using broad terms. </dd>
  <dd>Obligation: Required</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: No</dd>
  <dd>Syntax/Formatting:Free text</dd>
  <dd>Recommended Controlled Vocabulary:Yes [Collection; Dataset; Image; Interactive Resource; Moving Image; Physical Object; Service; Software; Sound; Still Image; Text]</dd>
  <dd>Notes: 
	<ul>
		<li>This information should relate to the original object, not the digitized surrogate</li>
		<li>If more than one present, record each value in new field</li>
		<li>Expectation: one type is sufficient for most object, however specific collections may have more guidance on particular cases</li>
		<li>If a term does not fit, bring to Metadata Working Group</li>
		<li>Born-digital uses this field for theming</li>
		<li>Newspaper generates field in TWIG</li>
		<li>We need this field in order to make our display work</li>
	</ul>
  </dd>
  <dd><i>Field Changes: </i> Absorbed content from IMI/type_of_work</dd>
</dl>
<dd><b>Related Fields</b></dd>
	| <a href="mods.typeOfResource.md">MODS/typeOfResource</a> | <a href="rdf.type.md">RDF/dcterms:type</a> |
</dl>
</body>
</html>