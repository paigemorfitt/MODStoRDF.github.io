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
  <dd><ins>Definition: </ins>[here]</dd>
  <dd><ins>Label: </ins> [here]</dd>
  <dd><ins>Domain: </ins> [here]</dd>
  <dd><ins>Range: </ins> [here]</dd>
</dl>
<h2>local:adv</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins>Definition: </ins>Generic "Advisor" term.</dd>
  <dd><ins>Label: </ins> Advisor</dd>
  <dd><ins>Format: </ins> local:adv:person[Lastname, Firstname]</dd>
  <dd>
  <ul>
				<li>local:adv:person:Philippe, Louis</li> 
				<li>locas:adv:person:Philippe, Louis|local:adv:person:Hayden, Viola</li>
			</ul>
	</dd>
  <dd><ins>Comment: </ins> This is a local term.</dd>
</dl>
<h2>relators:ctb</h2>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">Definition: </font></ins>A person, family or organization responsible for making contributions to the resource. This includes those whose work has been contributed to a larger work, such as an anthology, serial publication, or other compilation of individual works. If a more specific role is available, prefer that, e.g. editor, compiler, illustrator <a href="http://id.loc.gov/vocabulary/relators/ctb.md">(reference)</a></font> </dd>
  <dd><ins><font color="brown">Label:</font></ins>Contributor</dd>
  <dd><ins>Format: </ins> local:adv:person[Lastname, Firstname]</dd>
  <dd>
  <ul>
				<li>relators:ctb:person:Barrow, William,  1817-1877</li> 
				<li>relators:ctb:person:Barrow, William,  1817-1877|relators:ctb:corporate_body:Oxford World's Classic</li>
			</ul>
	</dd>
</dl>
<p><i>Last Updated: </i>4/23/2021</p>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<tr>
				<td><a href="IMI.advisor.md">IMI/advisors</a></td>
				<td><a href="mods.name.md">MODS/name/namePart</a></td>
			</tr>
			<tr>
				<td><a href="contributors.md">IMI/contributors</a></td>
			</tr>
			<tr>
				<td><a href="creators.md">IMI/creators</a></td>
			</tr>
			<tr>
				<td><a href="department.md">IMI/department</a></td>
			</tr>
			<tr>
				<td><a href="funding_sources.md">IMI/funding_sources</a></td>
			</tr>
	</table>
</dl>
</body>
</html>