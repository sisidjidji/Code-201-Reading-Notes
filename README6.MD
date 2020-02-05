# CLASS 6

## 1. OBJECT :

objects groupe together a set of variables and fonctions to create a model of something you would recognize from the real world in an object,variables and functions take on new names.

Variables ----> Properties .
Functions ----> Methods .


## 2. document object model DOM  :

when the browser load  the web page,it creates a model of the page in memory 
the DOM specifies the way in which the browser should structure this model using a <b>DOM tree</b>

- the browser represents the page using a DOM tree .

- DOM trees have four types of nodes: document nodes,element nodes,attribute nodes, and text nodes 

- you can select element nodes by their id or class attributes,by tag name,or using CSS 

- Whenever a DOM query can return more than one node, it will always return a NodeList

- from a element node ,you can access and update its content using properties such as textContent and innerHTML or usinf DOM manipulation techniques 

- an element node can contain multiple text nodes and child elements that are sibling of each others .

- browser offer tools for viewing the DOM tree

## Syntax :

### Methods that return a single element NODE

* getElementByid(id)

* querySelector('CSS selector')

### Methods that return one or more elements as NODEList

* getEalementsByClassName('class')

* getEalementsBytagName('tagName')

* querySelectorall('CSS selector')
