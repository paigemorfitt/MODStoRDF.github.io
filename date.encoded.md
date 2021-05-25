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

<h1>IMI/date_encoded</h1>
<dl>
  <dt><b>Description</b></dt>
  <dd>ARMINDA Use: Encoded date of creation or publication of the original object with qualifiers and date ranges when applicable</dd>
  <dd>Obligation: Required, if applicable</dd>
  <dd>Repeatable: No</dd>
  <dd>Public Field: No</dd>
  <dd>Syntax/Formatting: EDTF according to DateFormattingGuidelinesARMINDA </dd>
  <dd>Recommended Controlled Vocabulary: N/A</dd>
  <dd>Notes: Currently this is maintained in order to have an encoded date that is as granular as possible within edtf</dd>
  <dd>Field Changes: 
	<ul>
		<li>Previous name oai_harvester_date</li>
		<li>Machine name:field_edtf_date_created</li>
	</ul>
  </dd>
</dl>
<dl>
	<dt><b>Related Fields</b></dt>
		| <a href="mods.originInfo_dateOther.md">MODS/originInfo/dateOther</a> | <a href="rdf.dcterms.created.md">dcterms:created</a> |
</dl>
<p><i>Last Updated: </i>05/05/2021</p>
</body>
</html>