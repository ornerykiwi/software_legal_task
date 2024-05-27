# Software Design Methodologies

## Design Strategies:
1. Structured design
2. Function oriented design
3. Object oriented design

## Task

### Question 1 - coupling and cohesion

| Definitions | Description |
| ----------- | ----------- |
| Coupling | When software modules (an extension to a main program dedicated to a specific function) depend on each other (interdependency.)|
| Cohesion | Elements within a module that are closely related to one specific purpose |

### Question 2 - the difference between top-down and bottom-up design

For the top-down approach, the problem is broken up into smaller parts and then focused on. Whereas, for the bottom-up, smaller problems are worked on and then integrated as a whole to complete the solution. A good example of bottom-up is object oriented programming where objects are created first. Top-down is like the way a big company structures its projects, there is more of a hierarchy where decisions are made. 

### Question 3 - methodology for a class diagram

For documenting the architecture of software, a UML diagram would be the best way to utilise class diagrams. 

### Question 4 - the four pillars of object oriented programming

| Definitions | Description |
| ----------- | ----------- |
| Encapsulation | The current snapshot of your object's methods, keys and properties. |
| Inheritance | Lets one object acquire the properties and methods of another object.  |
| Polymorphism | Things within the same inhertitance chain being able to do different things. |
| Abstraction | A resuable and easily changeable function that hides away implementation details for a method. "Make coffee" button. |

### Question 5 - what a strategy pattern is and how its implementation differs between functional and object oriented systems

A strategy pattern defines a family of algortithms in a method, encapsulates each of them which allows them to be interchangeable but get you to the same output in different ways. It consists of a common interface for all concrete strategies. Like the different types of sorting methods (common interface) you can use to sort a list of integers, Quicksort, Bubblesort or Mergesort (concrete strategies).  

| OOP | FP |
| ----------- | ----------- |
| Strategies are encapsulated in classes, which use objects | Strategies are functions, that are passed around |
| For interchangeability, set a different object that is from the same interface | Passes in a different function |

The difference between the two is that one uses classes and objects to switch between strategies and the other uses functions. 

### Question 6 - a new online payment system that works for most sectors in the market, what design methodology would be best?

Either Functional or Object Oriented programming would be fine, however to maximise the market share and to make the code more flexible, I would choose OOP. Here is why:

- You can define the abstract classes for different sectors (fashion and takeaway) and payment methods (cash or card). Which can then be added to if new options arise (gift/rewards card). 
- Other classes like transactions and user too, where the user can call the transaction method and certain payment method.

To my understanding, because this payment software would be more varied and have lots of abstract classes, it would be easier to use OOP. 

### Useful links:
- [Coupling](https://media.geeksforgeeks.org/wp-content/uploads/20240503155100/coupling-(1).webp)

- [Cohesion](https://media.geeksforgeeks.org/wp-content/uploads/20240503155137/Cohesion-(1).webp)

- [Four Pillars](https://www.freecodecamp.org/news/four-pillars-of-object-oriented-programming/)

- [Class Diagram of Strategy Design Pattern](https://media.geeksforgeeks.org/wp-content/uploads/20240207154820/StrategyDesignPatternExample.webp)

- [OOP vs FP](https://medium.com/@alityson.pratik/object-oriented-vs-functional-design-patterns-part-i-the-strategy-design-pattern-d78016afda5e)
