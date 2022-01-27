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
 <p>Due to complexity of field, there is no one field_linked_agent to RDF mapping. Instead, it is parsed out by Role.</p>
</dl>
<h2>local:adv</h2>
<table>
<tr>
	<th>Definition</th>
	<td>Generic "Advisor" term.</td>
</tr>
<tr>
	<th>Label</th>
	<td>Advisor</td>
</tr>
<tr>
	<th>Prefix</th>
	<td>local:adv:peson</td>
</tr>
<tr>
	<th>Examples</th>
	<td>
		<li>local:adv:person:Philippe, Louis</li> 
		<li>local:adv:person:Philippe, Louis|local:adv:person:Hayden, Viola</li>
	</td>
</tr>
</table>
<dl>
	<dt><b>Related Fields</b></dt>
			| <a href="advisor.md">IMI/advisor</a> | 
			<a href="DrupalField.md">Drupal Field</a> | 
			<a href="mods.name.md">MODS/name/namePart</a> |
</dl>
<h2>local:dpt</h2>
<table>
<tr>
	<th>Definition</th>
	<td>College division in which the item is categorized</td>
</tr>
<tr>
	<th>Label</th>
	<td>Major Department or Program</td>
</tr>
<tr>
	<th>Prefix</th>
	<td>local:dpt:corporate_body</td>
</tr>
<tr>
	<th>Examples</th>
	<td>
		<li>local:dpt:corporate_body:Whitman College. Religion Department</li> 
		<li>local:dpt:corporate_body:Whitman College. Geology Department|local:dpt:corporate_body:Whitman College. Physics Departmen</li>
	</td>
</tr>
</table>
<dl>
	<dt><b>Related Fields</b></dt>
			<dd>| <a href="department.md">IMI/department</a> | 
			<a href="DrupalField.md">Drupal Field</a> | 
			<a href="mods.name.md">MODS/name/namePart</a> |</dd>
</dl>
<h2>relators:ctb</h2>
<table>
<tr>
	<th>Definition</th>
	<td>A person, family or organization responsible for making contributions to the resource. This includes those whose work has been contributed to a larger work, such as an anthology, serial publication, or other compilation of individual works. If a more specific role is available, prefer that, e.g. editor, compiler, illustrator <a href="http://id.loc.gov/vocabulary/relators/ctb.html">(reference)</a> </td>
</tr>
<tr>
	<th>Label</th>
	<td>Contributor</td>
</tr>
<tr>
	<th>Prefix</th>
	<td>relators:ctb:person[Lastname, Firstname] ; relators:ctb:family[Family name] ; relators:ctb:corporate_body[Corporate Body name]</td>
</tr>
<tr>
	<th>Note</th>
	<td>Due to "dpt" being coded in relator as Depositor, we are are removing that relators term in favor of dpt being Department. (The other option was changing the code to dpx)</td>
</tr>
<tr>
	<th>Examples</th>
	<td>
		<li>relators:ctb:person:Barrow, William,  1817-1877</li> 
		<li>relators:ctb:person:Barrow, William,  1817-1877|relators:ctb:corporate_body:Oxford World's Classic</li>
	</td>
</tr>
</table>
	</dd>
<dl>
	<dt><b>Related Fields</b></dt>
			| <a href="contributors.md">IMI/contributors</a> | 
			<a href="DrupalField.md">Drupal Field</a> | 
			<a href="mods.name.md">MODS/name/namePart</a> |
</dl>
<h2>relators:cre</h2>
<table>
<tr>
	<th>Definition</th>
	<td>A person or organization responsible for the intellectual or artistic content of a resource<a href="https://id.loc.gov/vocabulary/relators/cre.html">(reference)</a></td>
</tr>
<tr>
	<th>Label</th>
	<td>Creator</td>
</tr>
<tr>
	<th>Prefix</th>
	<td>relators:cre:person{Last name, First name] ; relators:cre:family[Family name] ; relators:cre:corporate_body[Corporate Body name]</td>
</tr>
<tr>
	<th>Examples</th>
	<td>
		<li>relators:cre:person:Dumas, Alexandre,  1802-1970</li> 
		<li>relators:cre:person:Dumas, Alexandre,  1802-1970|relators:cre:person:Fairbanks, Douglas, 1883-1939</li>
	</td>
</tr>
</table>
<dl>
	<dt><b>Related Fields</b></dt>
						| <a href="creators.md">IMI/creators</a> |
						<a href="DrupalField.md">Drupal Field</a> |
						<a href="mods.name.md">MODS/name/namePart</a> |
</dl>
<h2>relators:pbl</h2>
<table>
<tr>
	<th>Definition</th>
	<td>A person or organization responsible for publishing, releasing, or issuing a resource. <a href="http://id.loc.gov/vocabulary/relators/pbl.html">(reference)</a></td>
</tr>
<tr>
	<th>Label</th>
	<td>Publisher</td>
</tr>
<tr>
	<th>Prefix</th>
	<td>relators:pbl:person[Last name, First name] ; relators:pbl:corporate_body[Corporate Body name]</td>
</tr>
<tr>
	<th>Examples</th>
	<td>
		<li>relators:pbl:company: Le Siècle (newspaper)</li> 
		<li>relators:pbl:person: Kanter, Albert Lewis, 1897-1973|relators:pbl:corporate_body:Elliot Publishing Company</li>
	</td>
</tr>
</table>
<dl>
	<dt><b>Related Fields</b></dt>
			| <a href="publisher.md">IMI/publisher</a> | 
			<a href="DrupalField.md">Drupal Field</a> |
			<a href="mods.originInfo_publisher.md">MODS/originInfo/publisher</a>
</dl>
<p><i>Last Updated: </i>09/30/2021</p>
</body>
</html>



