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
  
<p>Collections in Arminda. For information about IMI field content <a href="imi.field.content.md">click here</a> For a list of fields that have been removed <a href="fields.removed.md">click here</a>. List of <a href="Islandora.8.terms.md">Terms</a> is in progress.</p>
   <tr>
    <th><a href="Archives.md">Archives</a></th>
	<th><a href="Theses.md">Theses</a></th>
    <th><a href="scholarship.md">Scholarship</a></th>
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
    <td><a href="abstract.md" class ="magic-button" title="ARMINDA Use: A summary of the resource, primarily used with scholarship objects">abstract</a></td>
    <td><a href="mods.abstract.md" class ="magic-button" title="Definition: A summary of the content of the resource" >abstract</a></td>
    <td><a href="rdf.abstract.md" class ="magic-button" title="Definition: A summary of the resource">dcterms:abstract </a></td>
  </tr>
   <tr>
    <td><a href="access_condition.md" class ="magic-button" title="ARMINDA Use: Field that indicates item may be accessed by only current Whitman affiliates (netID holders)" >access_condition</a></td>
    <td><a href="mods.access_condition.md" class ="magic-button" title="Definition: Information about restrictions imposed on access to a resource.">accessCondition</a></td>
    <td><a href="rdf.rdau.p60496.md" class ="magic-button" title="Definition: Relates a resource to limitations placed on access to a resource">rdau:P60496</a></td>
  </tr>
   <tr>
    <td><a href="advisor.md" class ="magic-button" title="ARMINDA Use: A person under whose supervision a student develops and/or presents an academic paper or project, including theses and capstone projects.">advisors</a></td>
    <td><a href="mods.name.md" class ="magic-button" title="Definition: The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource ">name/namePart</a></td>
    <td><a href="rdf.field_linked_agent.md" class ="magic-button" title="Definition: Generic Advisor term.">local:adv</a></td>
  </tr>
  <tr>
    <td><a href="imi.bucket.md" class ="magic-button" title="ARMINDA Use: BePress inherited field which indicated the collection --bucket-- an item is associated with">bucket</a></td>
    <td><a href="mods.relateditem_note.md" class ="magic-button" title="Definition: Information that identifies other resources related to the one being described">relatedItem/note</a></td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="cmodel.md" class ="magic-button" title="Tells what content model the file is -- audio, image.etc;  tells what type of file for Islandora to expect. ">cmodel</a></td>
    <td>N/A</td>
    <td><a href="rdf.pcdm_memberOf.md" class ="magic-button" title="Definition: Links from an Object or Collection to a containing Object or Collection.">pcdm:memberOf</a></td>
  </tr>
  <tr>
    <td><a href="contributors.md" class ="magic-button" title="identifies the entity or entities that made contributions to the creation of the resource but whose contributions are secondary to any person or organization specified in the creator(s) field. ">contributors</a></td>
    <td><a href="mods.name.md" class ="magic-button" title="Definition: The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource">name/namePart</a></td>
    <td><a href="rdf.field_linked_agent.md" class ="magic-button" title="identifies the entity or entities that made contributions to the creation of the resource but whose contributions are secondary to any person or organization specified in the creator(s) field. ">local:adv</a></td>
  </tr>
  <tr>
    <td><a href="coverage_spatial.md" class ="magic-button" title="ARMINDA Use: Geographic subject headings">coverage_spatial</a></td>
    <td><a href="mods.subject_geographic.md" class ="magic-button" title="Definition: A term or phrase representing the primary topic(s) on which a work is focused">subject/geographic</a></td>
    <td><a href="rdf.dcterms_spatial.md" class ="magic-button" title="Definition: Spatial characteristics of the resource.">dcterms:spatial</a></td>
  </tr>
   <tr>
    <td><a href="creators.md" class ="magic-button" title="ARMINDA Use: identifies the entity/entities primarily responsible for making the resource">creators</a></td>
    <td><a href="mods.name.md" class ="magic-button" title="Definition: The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource">name/namePart</a></td>
    <td><a href="rdf.field_linked_agent.md" class ="magic-button" title="Definition: identifies the entity/entities primarily responsible for making the resource ">local:adv</a></td>
  </tr>
    <tr>
		<td><a href="date.display.md" class ="magic-button" title="ARMINDA Use: Date of creation or publication of original object in human readable format for public viewing">date_display</a></td>
		<td><a href="mods.originInfo_dateOther.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/dateOther</a></td>
		<td><a href="rdf.rdau.p60527.md" class ="magic-button" title="Definition: Relates a resource to a timespan that is the earliest associated with a resource">rdau:P60527</a></td>
  </tr>
   <tr>
    <td><a href="date.encoded.md" class ="magic-button" title="ARMINDA Use: Encoded date of creation or publication of the original object with qualifiers and date ranges when applicable">date_encoded</a></td>
		<td><a href="mods.originInfo_dateOther.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/dateOther</a></td>
    <td><a href="rdf.dcterms.created.md" class ="magic-button" title="Definition: Date of creation of the resource. ">dcterms:created</a></td>
  </tr>  
   <tr>
		<td><a href="date_issued.md" class ="magic-button" title="ARMINDA Use: Issue date of the newspaper">date_issued</a></td>
		<td><a href="mods.originInfo_dateIssued.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/dateIssued</a></td>
		<td><a href="rdf.dcterms.issued.md" class ="magic-button" title="Definition: Date of formal issuance of the resource.">dcterms:issued</a></td>
  </tr>
  <tr>
    <td><a href="date.sort.md" class ="magic-button" title="ARMINDA Use: Encoded date of creation or publication of the original object that strips out qualifiers and date ranges to allow us to sort on date in ARMINDA">date_sort</a></td>
    <td><a href="mods.originInfo.dateCreated.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/dateCreated</a></td>
    <td><a href="rdf.dcterms.date.md" class ="magic-button" title="Definition: A point or period of time associated with an event in the lifecycle of the resource.">dcterms:date</a></td>
  </tr>
  <tr>
    <td><a href="department.md" class ="magic-button" title="ARMINDA Use: College division in which the item is categorized">department</a></td>
    <td><a href="mods.name.md" class ="magic-button" title="Definition: The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource">name/namePart</a></td>
    <td><a href="rdf.field_linked_agent.md" class ="magic-button" title="Definition: College division in which the item is categorized">local:adv</a></td>
  </tr>
  <tr>
    <td><a href="description.md" class ="magic-button" title="Definition: An account of the resource, primarily used for archival objects">description</a></td>
    <td><a href="mods.abstract.md" class ="magic-button" title="Definition: A summary of the content of the resource">abstract</a></td>
    <td><a href="RDF.description.md" class ="magic-button" title="An account of the resource.">dcterms:description</a></td>
  </tr>
  <tr>
    <td><a href="embargo_date.md" class ="magic-button" title="ARMINDA Use:Date when item is released for public viewing.">embargo_date</a></td>
    <td><a href="mods.originInfo_dateValid.md" class ="magic-button" title="Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource. ">originInfo/dateValid</a></td>
    <td><a href="rdf.schema.availabilityStarts.md" class ="magic-button" title="Definition: The beginning of the availability of the product or service included in the offer.">schema:avalibilityStarts</a></td>
  </tr>
  <tr>
    <td><a href="extent.md" class ="magic-button" title="[definition]">extent</a></td>
    <td><a href="mods.physicalDescription.md" class ="magic-button" title="[definition]">physicalDescription/extent</a></td>
    <td><a href="rdf.dcterms.extent.md" class ="magic-button" title="[definition]">dcterms:extent</a></td>
  </tr>
  <tr>
	<td><a href="" class ="magic-button" title="[definition]">file_display_hint</a></td>
	<td>N/A</td>
	<td><a href="" class ="magic-button" title="[definition]">[unknown]</a></td>
  </tr>
  <tr>
    <td><a href="field_linked_agent.md" class ="magic-button" title="[definition]">field_linked_agent</a></td>
    <td>N/A</td>
    <td><a href="a href="rdf.field_linked_agent.md" class ="magic-button" title="[definition]">[unknown]</a></td>
  </tr>
  <tr>
	<td><a href="" class ="magic-button" title="[definition]">field_weight</a></td>
	<td>N/A</td>
	<td><a href="" class ="magic-button" title="[definition]">[unknown]</a></td>
  </tr>
  <tr>
	<td><a href="" class ="magic-button" title="[definition]">file</a></td>
	<td>N/A</td>
	<td><a href="" class ="magic-button" title="[definition]">[unknown]</a></td>
  </tr>
    <tr>
    <td><a href="filepath.md" class ="magic-button" title="[definition]">filepath</a></td>
    <td><a href="identifier.md" class ="magic-button" title="[definition]">identifier</a></td>
    <td>N/A</td>
  </tr>
    <tr>
    <td><a href="funding_sources.md" class ="magic-button" title="[definition]">funding_sources</a></td>
    <td><a href="mods.name.md" class ="magic-button" title="[definition]">name/namePart</a></td>
    <td><a href="rdf.p60451.md" class ="magic-button" title="[definition]">rdau:P60451</a></td>
  </tr>
  <tr>
    <td><a href="genre.md" class ="magic-button" title="[definition]">genre</a></td>
    <td><a href="mods.genre.md" class ="magic-button" title="[definition]">genre</a></td>
    <td><a href="rdf.genre.md" class ="magic-button" title="[definition]">schema:genre</a></td>
  </tr>
  <tr>
	<td><a href="" class ="magic-button" title="[definition]">id</a></td>
	<td>N/A</td>
	<td><a href="" class ="magic-button" title="[definition]">[unknown]</a></td>
  </tr>
     <tr>
    <td><a href="context_key.md" class ="magic-button" title="[definition]">identifier_unique</a></td>
    <td><a href="MODS.identifier.md" class ="magic-button" title="[definition]">identifier</a></td>
    <td><a href="RDF.identifier.md" class ="magic-button" title="[definition]">dc:identifier</a></td>
  </tr>
  <tr>
    <td><a href="part.issue.md" class ="magic-button" title="[definition]">issue</a></td>
    <td><a href="mods.part-detail-number.md" class ="magic-button" title="[definition]">part/detail/number</a></td>
    <td><a href="RDF.isPartOf.md" class ="magic-button" title="[definition]">dcterms:isPartOf</a></td>
  </tr>
   <tr>
    <td><a href="language.md" class ="magic-button" title="[definition]">language</a></td>
    <td><a href="mods.language.languageTerm.md" class ="magic-button" title="[definition]">language/languageTerm</a></td>
    <td><a href="rdf.language.md" class ="magic-button" title="[definition]">dcterms:language</a></td>
  </tr>
  <tr>
    <td><a href="license_file.md" class ="magic-button" title="[definition]">license_file</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="line_num.md" class ="magic-button" title="[definition]">line_num</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr> 
   <tr>
    <td><a href="obj_file.md" class ="magic-button" title="[definition]">obj_file</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>  
   <tr>
    <td><a href="origin.md" class ="magic-button" title="[definition]">origin</a></td>
    <td><a href="mods.originInfo-place-placeTerm.md" class ="magic-button" title="[definition]">originInfo/place/placeTerm</a></td>
    <td><a href="rdf.p60523.md" class ="magic-button" title="[definition]">rdau:P60523</a></td>
  </tr>
  <tr>
	<td><a href="" class ="magic-button" title="[definition]">parent_id</a></td>
	<td>N/A</td>
	<td><a href="" class ="magic-button" title="[definition]">[unknown]</a></td>
  </tr>
  <tr>
    <td><a href="parent.md" class ="magic-button" title="[definition]">parent</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
   <tr>
    <td><a href="permanent_url.md" class ="magic-button" title="[definition]">permanent_url</a></td>
    <td><a href="MODS.identifier.md" class ="magic-button" title="[definition]">identifier</a></td>
    <td><a href="rdf.p60919.md" class ="magic-button" title="[definition]">rdau:P60919</a></td>
  </tr>
  <tr>
    <td><a href="pid.md" class ="magic-button" title="[definition]">PID</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
   <tr>
    <td><a href="provenance.md" class ="magic-button" title="[definition]">provenance</a></td>
    <td><a href="mods.note.md" class ="magic-button" title="[definition]">note</a></td>
    <td><a href="rdf.dcterms.provenance.md" class ="magic-button" title="[definition]">dcterms:provenance</a></td>
	</tr>
   <tr>
    <td><a href="publisher.md" class ="magic-button" title="[definition]">publisher</a></td>
    <td><a href="mods.originInfo-publisher.md" class ="magic-button" title="[definition]">originInfo/publisher</a></td>
    <td><a href="rdf.field_linked_agent.md" class ="magic-button" title="[definition]">relators:pbl</a></td>
  </tr> 
   <tr>
    <td><a href="rights.md" class ="magic-button" title="[definition]">rights_contact</a></td>
    <td><a href="mods.access_condition.md" class ="magic-button" title="[definition]">accessCondition</a></td>
    <td><a href="rdf.accessibilityControl.md" class ="magic-button" title="[definition]">schema:accessibilityControl</a></td>
  </tr>
    <td><a href="rights_statement.md" class ="magic-button" title="[definition]">rights_statement</a></td>
    <td><a href="mods.access_condition.md" class ="magic-button" title="[definition]">accessCondition</a></td>
    <td><a href="rdf.rdau.P60339.md" class ="magic-button" title="[definition]">rdau:P60339</a></td>
  </tr>
  <tr>
    <td><a href="rowNumber.md" class ="magic-button" title="[definition]">rowNumber</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="seq_number.md" class ="magic-button" title="[definition]">seq_number</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="source.md" class ="magic-button" title="[definition]">source</a></td>
    <td><a href="mods.relatedItem.part.text.md" class ="magic-button" title="[definition]">relatedItem/part/text</a></td>
    <td><a href="rdf.dc.source.md" class ="magic-button" title="[definition]">dcterms:source</a></td>
  </tr>
    <tr>
    <td><a href="keywords.md" class ="magic-button" title="[definition]">subject_keywords</a></td>
    <td><a href="mods.subject.topic.md" class ="magic-button" title="[definition]">subject/topic</a></td>
    <td><a href="rdf.subject.md" class ="magic-button" title="[definition]">dcterms:subject</a></td>
  </tr>
  <tr>
    <td><a href="title.md" class ="magic-button" title="[definition]">title</a></td>
    <td><a href="mods.titleInfo.title.md" class ="magic-button" title="[definition]">titleInfo/title</a></td>
    <td><a href="rdf.title.md" class ="magic-button" title="[definition]">dcterms:title</a></td>
  </tr>
    <tr>
    <td><a href="nonenglish_title.md" class ="magic-button" title="[definition]">title_alternative</a></td>
    <td><a href="mods.titleInfo.title.md" class ="magic-button" title="[definition]">titleInfo/title</a></td>
    <td><a href="rdf.alternative.md" class ="magic-button" title="[definition]">dcterms:alternative</a></td>
  </tr>
  <tr>
	<td><a href="" class ="magic-button" title="[definition]">url_alias</a></td>
	<td>N/A</td>
	<td><a href="" class ="magic-button" title="[definition]">[unknown]</a></td>
  </tr>
  <tr>
    <td><a href="download_url.md" class ="magic-button" title="[definition]">url_external</a></td>
    <td><a href="mods.location-url.md" class ="magic-button" title="[definition]">location/url</a></td>
    <td><a href="RDF.url.md" class ="magic-button" title="[definition]">schema:url</a></td>
  </tr>
  <tr>
    <td><a href="volume.md" class ="magic-button" title="[definition]">volume</a></td>
    <td><a href="mods.part-detail-number.md" class ="magic-button" title="[definition]">part/detail/number</a></td>
    <td><a href="rdf.volumeNumber.md" class ="magic-button" title="[definition]">schema:volumeNumber</a></td>
  </tr>
  <tr>
    <td><a href="work_type.md" class ="magic-button" title="[definition]">work_type</a></td>
    <td><a href="mods.typeOfResource.md" class ="magic-button" title="[definition]">typeOfResource</a></td>
    <td><a href="rdf.type.md" class ="magic-button" title="[definition]">dcterms:type</a></td>
  </tr>
  <tr>
    <td><a href="graduation_year.md" class ="magic-button" title="[definition]">year_graduation</a></td>
    <td><a href="mods.originInfo_dateOther.md" class ="magic-button" title="[definition]">originInfo/dateOther</a></td>
    <td><a href="rdf.rdau.p60514.md" class ="magic-button" title="[definition]">rdau:P60514</td>
  </tr>
</table>
<dl>
	<p><i>Last Updated: </i>05/24/2021</p>
</dl>
</body>
</html>