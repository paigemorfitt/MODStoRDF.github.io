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



<h1>RDF/field_linked_agent</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: [here]</dd>
  <dd>Label:  [here]</dd>
  <dd>Domain:  [here]</dd>
  <dd>Range:  [here]</dd>
</dl>
<h2>local:adv</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: Generic "Advisor" term.</dd>
  <dd>Label:  Advisor</dd>
  <dd>Format:  local:adv:person[Lastname, Firstname]</dd>
  <dd>
		<ul>
			<li>local:adv:person:Philippe, Louis</li> 
			<li>local:adv:person:Philippe, Louis|local:adv:person:Hayden, Viola</li>
		</ul>
	</dd>
  <dd>Comment:  This is a local term.</dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
			<dd>| <a href="advisor.md">IMI/advisors</a> | <a href="mods.name.md">MODS/name/namePart</a> |</dd>
</dl>
<h2>relators:ctb</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: A person, family or organization responsible for making contributions to the resource. This includes those whose work has been contributed to a larger work, such as an anthology, serial publication, or other compilation of individual works. If a more specific role is available, prefer that, e.g. editor, compiler, illustrator <a href="http://id.loc.gov/vocabulary/relators/ctb.md">(reference)</a> </dd>
  <dd>Label:Contributor</dd>
  <dd>Format:  local:adv:person[Lastname, Firstname]</dd>
  <dd>
	<ul>
		<li>relators:ctb:person:Barrow, William,  1817-1877</li> 
		<li>relators:ctb:person:Barrow, William,  1817-1877|relators:ctb:corporate_body:Oxford World's Classic</li>
		</ul>
	</dd>
</dl>
<h2>RDF/relators:cre</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd>Definition: A person or organization responsible for the intellectual or artistic content of a resource<a href="https://id.loc.gov/vocabulary/relators/cre.html">(reference)</a></dd>
  <dd>Label: Creator</dd>
  <dd>Format:  relatorscre:person[Lastname, Firstname]</dd>
    <dd>
		<ul>
			<li>relators:cre:person:Dumas, Alexandre,  1802-1970</li> 
			<li>relators:cre:person:Dumas, Alexandre,  1802-1970|relators:cre:person:OFairbanks, Douglas, 1883-1939</li>
		</ul>
	</dd>
</dl>
<p><i>Last Updated: </i>4/30/2021</p>
<dl>
	<dt><b>Related Fields</b></dt>
			<dd>| <a href="contributors.md">IMI/contributors</a> | <a href="mods.name.md">MODS/name/namePart</a> |</dd>
			<dd>| <a href="creators.md">IMI/creators</a> | <a href="MODS.template.md">[here]</a> |</dd>
			<dd>| <a href="department.md">IMI/department</a> | <a href="MODS.template.md">[here]</a> |</dd>
</dl>
</body>
</html>


