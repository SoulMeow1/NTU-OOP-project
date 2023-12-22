# Main contributions to this project:

Drawn the class diagram,
Programmed the overall structure of the project in its infancy. Then programmed the majority of the User class, Student class, StudComm class and Staff class. 

## Features of the project:

Methods all follow the single responsibility principle. 

Methods are open for extension. Consider the abstract user class. Subclasses like Staff class and Student class inherit from it. We can make an auditor class in the future if the client wants us to do so. 

Methods inside the classes have rarely overridden. This ensures the Liskov substitution principle

Classes are segregated to fulfill specific niches. Consider the subclasses of the message class. They are Suggestion class and Enquiry class. 
Currently the two subclasses are 99% similar but they fulfill seperate responsibilities. One is for Student committee to make suggestions to camps and the other are prospective attendees' enquiries. 
Differences in their responsibilities dictate that they should have different classes instead of using a generic message class. 

Dependency inversion is not used much in this project.

## Improvements that can be made:

have a generic menu class to standardize all menus. This also makes the programmer's life much easier as they implement new menus because of encapsulation.
