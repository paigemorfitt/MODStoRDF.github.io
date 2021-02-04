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

<h1>Migration Questions</h1>

<dt>
	<li>Question: IMI/abstract : Is this going to be one field or two? currently, this field is being used as an Abstrace field, and a Description field based on different collections. Will this need to be broken up into two different fields for RDF mapping, or can we use different YAML files for different collections?  </li>
    <li>Answer: it is easier to break into two fields. Otherwise a code would be needed</li>
</dt>
<dt>
	<li>Question: IMI/embargo_date : How do we store this information upon migration? How do we display a field that displays only for items under embargo, and remove once the embargo is expired?</li>
</dt>
<dt>
	<li>Question: Can you use html?</li>
	<li>Answer: Yes. You can configure fields to accept html.</li>
</dt>
<dt>
	<li>Question: can you link controlled vocabulary terms to their url?</li>
	<li>Answer: It is possible. You can also insert the url directly (summary of answer)</li>
</dt>
<dt>
	<li>Question: do you need to provide list of solr or XPath fields for migraiton?</li>
	<li>Answer: No. For the migration, it works backwards by looking at your content then selecting solr fields (summary of question)</li>
</dt>
<p>Note: It is encouraged to do more reasearch on Answers as some contain additional information necessary to answer the question, information that is not listed/is institution or situation specific </li>
</body>
</html>