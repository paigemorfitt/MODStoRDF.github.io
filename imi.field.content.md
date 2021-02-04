<!DOCTYPE html>
<html>
<head>

</head>
<body>

<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th><a href="IMI.md">IMI Columns</a></th>
    <th><a href="MODS.md">MODS Fields</a></th>
    <th><a href="RDF.md">RDF Fields</a></th>
  </tr>
<table>

 <h1>Arminda information page</h1> 

<dd><ins><font color="brown">Fields that are repeatable </font></ins>
	<ul>
		 <li>IMI/contributors -- MODS/name/namePart -- RDF/[foaf:name]/[relators:ctb] </li>
		 <li>IMI/creators -- MODS/name/namePart -- RDF/[foaf:name]/[relators:aut] </li>
		 <li>IMI/language -- MODS/language/languageTerm -- RDF/dcterms:language </li>
		 <li>IMI/subject_keywords -- MODS/subject/topic -- RDF/dcterms:subject </li>
		 <li>IMI/coverage_spatial -- MODS/subject/geographic -- RDF/dcterms:spatial</li>
	</ul>
</dd> 
<dd><ins><font color="brown">Fields with a Controlled Vocabulary</font></ins>
	<ul>
		<li>IMI/access_condition -- MODS/accessCondition -- RDF/rdau:P60496</li>
		 <li>IMI/contributors -- MODS/name/namePart -- RDF/[foaf:name]/[relators:ctb] </li>
		 <li>IMI/creators -- MODS/name/namePart -- RDF/[foaf:name]/[relators:aut] </li>
		 <li>IMI/language -- MODS/language/languageTerm -- RDF/dcterms:language </li>
		 <li>IMI/subject_keywords -- MODS/subject/topic -- RDF/dcterms:subject </li>
		 <li>IMI/work_type -- MODS/typeOfResource -- RDF/dcterms:type </li>
		 <li>IMI/[MODS/RecordSeries] -- MODS/relatedItem/part/text -- RDF/rdau:P60101 </li>
		 <li>IMI/[MODS/RecordSeriesID] -- MODS/location/holdingSimple/copyInformation/subLocation -- RDF/rdau:P60348 </li>
		 <li>IMI/[MODS/Suceeding Frequency] -- MODS/relatedItem/originInfo/frequency -- RDF/rdau:P60583 </li>
		 <li>IMI/coverage_spatial -- MODS/subject/geographic -- RDF/dcterms:spatial</li>
	</ul>
</dd> 
<dd><ins><font color="brown">Fields with html, accents, or other special characters</font></ins>
	<ul>
		<li>IMI/abstract -- MODS/abstract -- RDF/dcterms:abstract </li>
		<li>IMI/contributors -- MODS/name/namePart -- RDF/[foaf:name]/[relators:ctb] </li>
		<li>IMI/creators -- MODS/name/namePart -- RDF/[foaf:name]/[relators:aut]</li>
		<li>IMI/date_display -- MODS/originInfo/dateOther -- RDF/dcterms:date</li>
		<li>IMI/language -- MODS/language/languageTerm -- RDF/dcterms:language </li>
		<li>IMI/provenance -- MODS/note -- RDF/dcterms:provenance </li>
		<li>IMI/subject_keywords -- MODS/subject/topic -- RDF/dcterms:subject </li>
		<li>IMI/coverage_spatial -- MODS/subject/geographic -- RDF/dcterms:spatial</li>
	</ul>
</dd> 
<dl>
<p><li>IMI/[here] -- MODS/[here] -- RDF/[[here]</li></p>
	<p><font color="red"><i>Last Updated: </i></font>2/1/2021</p>
</dl>
</body>
</html>