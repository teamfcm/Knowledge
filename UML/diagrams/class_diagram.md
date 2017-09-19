# Class diagram

The UML representation of a class is a rectangle containing three compartments stacked vertically.

The top compartment shows the class's name. The middle compartment lists the class's attributes. The bottom compartment lists the class's operations.

![IMG](https://www.ibm.com/developerworks/rational/library/content/RationalEdge/sep04/bell/bell_fig1.jpg)

Sometimes, attributes can have default value (Ex: flightNumber : Interger = 0).

Inheritance is indicated by a solid line with a closed, unfilled arrowhead pointing at the super class.

An association is a linkage between two classes.

A bi-directional association is indicated by a solid line between the two classes. At either end of the line, you place a role name and a multiplicity value. 

![IMG](https://www.ibm.com/developerworks/rational/library/content/RationalEdge/sep04/bell/bell_fig6.jpg)

0..* means zero or more

0..1 means zero or one

0..5 means zero to five


In a uni-directional association, two classes are related, but only one class knows that the relationship exists.

A uni-directional association is drawn as a solid line with an open arrowhead

![IMG](https://www.ibm.com/developerworks/rational/library/content/RationalEdge/sep04/bell/bell_fig7.jpg)

