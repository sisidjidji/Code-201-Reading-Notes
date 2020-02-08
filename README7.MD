# CLASS 7 

# Domain Modeling
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

# Tables:

- the <b> < table> </b> element is used to add tables to web page
- a table is drawn out rowby row .Each row is created with the <b> < tr></b>
- inside each row there are a number of cells  represented by the < td> element or  <b>< th> </b> if it is a header 
- you can make celles of table span more than one row or column using the <b> rowspan</b> and <b> colspan</b> attributes
- for long tables you can split the tables you can split the table into a <b> < thead> <b>, <b> < tbody> <b>, <b> < tfoot> <b>


### basic table structure :
< table>
< tr>// firsr row
< td> 1 st cell< td>
< td> 2 nd cell < td>
< td> 3 ed cell< td>
< /tr>
< tr> // second row
< td> 1 st cell < td>
< td> 2 nd cell< td>
< td>3 ed cell < td>
< tr>
< table>

### tables heading :
< table>
< tr>
< th>< /th>
< th scope ="col1">first columne title< /th>
< th scope ="col2">first columne title< /th>
< /tr>
< tr>// firsr row
< th scope="row"> first row title< /th>
< td> 1 st cell< td>
< td>2nd cell< td>
< /tr>
< table>

