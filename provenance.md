<!DOCTYPE html>
<html>

<body>
<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th>IMI Columns</th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="#">RDF Fields</a></th>
  </tr>
</table>



<h1>IMI/provenance</h1>
<dl>
	<dt><b>Description</b></dt>
	<dd><ins><font color="brown">ARMINDA Use:</font></ins>Contains provenance information about the object: [currently] donor information and/or when and how the object was acquired by Whitman College.</dd>
	<dd><ins><font color="brown">Obligation:</font></ins>Recommended</dd>
	<dd><ins><font color="brown">Repeatable:</font></ins>No</dd>
	<dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
	<dd><ins><font color="brown">Front-end name:</font></ins>Provenance</dd>
	<dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free text
	</dd>
	<dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
	<dd><ins><font color="brown">Notes: </font></ins>
		<ul>
			<li>Primarily used for Sheehan Collection</li>
			<li>May contain html, accents, or other special characters</li>
		</ul>
	</dd>
	<dd><font color="blue"><i>Field Changes: </i></font>Absorbed IMI/donor</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins>/mods/note</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/dcterms:provenance</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
			<li>mods_note_displayLabel_ms: mods_note_displayLabel_ms(string)</li>
			<li>mods_note_ms: mods_note_ms(string)</li>
			</ul>
		</dd>
<dl>
	<dt>IMI to MODS</dt>
		<dd>&lt;note displayLabel=""Provenance""&gt;{{jsonize(cells[""provenance""].value).replace('null', '')}} &lt;/note&gt;
</dd>
</dl>
<dl>
	<dt>IMI to RDF</dt>
		<dd>&lt;dcterms:provenance&gt;{{jsonize(cells["provenance"].value).replace('null', '')}}&lt;/dcterms:provenance&gt;</dd>
</dl>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/11/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.note.md">MODS/note</a></td>
			<td><a href="rdf.dcterms.provenance.md">RDF/dcterms:provenanc</a></td>
		</table>
</dl>
</body>
</html