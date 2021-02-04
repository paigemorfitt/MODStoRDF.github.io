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

<h1>IMI/bucket</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>BePress inherited field which indicated the collection --bucket-- an item is associated with</dd>
  <dd><ins><font color="brown">Obligation:</font></ins> Optional</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> No</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>Free text</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
  <dd><ins><font color="brown">Notes: </font></ins>Field discontinued</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>previous name : "issue"</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
	  <dd> <ins><font color="brown">MODS XPath </font></ins>/mods/relatedItem</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_relatedItem__displayLabel_ms: mods_relatedItem__displayLabel_ms(string)</li>
				<li>mods_relatedItem_displayLabel_ms: mods_relatedItem_displayLabel_ms(string)</li>
				<li>mods_relatedItem_note_bucket_ms: mods_relatedItem_note_bucket_ms(string)</li>
				<li>mods_relatedItem_note_issue_ms: mods_relatedItem_note_issue_ms(string)</li>
			</ul>
		</dd>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/23/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.relateditem_note.md">MODS/relatedItem/note</a></td>
		</table>
</dl>
</body>
</html>