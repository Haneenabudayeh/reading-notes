
# summary:


## Domain Modeling:
Domain modeling is the process of creating a conceptual model in code for a specific problem. 

# notes:
* When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
* Model its attributes with a constructor function that defines and initializes properties.
* Model its behaviors with small methods that focus on doing one job well.
* Create instances using the new keyword followed by a call to a constructor function.
* Store the newly created object in a variable so you can access its properties and methods from outside.
* Use the this variable within methods so you can access the object's properties and methods from inside.


## tables 
### table is a way to display content in grid format .
An HTML table is defined with the *table* tag.

Each table row is defined with the *tr8 tag. 
- A table header is defined with the *th* tag. By default, table headings are bold and centered. 
- A table data/cell is defined with the *td* tag.

 CSS property can use in table:
 1. Adding a Border
 2. Collapsed Borders
 3. Adding Cell Padding
 4. Left-align Headings
 5. Adding Border Spacing

 ## ch3:
 ### JavaScript Methods
  JavaScript methods are actions that can be performed on objects.

 A JavaScript method is a property containing a function definition.
### Accessing Object Methods
 You access an object method with the following syntax:
 objectName.methodName()


 #### The this Keyword
 In a function definition, this refers to the "owner" of the function.