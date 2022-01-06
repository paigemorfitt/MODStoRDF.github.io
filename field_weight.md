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

<h1>field_weight</h1>
<table>
<tr>
	<th>ARMINDA Use</th>
	<td>Indicates the order of a resource in a collection of resources</td>
</tr>
<tr>
	<th>Obligation</th>
	<td>Required, if applicable</td>
</tr>
<tr>
	<th>Repeatable</th>
	<td>No</td>
</tr>
<tr>
	<th>Public Field</th>
	<td>No</td>
</tr>
<tr>
	<th>Syntax/Formatting</th>
	<td>Number (integer)</td>
</tr>
<tr>
	<th>Recommended Controlled Vocabulary</th>
	<td>N/A</td>
</tr>
<tr>
	<th>Notes</th>
	<td>
		<ul>
			<li>Only applicable when creating compound objects and paged content</li>
			<li>Parent must be placed higher on the spreadsheet than children</li>
			<li>By default child resource nodes are un-ordered. To order the sub-components of a paged content resource node, Islandora provides a Weight field to store a integer value on child resource nodes. Children resource nodes with smaller weight values will come before child resource nodes with larger weight values. This follows the usual ordering pattern of 1 (smaller) coming before 2 (larger).</li>
			<li>Weight values do not need to be sequential, just ordered from smallest to largest. For example, the first child resource node can have a value of 10 and the next could have a value of 20 and they will be ordered accordingly. Should a new child be added with the weight value of 15 it will automatically be sorted after the child with the weight value 10 and before the child with the weight value 20.</li>
			<li>Not mapped to RDF </li>
		</ul>
	</td>
</tr>
<tr>
	<th>Field Changes</th>
	<td>N/A</td>
</tr>
</table>
 <dl>
	<dt><b>Related Fields</b></dt>
		 <dd> 
			<a href="DrupalFields.md#weight">Drupal Fields</a> 
		</dd>
</dl>
<p><i>Last Updated: 01/06/2022</i></p>
</body>
</html>