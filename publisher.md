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

<h1>IMI/publisher</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: the name of the entity that published, printed, distributed, released, issued, or produced the resource.  This may be a formal publisher, or for unpublished materials, a university department or other corporate entity.</dd>
  <dd>Obligation: Recommended, if applicable</dd>
  <dd>Repeatable: Yes* </dd>
  <dd>Public Field: Yes</dd>
  <dd>Public-facing name:Publisher</dd>
  <dd>Syntax/Formatting:Free-text</dd>
  <dd>Recommended Controlled Vocabulary:Recommended use of controlled heading (ex: LCNAF) ; if no controlled heading is present, format in similar fashion. </dd>
  <dd>Notes: 
	<ul>
		<li>*Repeatable, if applicable</li>
		<li>For collection-wide metadata, an umbrella publisher is okay (newspapers)</li>
		<li>For localized publishers, see in-house formatting</li>
		<li>Stick to what is on the resource </li>
		<li>Contains prefix: relators:pbl</li>
	</ul>
  </dd>
  <dd>Field Changes: Contnet will move to field_linked_agent</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		|<a href="mods.originInf_publisher.md">MODS/originInfo/publisher</a> | <a href="rdf.field_linked_agent.md">RDF/relators:pub</a>|
</dl>
<p><i>Last Updated: </i>05/25/2021</p>
</body>
</html>