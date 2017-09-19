# Class diagram

The **UML representation** of a class is a rectangle containing three compartments stacked vertically.

The top compartment shows the class's name. The middle compartment lists the class's attributes. The bottom compartment lists the class's operations.

![IMG](https://www.ibm.com/developerworks/rational/library/content/RationalEdge/sep04/bell/bell_fig1.jpg)

Sometimes, attributes can have **default value** (Ex: flightNumber : Interger = 0).

**Inheritance** is indicated by a solid line with a closed, unfilled arrowhead pointing at the super class.

An **association** is a linkage between two classes.

A **bi-directional** association is indicated by a solid line between the two classes. At either end of the line, you place a role name and a multiplicity value. 

![IMG](https://www.ibm.com/developerworks/rational/library/content/RationalEdge/sep04/bell/bell_fig6.jpg)

0..*\ means zero or more

0..1 means zero or one

0..5 means zero to five


In a **uni-directional** association, two classes are related, but only one class knows that the relationship exists.

A uni-directional association is drawn as a solid line with an open arrowhead

![IMG](https://www.ibm.com/developerworks/rational/library/content/RationalEdge/sep04/bell/bell_fig7.jpg)

A class and an **interface** differ: A class can have an actual instance of its type, whereas an interface must have at least one class to implement it.

An interface is considered to be a specialization of a class modeling element. Therefore, an interface is drawn just like a class, but the top compartment of the rectangle also has the text "«interface»".

A dotted line with a closed, unfilled arrow means realization (or implementation)

![IMG](https://www.ibm.com/developerworks/rational/library/content/RationalEdge/sep04/bell/bell_fig10.gif)



![IMG](https://www.ibm.com/developerworks/rational/library/content/RationalEdge/sep04/bell/bell_fig11.jpg)

In the class diagram shown in this figure , the association between the Flight class and the FrequentFlyer class results in an **association class** called MileageCredit. This means that when an instance of a Flight class is associated with an instance of a FrequentFlyer class, there will also be an instance of a MileageCredit class.