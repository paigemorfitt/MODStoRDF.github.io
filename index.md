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
  
<p>Collections in Arminda. For information about IMI field content <a href="imi.field.content.md">click here</a> For a list of fields that have been removed <a href="fields.removed.md">click here</a>. List of <a href="Islandora.8.terms.md">Terms and Facts</a> (in progress).</p>
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
    <td><a href="abstract.md" class ="magic-button" title="ARMINDA Use: A summary of the resource, primarily used with scholarship objects">field_abstract</a></td>
    <td><a href="mods.abstract.md" class ="magic-button" title="Definition: A summary of the content of the resource" >abstract</a></td>
    <td><a href="rdf.abstract.md" class ="magic-button" title="Definition: A summary of the resource">dcterms:abstract </a></td>
  </tr>
   <tr>
    <td><a href="access_condition.md" class ="magic-button" title="ARMINDA Use: Field that indicates item may be accessed by only current Whitman affiliates (netID holders)" >field_limited_access</a></td>
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
    <td><a href="cmodel.md" class ="magic-button" title="Tells what content model the file is -- audio, image.etc;  tells what type of file for Islandora to expect. ">field_model</a></td>
    <td>N/A</td>
    <td><a href="rdf.pcdm_memberOf.md" class ="magic-button" title="Definition: Links from an Object or Collection to a containing Object or Collection.">pcdm:memberOf</a></td>
  </tr>
  <tr>
    <td><a href="contributors.md" class ="magic-button" title="identifies the entity or entities that made contributions to the creation of the resource but whose contributions are secondary to any person or organization specified in the creator(s) field. ">contributors</a></td>
    <td><a href="mods.name.md" class ="magic-button" title="Definition: The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource">name/namePart</a></td>
    <td><a href="rdf.field_linked_agent.md" class ="magic-button" title="identifies the entity or entities that made contributions to the creation of the resource but whose contributions are secondary to any person or organization specified in the creator(s) field. ">relators:ctb</a></td>
  </tr>
  <tr>
    <td><a href="coverage_spatial.md" class ="magic-button" title="ARMINDA Use: Geographic subject headings">field_geographic_subject</a></td>
    <td><a href="mods.subject_geographic.md" class ="magic-button" title="Definition: A term or phrase representing the primary topic(s) on which a work is focused">subject/geographic</a></td>
    <td><a href="rdf.dcterms_spatial.md" class ="magic-button" title="Definition: Spatial characteristics of the resource.">dcterms:spatial</a></td>
  </tr>
   <tr>
    <td><a href="creators.md" class ="magic-button" title="ARMINDA Use: identifies the entity/entities primarily responsible for making the resource">creators</a></td>
    <td><a href="mods.name.md" class ="magic-button" title="Definition: The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource">name/namePart</a></td>
    <td><a href="rdf.field_linked_agent.md" class ="magic-button" title="Definition: identifies the entity/entities primarily responsible for making the resource ">relators:cre</a></td>
  </tr>
    <tr>
		<td><a href="date.display.md" class ="magic-button" title="ARMINDA Use: Date of creation or publication of original object in human readable format for public viewing">field_date_display</a></td>
		<td><a href="mods.originInfo_dateOther.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/dateOther</a></td>
		<td><a href="rdf.rdau.p60527.md" class ="magic-button" title="Definition: Relates a resource to a timespan that is the earliest associated with a resource">rdau:P60527</a></td>
  </tr>
   <tr>
    <td><a href="date.encoded.md" class ="magic-button" title="ARMINDA Use: Encoded date of creation or publication of the original object with qualifiers and date ranges when applicable">field_edtf_date_created</a></td>
		<td><a href="mods.originInfo_dateOther.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/dateOther</a></td>
    <td><a href="rdf.dcterms.created.md" class ="magic-button" title="Definition: Date of creation of the resource. ">dcterms:created</a></td>
  </tr>  
   <tr>
		<td><a href="date_issued.md" class ="magic-button" title="ARMINDA Use: Issue date of the newspaper">field_edtf_date_issued</a></td>
		<td><a href="mods.originInfo_dateIssued.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/dateIssued</a></td>
		<td><a href="rdf.dcterms.issued.md" class ="magic-button" title="Definition: Date of formal issuance of the resource.">dcterms:issued</a></td>
  </tr>
  <tr>
    <td><a href="date.sort.md" class ="magic-button" title="ARMINDA Use: Encoded date of creation or publication of the original object that strips out qualifiers and date ranges to allow us to sort on date in ARMINDA">field_edtf_date</a></td>
    <td><a href="mods.originInfo.dateCreated.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/dateCreated</a></td>
    <td><a href="rdf.dcterms.date.md" class ="magic-button" title="Definition: A point or period of time associated with an event in the lifecycle of the resource.">dcterms:date</a></td>
  </tr>
  <tr>
    <td><a href="department.md" class ="magic-button" title="ARMINDA Use: College division in which the item is categorized">department</a></td>
    <td><a href="mods.name.md" class ="magic-button" title="Definition: The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource">name/namePart</a></td>
    <td><a href="rdf.field_linked_agent.md" class ="magic-button" title="Definition: College division in which the item is categorized">local:dpt</a></td>
  </tr>
  <tr>
    <td><a href="description.md" class ="magic-button" title="Definition: An account of the resource, primarily used for archival objects">field_description_long</a></td>
    <td><a href="mods.abstract.md" class ="magic-button" title="Definition: A summary of the content of the resource">abstract</a></td>
    <td><a href="rdf.dcterms.description.md" class ="magic-button" title="An account of the resource.">dcterms:description</a></td>
  </tr>
  <tr>
    <td><a href="embargo_date.md" class ="magic-button" title="ARMINDA Use:Date when item is released for public viewing.">field_embargo_date</a></td>
    <td><a href="mods.originInfo_dateValid.md" class ="magic-button" title="Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource. ">originInfo/dateValid</a></td>
    <td><a href="rdf.schema.availabilityStarts.md" class ="magic-button" title="Definition: The beginning of the availability of the product or service included in the offer.">schema:avalibilityStarts</a></td>
  </tr>
  <tr>
    <td><a href="field_extent.md" class ="magic-button" title="ARMINDA Use:Statement of the physical size or duration of the object, such as dimensions, number of items, pages, or running time.">field_extent</a></td>
    <td><a href="mods.physicalDescription.extent.md" class ="magic-button" title="Definition: Describes the physical characteristics of the resource.">physicalDescription/extent</a></td>
    <td><a href="rdf.dcterms.extent.md" class ="magic-button" title="Definition: The size or duration of the resource.">dcterms:extent</a></td>
  </tr>
  <tr>
	<td><a href="field_display_hint.md" class ="magic-button" title="Terms that will change how this resource is displayed">field_display_hint</a></td>
	<td>N/A</td>
	<td>N/A</td>
  </tr>
    <tr>
	<td><a href="field_access_terms.md" class ="magic-button" title="“Terms used to limit, restrict or coordinate access” - Islandora 8">field_access_terms</a></td>
	<td>N/A</td>
	<td class ="magic-button" title="[This I8 field will not be  mapped to RDF as it reproduces information in IMI/access_condition]">N/A</td>
  </tr>
  <tr>
    <td><a href="field_linked_agent.md" class ="magic-button" title="[Label of a field instance populated by taxonomy terms from Corporate Body, Family and Person vocabularies]">field_linked_agent</a></td>
    <td>[see <a href="mods.name.md">name/namePart </a>]</td>
    <td><a href="a href="rdf.field_linked_agent.md" class ="magic-button" title="[definition]">[Undetermined]</a></td>
  </tr>
  <tr>
	<td><a href="field_weight.md" class ="magic-button" title="[Indicates the order of a resource in a collection of resources]">field_weight</a></td>
	<td>N/A</td>
	<td class ="magic-button" title="[This I8 field will not be  mapped to RDF]">N/A</td>
  </tr>
  <tr>
	<td><a href="file.md" class ="magic-button" title="Values contain field location of fields that are used to create Drupal Media">file </a></td>
	<td>N/A</td>
	<td>N/A</td>
  </tr>
    <tr>
    <td><a href="field_funding_sources.md" class ="magic-button" title="ARMINDA Use:Indicates institution or program that helped to fund research project">funding_sources</a></td>
    <td><a href="mods.name.md" class ="magic-button" title="Definition: The name of a person, organization, or event (conference, meeting, etc.) associated in some way with the resource">name/namePart</a></td>
    <td><a href="rdf.rdau.p60451.md" class ="magic-button" title="Definition: Relates a resource to an agent who sponsors some aspect of a resource.">rdau:P60451</a></td>
  </tr>
  <tr>
    <td><a href="field_genre.md" class ="magic-button" title="ARMINDA Use: A more detailed sub-type refining the broader Work Type element; provides a specific characterization of the nature or style of the original content source">field_genre</a></td>
    <td><a href="mods.genre.md" class ="magic-button" title="Definition: A term or terms that designate a category characterizing a particular style, form, or content, such as artistic, musical, literary composition, etc.">genre</a></td>
    <td><a href="rdf.schema.genre.md" class ="magic-button" title="Definition: Genre of the creative work, broadcast channel or group."><b>schema:genre</b></a> I8 mapping needs correcting</td>
  </tr>
     <tr>
    <td><a href="field_identifier.md" class ="magic-button" title="ARMINDA Use: Character string or number that clearly and uniquely identifies a digital object or resource. This field ensures that individual digital objects can be accessed, managed, stored, recalled, and used reliably.">field_identifier</a></td>
    <td><a href="mods.identifier.md" class ="magic-button" title="Definition: Contains a unique standard number or code that distinctively identifies a resource.">identifier</a></td>
    <td><a href="rdf.dcterms.identifier.md" class ="magic-button" title="Definition: An unambiguous reference to the resource within a given context.">dcterms:identifier</a></td>
  </tr>
  <tr>
    <td><a href="field_issue_num.md" class ="magic-button" title="ARMINDA Use: Indicate issue number sequential order of volume">field_issue</a></td>
    <td><a href="mods.part.detail.number.md" class ="magic-button" title="Definition: Numbering and type of designation of the part in relation to the host/parent">part/detail/number</a></td>
    <td><a href="rdf.schema.issueNumber.md" class ="magic-button" title="Definition : Identifies the issue of publication; for example, "iii" or "2".">schema:issueNumber</a></td>
  </tr>
   <tr>
    <td><a href="field_language.md" class ="magic-button" title="ARMINDA Use:  the non-English language of the source content being described : applies to textual or spoken word (linguistic) content).">field_language</a></td>
    <td><a href="mods.language.languageTerm.md" class ="magic-button" title="Definition: A designation of the language in which the content of a resource is expressed.">language/languageTerm</a></td>
    <td><a href="rdf.dcterms.language.md" class ="magic-button" title="Definition: A language of the resource">dcterms:language</a></td>
  </tr>
  <tr>
    <td><a href="license_file.md" class ="magic-button" title="ARMINDA Use: Field used for ingest into ARMINDA. ">license_file</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td><a href="line_num.md" class ="magic-button" title="ARMINDA Use: The line_number is the CSV line number that the IMI module needs in order to keep the CSV in order.">line_num</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr> 
   <tr>
    <td><a href="obj_file.md" class ="magic-button" title="ARMINDA Use: Tells where the file is when item is uploaded to Islandora">obj_file</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>  
   <tr>
    <td><a href="origin.md" class ="magic-button" title="ARMINDA Use: Provides place names associated with the creation or issuance of a resource. ">field_origin</a></td>
    <td><a href="mods.originInfo_place_placeTerm.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/place/placeTerm</a></td>
    <td><a href="rdf.rdau.p60523.md" class ="magic-button" title="Definition: Relates a resource to a place from which a resource originate">rdau:P60523</a></td>
  </tr>
    <tr>
    <td><a href="parent.md" class ="magic-button" title="ARMINDA Use: Tells  Islandora 7 the hierarchy of where an object lives ">parent</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
  <tr>
	<td><a href="parent.id.md" class ="magic-button" title="[definition]">parent_id (under construction)</a></td>
	<td>N/A</td>
	<td><a href="" class ="magic-button" title="[definition]">[unknown]</a></td>
  </tr>
   <tr>
    <td><a href="field_permanent_url.md" class ="magic-button" title="ARMINDA Use: Unique uri (uniform resource identifier) to the item">field_permanent_url</a></td>
    <td><a href="mods.identifier.md" class ="magic-button" title="Definition: Contains a unique standard number or code that distinctively identifies a resource.">identifier</a></td>
    <td><a href="rdf.rdau.p60919.md" class ="magic-button" title="Definition: Relates a resource to an appellation of resource that consists of a code, number, or other string, usually independent of natural language and social naming conventions, used to identify a resource">rdau:P60919</a></td>
  </tr>
  <tr>
    <td><a href="pid.md" class ="magic-button" title="ARMINDA Use: Persistent Identifier that is generated sequentially, and is  a unique identifier for Islandora 7">PID</a></td>
    <td>N/A</td>
    <td>N/A</td>
  </tr>
   <tr>
    <td><a href="field_provenance.md" class ="magic-button" title="ARMINDA Use:Contains provenance information about the object: [currently] donor information and/or when and how the object was acquired by Whitman College.">field_provenance</a></td>
    <td><a href="mods.note.md" class ="magic-button" title="Definition: General textual information relating to a resource.">note</a></td>
    <td><a href="rdf.dcterms.provenance.md" class ="magic-button" title="Definition: A statement of any changes in ownership and custody of the resource since its creation that are significant for its authenticity, integrity, and interpretation.">dcterms:provenance</a></td>
	</tr>
   <tr>
    <td><a href="publisher.md" class ="magic-button" title="ARMINDA Use: the name of the entity that published, printed, distributed, released, issued, or produced the resource.  This may be a formal publisher, or for unpublished materials, a university department or other corporate entity.">publisher</a></td>
    <td><a href="mods.originInfo_publisher.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/publisher</a></td>
    <td><a href="rdf.field_linked_agent.md" class ="magic-button" title="Definition: A person or organization responsible for publishing, releasing, or issuing a resource. ">relators:pbl</a></td>
  </tr> 
   <tr>
    <td><a href="field_rights_contact.md" class ="magic-button" title="ARMINDA Use: HTML link to ARMINDA page linking to contact information for use by end users who wish to pursue required permissions for publication, dissemination, etc">field_rights_contact</a></td>
    <td><a href="mods.access_condition.md" class ="magic-button" title="Definition: Information about restrictions imposed on access to a resource.">accessCondition</a></td>
    <td><a href="rdf.schema.accessibilityControl.md" class ="magic-button" title="Definition: Identifies input methods that are sufficient to fully control the described resource (WebSchemas wiki lists possible values).">schema:accessibilityControl</a></td>
  </tr>
    <td><a href="field_rights.md" class ="magic-button" title="ARMINDA Use: URL that indicates copyright and/or creative commons status supplemented with optional explanatory text. Can include free-text explanation of rights.">field_rights</a></td>
    <td><a href="mods.access_condition.md" class ="magic-button" title="Definition: Information about restrictions imposed on access to a resource.">accessCondition</a></td>
    <td><a href="rdf.rdau.P60339.md" class ="magic-button" title="Definition: Relates a resource to a statement relating to anidentification or function of any agents responsible for the creation of, or who contributes to a realization of, the intellectual or artistic content of a resource.">rdau:P60339</a></td>
  </tr>
  <tr>
    <td><a href="source.md" class ="magic-button" title="ARMINDA Use: A related resource from which the described resource is derived.">source</a></td>
    <td><a href="mods.relatedItem.part.text.md" class ="magic-button" title="Definition: Information that identifies other resources related to the one being described ">relatedItem/part/text</a></td>
    <td><a href="rdf.dcterms.source.md" class ="magic-button" title="Definition: A related resource from which the described resource is derived.">dcterms:source</a></td>
  </tr>
    <tr>
    <td><a href="subject.keywords.md" class ="magic-button" title="ARMINDA Use: Term(s) representing the primary topic(s) on which a work is focused.">subject_keywords</a></td>
    <td><a href="mods.subject.topic.md" class ="magic-button" title="Definition: A term or phrase representing the primary topic(s) on which a work is focused">subject/topic</a></td>
    <td><a href="rdf.dcterms.subject.md class ="magic-button" title="Definition: The topic of the resource.">dcterms:subject</a></td>
  </tr>
  <tr>
    <td><a href="title.md" class ="magic-button" title="ARMINDA Use: Name given to the resource or supplied title if one is absent">title</a></td>
    <td><a href="mods.titleInfo.title.md" class ="magic-button" title="Definition: A word, phrase, character, or group of characters, normally appearing in a resource, that names it or the work contained in it.">titleInfo/title</a></td>
    <td><a href="rdf.dcterms.title.md" class ="magic-button" title="Definition: A name given to the resource.">dcterms:title</a></td>
  </tr>
    <tr>
    <td><a href="title.alternative.md" class ="magic-button" title="ARMINDA Use:An alternative title of the described resource including abbreviations and translations">title_alternative</a></td>
    <td><a href="mods.titleInfo.title.md" class ="magic-button" title="Definition: A word, phrase, character, or group of characters, normally appearing in a resource, that names it or the work contained in it.">titleInfo/title</a></td>
    <td><a href="rdf.dcterms.alternative.md" class ="magic-button" title="Definition: An alternative name for the resource.">dcterms:alternative</a></td>
  </tr>
  <tr>
	<td><a href="url_alias.md" class ="magic-button" title="Reserved Workbench CSV column used for created and updating : similar to Permalink handle)">url_alias</a></td>
	<td>N/A</td>
	<td>N/A</td>
  </tr>
  <tr>
    <td><a href="url.external.md" class ="magic-button" title="ARMINDA Use: URL linking file content not hosted in ARMINDA to metadata record, in ARMINDA">url_external</a></td>
    <td><a href="mods.location_url.md" class ="magic-button" title="Definition: Identifies the institution or repository holding the resource, the physical location of the resource, and/or the electronic location in the form of the digital resource in the form of a URL.">location/url</a></td>
    <td><a href="rdf.schema.url.md" class ="magic-button" title="Definition: URL of the item. ">schema:url</a></td>
  </tr>
  <tr>
    <td><a href="volume_num.md" class ="magic-button" title="ARMINDA Use: Volume of newspaper">volume</a></td>
    <td><a href="mods.part_detail_number.md" class ="magic-button" title="Definition: Numbering and type of designation of the part in relation to the host/parent.">part/detail/number</a></td>
    <td><a href="rdf.schema.volumeNumber.md" class ="magic-button" title="Definition: Identifies the volume of publication or multi-part work; for example, "iii" or "2".">schema:volumeNumber</a></td>
  </tr>
  <tr>
    <td><a href="work_type.md" class ="magic-button" title="ARMINDA Use: Basic conceptual indication of the kind of object being described, using broad terms.">work_type</a></td>
    <td><a href="mods.typeOfResource.md" class ="magic-button" title="Definition: A term that specifies the characteristics and general type of content of the resource.">typeOfResource</a></td>
    <td><a href="rdf.dcterms.type.md" class ="magic-button" title="Definition: The nature or genre of the resource.">dcterms:type</a></td>
  </tr>
  <tr>
    <td><a href="graduation_year.md" class ="magic-button" title="ARMINDA Use: Year author graduated from Whitman College">year_graduation</a></td>
    <td><a href="mods.originInfo_dateOther.md" class ="magic-button" title="Definition: Information about the origin of the resource, including place of origin or publication, publisher/originator, and dates associated with the resource.">originInfo/dateOther</a></td>
    <td><a href="rdf.rdau.p60514.md" class ="magic-button" title="Definition: Relates a resource to a timespan during which an academic degree is conferred by a granting institution or faculty">rdau:P60514</td>
  </tr>
</table>
<dl>
	<p><i>Last Updated: </i>09/03/2021</p>
</dl>
</body>
</html>