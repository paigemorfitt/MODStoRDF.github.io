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



<h1>IMI/embargo_date</h1>
<dl>
	<dt><b>Description</b></dt>
	<dd><ins><font color="brown">ARMINDA Use:</font></ins>Date when item is released for public viewing. </dd>
	<dd><ins><font color="brown">Obligation:</font></ins> Required, if applicable</dd>
	<dd><ins><font color="brown">Repeatable:</font></ins> No</dd>
	<dd><ins><font color="brown">Public Field:</font></ins>Yes</dd>
	<dd><ins><font color="brown">Front-end Name:</font></ins>Embargo Period</dd>
	<dd><ins><font color="brown">Syntax/Formatting:</font></ins>DateFormattingGuidelinesARMINDA</dd>
	<dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>N/A</dd>
	<dd><ins><font color="brown">Notes: </font></ins>
		<ul>
			<li>[name will not change in order to allow this field to stand out from other date fields]</li>
			<li>Do not add encoding to field in IMI spreadsheet (ex: "||edtf||")</li>
		</ul>
		</dd>
	<dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins>/mods/originInfo/dateValid</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/schema:availabilityStarts</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_originInfo_dateValid_ms: mods_originInfo_dateValid_ms(string)</li>
				<li>mods_originInfo_displayLabel_ms: mods_originInfo_displayLabel_ms(string)</li>
				<li>mods_originInfo_encoding_edtf_dateValid_ms: mods_originInfo_encoding_edtf_dateValid_ms(string)</li>
				<li>mods_originInfo_encoding_w3cdtf_dateValid_ms: mods_originInfo_encoding_w3cdtf_dateValid_ms(string)</li>
			</ul>
		</dd>
<dl>
	<dt>IMI to MODS</dt>
		<dd>&lt;originInfo displayLabel="Embargo Period"&gt; &lt;dateValid&gt;%value%&lt;/dateValid&gt; &lt;dateValid encoding=""edtf""&gt;{{jsonize(cells["embargo_date"].value).replace('null', '')}}&lt;/dateValid&gt; &lt;dateValid encoding="w3cdtf"&gt;{{jsonize(cells["embargo_date"].value).replace('null', '')}}&lt;/dateValid&gt; &lt;/originInfo&gt;
</dd>
</dl>
<dl>
	<dt>IMI to RDF</dt>
		<dd>&lt;schema:availabilityStarts&gt;{{jsonize(cells["embargo_date"].value).replace('null', '')}}&lt;/schema:availabilityStarts&gt;
</dd>
</dl>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/11/2020</p>
</dl>
<dl>
	<dd><b>Related Fields</b></dd>
		<table>
			<td><a href="mods.originInfo_dateValid.md">MODS/originInfo/dateValid</a></td>
			<td><a href="rdf.availabilityStarts.md">RDF/schema:avalibilityStarts</a></td>
		</table>
</dl>
</body>
</html>