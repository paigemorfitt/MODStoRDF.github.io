<!DOCTYPE html>
<html>
<head>

</head>
<body>

<table style="width:100%">
  <tr>
    <th>Main page</th>
	<th><a href="IMI.md">IMI Column</a></th>
    <th><a href="MODS.md">MODS Field</a></th>
    <th><a href="RDF.md">RDF Field</a></th>
  </tr>
<table>

 <h1>Arminda information page</h1> 
  
<p>Collections in Arminda. For information about IMI field content <a href="imi.field.content.md">click here</a> For a list of fields that have been removed <a href="fields.removed.md">click here</a></p>
   <tr>
    <th><a href="Archives.md">Archives</a></th>
	<th><a href="Theses.md">Theses</a></th>
    <th><a href="Scholarship.md">Scholarship</a></th>
    <th><a href="Offices&Programs.md">Offices & Programs</a></th>
	<th><a href="Newspapers.md">Newspapers</a></th>
  </tr>
 </table>
  
</table>
<p>This is an explination of metadata that is in Arminda, Islandora repository for Whitman College; moving from IMI to MODS to RDF. Below are the fields moving from IMI to MODS to RDF, fields that have been through the review process. See link for  <a href="IMItoMODS.md">IMI to MODS</a> or <a href="IMItoRDF.md">IMI to RDF</a> (both untested).</p> 
<p>See <a href="migration questions.md">Migration Questions</a> for fields that are "under review".</p>
<table>
  <tr>
    <th>IMI Column</th>
    <th>MODS field</th>
    <th>RDF field</th>
  </tr>
  <tr>
    <td><a href="abstract.md">abstract</a></td>
    <td><a href="mods.abstract.md">abstract</a></td>
    <td><a href="rdf.abstract.md">dcterms:abstract </a></td>
  </tr>
   <tr>
    <td><a href="access_condition.md">access_condition</a></td>
    <td><a href="mods.access_condition.md">accessCondition</a></td>
    <td><a href="rdf.rdau.p60496.md">rdau:P60496</a></td>
  </tr>
   <tr>
    <td><a href="IMI.advisor.md">advisors</a></td>
    <td><a href="mods.name.md">name/namePart</a></td>
    <td><a href="rdf.relators.ths.md">dcterms:contributor / relators:ths</a></td>
  </tr>
   <tr>
    <td><a href="box.md">box</a>(under review)</td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="imi.bucket.md">bucket</a></td>
    <td><a href="mods.relateditem_note.md">relatedItem/note</a></td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="campus_location.md">campus_location</a></td>
    <td><a href="mods.location-physicalLocation.md">N/A</a></td>
    <td><a href="rdf.contentLocation.md">N/A</a></td>
  </tr>
  <tr>
    <td><a href="city.md">city</a></td>
    <td><a href="mods.originInfo-place-placeTerm.md">originInfo/place/placeTerm</a></td>
    <td><a href="rdf.locationCreation.md">schema:locationCreated</a></td>
  </tr>
  <tr>
    <td><a href="cmodel.md">cmodel</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="contributors.md">contributors</a></td>
    <td><a href="mods.name.md">name/namePart</a></td>
    <td><a href="rdf.relators.ctb.md">dcterms:contributor/ relators:ctb</a></td>
  </tr>
  <tr>
    <td><a href="coverage_spatial.md">coverage_spatial</a></td>
    <td><a href="mods.subject_geographic.md">subject/geographic</a></td>
    <td><a href="rdf.spatial.md">dcterms:spatial</a></td>
  </tr>
   <tr>
    <td><a href="creators.md">creators</a></td>
    <td><a href="mods.name.md">name/namePart</a></td>
    <td><a href="rdf.relators-aut.md">dcterms:contributor/ relators:aut</a></td>
  </tr>
    <tr>
		<td><a href="date.display.md">date_display</a></td>
		<td><a href="mods.originInfo_dateOther.md">originInfo/dateOther</a></td>
		<td><a href="rdf.dcterms.date.md">dcterms:date</a></td>
  </tr>
   <tr>
    <td><a href="date.encoded.md">date_encoded</a></td>
    <td><a href="mods.originInfo_dateOther.md">originInfo/dateOther</a></td>
    <td><a href="rdf.rdau.p60527.md">rdau:P60527</a></td>
  </tr>  
   <tr>
		<td><a href="date_issued.md">date_issued</a></td>
		<td><a href="mods.originInfo_dateIssued.md">originInfo/dateIssued</a></td>
		<td><a href="rdf.valid.md">dcterms:valid</a></td>
  </tr>
  <tr>
    <td><a href="date.sort.md">date_sort</a></td>
    <td><a href="mods.originInfo.dateCreated.md">originInfo/dateCreated</a></td>
    <td><a href="rdf.dcterms.created.md">dcterms:created</a></td>
  </tr>
  <tr>
    <td><a href="department.md">department</a></td>
    <td><a href="mods.name.md">name/namePart</a></td>
    <td><a href="RDF.schema.department.md">schema:department</a></td>
  </tr>
  <tr>
    <td><a href="description.md">description</a></td>
    <td><a href="mods.abstract.md">abstract</a></td>
    <td><a href="RDF.description.md">dcterms:description</a></td>
  </tr>
  <tr>
    <td><a href="embargo_date.md">embargo_date</a></td>
    <td><a href="mods.originInfo_dateValid.md">originInfo/dateValid</a></td>
    <td><a href="rdf.availabilityStarts.md">schema:avalibilityStarts</a></td>
  </tr>
  <tr>
    <td><a href="extent.md">extent</a></td>
    <td><a href="mods.physicalDescription-extent.md">physicalDescription/extent</a></td>
    <td><a href="rdf.extent.md">dcterms:extent</a></td>
  </tr>
    <tr>
    <td><a href="filepath.md">filepath</a></td>
    <td><a href="mods.identifier.md">identifier</a></td>
    <td><a href="RDF.rdau.P61166.md">rdau:P61166</a></td>
  </tr>
    <tr>
    <td><a href="funding_source.md">funding_sources</a></td>
    <td><a href="mods.name.md">name/namePart</a></td>
    <td><a href="RDF.relators-spn.md">foaf:name / relators:spn</a></td>
  </tr>
  <tr>
    <td><a href="genre.md">genre</a></td>
    <td><a href="mods.genre.md">genre</a></td>
    <td><a href="rdf.genre.md">schema:genre</a></td>
  </tr>
     <tr>
    <td><a href="context_key.md">identifier_unique</a></td>
    <td><a href="MODS.identifier.md">identifier</a></td>
    <td><a href="RDF.identifier.md">dc:identifier</a></td>
  </tr>
  <tr>
    <td><a href="part.issue.md">issue</a></td>
    <td><a href="mods.part-detail-number.md">part/detail/number</a></td>
    <td><a href="RDF.isPartOf.md">dcterms:isPartOf</a></td>
  </tr>
   <tr>
    <td><a href="language.md">language</a></td>
    <td><a href="mods.language.languageTerm.md">language/languageTerm</a></td>
    <td><a href="rdf.language.md">dcterms:language</a></td>
  </tr>
  <tr>
    <td><a href="license_file.md">license_file</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="line_num.md">line_num</a>(under construction)</td>
    <td>N/A</td>
    <td>N/A</td>
  </tr> 
   <tr>
    <td><a href="obj_file.md">obj_file</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>  
   <tr>
    <td><a href="origin.md">origin</a></td>
    <td><a href="mods.originInfo-place-placeTerm.md">originInfo/place/placeTerm</a></td>
    <td><a href="rdf.p60523.md">rdau:P60523</a></td>
  </tr>
  <tr>
    <td><a href="parent.md">parent</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
   <tr>
    <td><a href="permanent_url.md">permanent_url</a></td>
    <td><a href="MODS.identifier.md">identifier</a></td>
    <td><a href="rdf.p60919.md">rdau:P60919</a></td>
  </tr>
  <tr>
    <td><a href="pid.md">PID</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
   <tr>
    <td><a href="provenance.md">provenance</a></td>
    <td><a href="mods.note.md">note</a></td>
    <td><a href="rdf.dcterms.provenance.md">dcterms:provenance</a></td>
	</tr>
  <tr>
    <td><a href="publication_date.md">publication_date</a></td>
    <td><a href="mods.originInfo_dateOther.md">originInfo/dateOther</a></td>
    <td><a href="rdf.issued.md">dcterms:issued</a></td>
  </tr>
   <tr>
    <td><a href="publisher.md">publisher</a></td>
    <td><a href="mods.originInfo-publisher.md">originInfo/publisher</a></td>
    <td><a href="RDF.relators-pbl.md">foaf:name / relators:pbl</a></td>
  </tr> 
   <tr>
    <td><a href="rights.md">rights_contact</a></td>
    <td><a href="mods.access_condition.md">accessCondition</a></td>
    <td><a href="rdf.accessibilityControl.md">schema:accessibilityControl</a></td>
  </tr>
    <td><a href="rights_statement.md">rights_statement</a></td>
    <td><a href="mods.access_condition.md">accessCondition</a></td>
    <td><a href="rdf.rdau.P60339.md">rdau:P60339</a></td>
  </tr>
  <tr>
    <td><a href="rowNumber.md">rowNumber</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="seq_number.md">seq_number</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="source.md">source</a></td>
    <td><a href="mods.relatedItem.part.text.md">relatedItem/part/text</a></td>
    <td><a href="rdf.dc.source.md">dcterms:source</a></td>
  </tr>
    <tr>
    <td><a href="keywords.md">subject_keywords</a></td>
    <td><a href="mods.subject.topic.md">subject/topic</a></td>
    <td><a href="rdf.subject.md">dcterms:subject</a></td>
  </tr>
  <tr>
    <td><a href="title.md">title</a></td>
    <td><a href="mods.titleInfo.title.md">titleInfo/title</a></td>
    <td><a href="rdf.title.md">dcterms:title</a></td>
  </tr>
    <tr>
    <td><a href="nonenglish_title.md">title_alternative</a></td>
    <td><a href="mods.titleInfo.title.md">titleInfo/title</a></td>
    <td><a href="rdf.alternative.md">dcterms:alternative</a></td>
  </tr>
  <tr>
    <td><a href="download_url.md">url_external</a></td>
    <td><a href="mods.location-url.md">location/url</a></td>
    <td><a href="RDF.url.md">schema:url</a></td>
  </tr>
  <tr>
    <td><a href="volume.md">volume</a></td>
    <td><a href="mods.part-detail-number.md">part/detail/number</a></td>
    <td><a href="rdf.volumeNumber.md">schema:volumeNumber</a></td>
  </tr>
  <tr>
    <td><a href="work_type.md">work_type</a></td>
    <td><a href="mods.typeOfResource.md">typeOfResource</a></td>
    <td><a href="rdf.type.md">dcterms:type</a></td>
  </tr>
  <tr>
    <td><a href="conference_year.md">year_conference</a></td>
    <td><a href="mods.originInfo_dateOther.md">originInfo/dateOther</a></td>
    <td><a href="rdf.rdau.p60526.md">rdau:P60526</a></td>
  </tr>
  <tr>
    <td><a href="graduation_year.md">year_graduation</a></td>
    <td><a href="mods.originInfo_dateOther.md">originInfo/dateOther</a></td>
    <td><a href="rdf.rdau.p60514.md">rdau:P60514</td>
  </tr>
</table>
<dl>
	<p><font color="red"><i>Last Updated: </i></font>3/4/2021</p>
</dl>
</body>
</html>