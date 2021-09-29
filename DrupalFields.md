<!DOCTYPE html>
<html>
<body>

<table style="width:100%">
  <tr>
    <th><a href="index.md">Main page</a></th>
	<th><a href="IMI.md">IMI Column</a></th>
    <th><a href="MODS.md">MODS Field</a></th>
	<th>Drupal Fields</th>
    <th><a href="RDF.md">RDF Field</a></th>
  </tr>
<table>
<h1>Drupal Field descriptions</h1>
	<p>There is no designated set of Drupal fields, however, there is a list of <a href="https://www.drupal.org/docs/drupal-apis/entity-api/fieldtypes-fieldwidgets-and-fieldformatters">drupal field types</a> that are used to create Drupal fields. These are our fields in Islandora 8, and their descriptions.</p>
<h2>Abstract</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Text (formatted, long)</td>
					<td>N/A / Limited (1)</td>
					<td>N/A</td>
					<td>field_abstract</td>
					<td>Custom field</td>
				</tr>
			</table>
	<dl>
			<dt><b>Related Fields</b></dt>
				| <a href="field_abstract.md">field_abstract</a> | <a href="mods.abstract.md">MODS/abstract</a> | <a href="rdf.dcterms.abstract.md">RDF/dcterms:abstract </a> |
		</dd>
	</dl>
<h2>Access Control</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Entity reference</td>
					<td>N/A / Unlimited</td>
					<td>Taxonomy term / Islandora Access</td>
					<td>field_access_terms</td>
					<td>Custom field?</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				<dd>| <a href="field_access_terms.md">field_access_terms</a>  |
	</dl>
<h2>Alternative Title</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Text (plain)</td>
					<td>255 Characters / Limited (1)</td>
					<td>N/A</td>
					<td>field_alternative_title</td>
					<td>Default field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
			 | <a href="field_alternative_title.md">field_alternative_title</a>| <a href="mods.titleInfo.title.md">MODS/titleInfo/title</a> | <a href="rdf.dcterms.alternative.md">RDF/dcterms:alternative</a> |
	</dl>
<h2>Date</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Text (plain)</td>
					<td>255 characters /Limited (1)</td>
					<td>N/A</td>
					<td>field_date_display</td>
					<td>Custom field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_date_display.md">field_date_display</a> | <a href="mods.originInfo_dateOther.md">MODS/OriginInfo/dateOther</a> | <a href="rdf.rdaup60527.md">RDF/rdau:P60527</a> | 
	</dl>
<h2>Description</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Text (formatted, long)</td>
					<td>N/A  / Limited (1)</td>
					<td>N/A</td>
					<td>field_description_long</td>
					<td>Custom field?</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_description_long.md">field_description_long</a> | <a href="mods.abstract.md">MODS/abstract</a> | <a href="rdf.dcterms.descriptions.md">RDF/description</a> | 
	</dl>	
<dl>
<h2>Display Hints</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Notes</i></th>
				</tr>
				<tr>
					<td>Entity reference</td>
					<td>Limited (1)</td>
					<td>Taxonomy/Islandora Display</td>
					<td>field_display_hints</td>
					<td>Default field</td>
				</tr>
			</table>
	<dl>
			<dt><b>Related Fields</b></dt>
				| <a href="field_display_hints.md">field_display_hints</a> |
		</dd>
	</dl>
<h2>Date (EDTF)</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>EDTF</td>
					<td>128 characters / Unlimited</td>
					<td>N/A</td>
					<td>field_edtf_date</td>
					<td>Custom field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_edtf_date.md">field_edtf_date</a> | 
				<a href="mods.originInfo.dateCreated.md">MODS/originInfo/dateCreated</a> |
				<a href="rdf.dcterms.date.md">RDF/dcterms:date</a> |
	</dl>
<h2>Date Created (EDTF)</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>EDTF</td>
					<td>128 characters / Unlimited</td>
					<td>N/A</td>
					<td>field_edtf_date_created</td>
					<td>Default field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_edtf_date_created.md">field_edtf_date_created</a> | 
				<a href="mods.originInfo.dateCreated.md">MODS/originInfo/dateCreated</a> | 
				<a href="rdf.dcterms.created.md">dcterms:created</a> |
	</dl>
	
<h2>Date Issued (EDTF)</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>EDTF</td>
					<td>128 characters / Unlimited</td>
					<td>N/A</td>
					<td>field_edtf_date_issued</td>
					<td>Default field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_edtf_date_issued.md">field_edtf_date_issued</a> | 
				<a href="mods.originInfo_dateIssued.md">MODS/originInfo/dateIssued</a> | 
				<a href="rdf.dcterms.issued.md">RDF/dcterms:issued</a> |
	</dl>
<h2>Embargoed Until</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>EDTF</td>
					<td>255 characters / Limited (1)</td>
					<td>N/A</td>
					<td>field_embargo_date</td>
					<td>Custom field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_embargo_date.md">field_embargo_date</a> |  
				<a href="mods.originInfo_dateValid.md">MODS/originInfo/dateValid</a> | 
				<a href="rdf.schema.availabilityStarts.md">RDF/schema:avalibilityStarts</a>| 
	</dl>
<h2>Extent</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Text (plain)</td>
					<td>255 characters / Unlimited</td>
					<td>N/A</td>
					<td>field_extent</td>
					<td>Default field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
			| <a href="field_extent.md">field_extent</a> |  
			<a href="mods.physicalDescription.extent.md">MODS/physicalDescription/extent |  
			<a href="rdf.dcterms.extent.md">RDF/dcterms:extent</a> |
	</dl>
	<h2>Funding</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Text (formatted, long)</td>
					<td>N/A / Limited (1)</td>
					<td>N/A</td>
					<td>field_funding_sources</td>
					<td>Custom Field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_funding_sources.md">field_funding_sources</a> | 
				<td><a href="mods.name.md">MODS/name/namePart</a> |  
				<a href="rdf.rdau.p60451.md">rdau:P60451</a> |
	</dl>
<h2>Genre</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Entity reference</td>
					<td>N/A / Unlimited</td>
					<td>Taxonomy term / Genre</td>
					<td>field_genre</td>
					<td>Custom field (mapping change from dc:type to schema:genre)</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_genre.md">field_genre</a> | 
				<a href="mods.genre.md" >MODS/genre</a> |
				<a href="rdf.schema.genre.md" >RDF/schema:genre</a> | 
	</dl>
<h2>Geographic Subject</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Entity reference</td>
					<td>N/A / Unlimited</td>
					<td>Taxonomy term / Geographic Location</td>
					<td>field_geographic_subject</td>
					<td>Default field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_geographic_subject.md">field_geographic_subject</a> | 
				<a href="mods.subject_geographic.md">MODS/subject/geographic</a> |
				<a href="rdf.dcterms_spatial.md">RDF/dcterms:spatial</a> | 
	</dl>
<h2>Graduation Year</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>EDTF</td>
					<td>255 characters / Limited (1)</td>
					<td>N/A</td>
					<td>field_graduation_year</td>
					<td>Custom field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_graduation_year.md">field_graduation_year</a> | 
				<a href="mods.originInfo_dateOther.md">MODS/originInfo/dateOther</a> |
				<a href="rdf.rdau.p60514.md">RDF/rdau:p60514</a> |
	</dl>
<h2>Identifier</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Text (plain)</td>
					<td>255 characters / Unlimited</td>
					<td>N/A</td>
					<td>field_identifier</td>
					<td>Default field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				<a href="field_identifier.md">field_identifier</a> | 
				<a href="MODS.identifier.md">MODS/identifier</a> | 
				<a href="rdf.dcterms.identifier.md">RDF/dcterms:identifier</a>|
	</dl>
<h2>Issue</h2>
			<table>
				<tr>
					<th><i>Type of field</i></th>
					<th><i>Max Length/Repeatability</i></th>
					<th><i>Type of Item Reference/Vocabulary</i></th>
					<th><i>Machine name</i></th>
					<th><i>Note</i></th>
				</tr>
				<tr>
					<td>Text (plain)</td>
					<td>255 characters / Limited (1)</td>
					<td>N/A</td>
					<td>field_issue_num</td>
					<td>Custom field</td>
				</tr>
			</table>
	<dl>
		<dt><b>Related Fields</b></dt>
				| <a href="field_issue_num.md">field_issue_num</a> | 
				<a href="mods.part.detail.number.md">MODS/part/detail/number</a> |
				<a href="rdf.schema.issueNumber.md">RDF/schema:issueNumber</a> |
	</dl>
<p><i>Last Updated: </i>09/29/2021</p>
</body>
</html>
