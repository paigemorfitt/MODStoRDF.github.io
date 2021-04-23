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
  <dd><ins>ARMINDA Use: </ins>BePress inherited field which indicated the collection --bucket-- an item is associated with</dd>
  <dd><ins>Obligation: </ins> Optional</dd>
  <dd><ins>Repeatable: </ins> No</dd>
  <dd><ins>Public Field: </ins> No</dd>
  <dd><ins>Syntax/Formatting: </ins>Free text</dd>
  <dd><ins>Recommended Controlled Vocabulary: </ins>N/A</dd>
  <dd><ins>Notes: </ins>
	<ul>
		<li>Field discontinued. Not being migrated to RDF. Not being removed from Spreadsheets.  Will not be ingested into Islandora 8.</li>
		<li>Content now spells out the full collection name.</li>
	</ul>
	</dd>
  <dd><i>Field Changes: </i>previous name : "issue".</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
	  <dd> <ins>MODS XPath </ins>/mods/relatedItem</dd>
		<dd> <ins>Solr Field(s)</ins>
			<ul>
				<li>mods_relatedItem__displayLabel_ms</li>
				<li>mods_relatedItem_displayLabel_ms</li>
				<li>mods_relatedItem_note_bucket_ms</li>
				<li>mods_relatedItem_note_issue_ms</li>
			</ul>
		</dd>
</dl>
	<p><i>Last Updated: </i>4/23/2021</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.relateditem_note.md">MODS/relatedItem/note</a></td>
		</table>
</dl>
</body>
</html>