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

<h1>language</h1> 
<dl>
  <dt><b>Description</b></dt>
  <dd><ins><font color="brown">ARMINDA Use:</font></ins>  the non-English language of the source content being described : applies to textual or spoken word (linguistic) content).  </dd>
  <dd><ins><font color="brown">Obligation:</font></ins>  Required, if applicable</dd>
  <dd><ins><font color="brown">Repeatable:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Public Field:</font></ins> Yes</dd>
  <dd><ins><font color="brown">Front-end name:</font></ins> Language</dd>
  <dd><ins><font color="brown">Syntax/Formatting:</font></ins>English language name of language
</dd>
  <dd><ins><font color="brown">Recommended Controlled Vocabulary:</font></ins>MARC Standard language code list, or spoken language spelling of language </dd>
  
  <dd><ins><font color="brown">Notes: </font></ins>
	<ul>
		<li>For multilingual material, include all languages, including English</li>
		<li>For specific use case, see Mastersheet guidelines.</li>
		<li>May use phonetic spelling of language if non-Latain characters are used</li>
		<li>Newspapers indicate language of content, including English language</li>
		<li>Newspapers metadata generated in TWIG.</li>
	</ul>
	</dd>
  <dd><font color="blue"><i>Field Changes: </i></font>N/A</dd>
</dl>
<dl>
    <dt><b>Location</b></dt>
		<dd> <ins><font color="brown">MODS XPath </font></ins> /mods/language/languageTerm/@type="text"</dd>
		<dd> <ins><font color="brown">RDF XPath</font></ins>/rdf:RDF/rdf:Description/dcterms:language</dd>
		<dd> <ins><font color="brown">Solr Field(s)</font></ins>
			<ul>
				<li>mods_language_languageTerm_text_ms: mods_language_languageTerm_text_ms(string)</li>
				<li>mods_language_languageTerm_code_ms: mods_language_languageTerm_code_ms(string)</li>
				<li>mods_language_languageTerm_code_authority_iso639-2b_ms: mods_language_languageTerm_code_authority_iso639-2b_ms(string)</li>
			</ul>
		</dd>
</dl>
<dl>
	<dt>IMI to MODS</dt>
		<dd>&lt;language&gt;&lt;languageTerm type="text"&gt;{{jsonize(cells["language"].value).replace('null', '')}}&lt;/languageTerm&gt;&lt;/language&gt;</dd>
</dl>
<dl>
	<dt>IMI to RDF</dt>
		<dd>&lt;dcterms:language&gt;{{jsonize(cells["language"].value).replace('null', '')}}&lt;/dcterms:language&gt;</dd>
</dl>
</dl>
	<p><font color="red"><i>Last Updated: </i></font>12/10/2020</p>
</dl>
<table>
   <tr>
    <td><a href="language.md">language</a></td>
    <td><a href="mods.language.languageTerm.md">language/languageTerm</a></td>
    <td><a href="rdf.language.md">dcterms:language</a></td>
  </tr>
</table>
</body>
</html>