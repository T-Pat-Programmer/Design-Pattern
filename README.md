# Design Patterns in Java – Creational, Behavioural, & Structural
We will be discussing about design patterns in Java
# What is design patterns?
    Java Design Patterns are techniques that provide a traditional business approach to resolve a recurring problem. Using design patterns saves time. There are several Java design patterns that can be use in Java projects.
    Using design patterns in Java promotes reusability that ends up in a lot of robust and highly maintainable code. It helps in reducing Total Cost of Ownership (TCO) of the software package.
    Since design patterns are already defined, it makes our code straightforward to understand and debug. It ends up in quicker development and new members of the team are aware of it simply.
# What are the categories or types of design patterns?
  Design patterns are in 3 categories
  1. Creational
  2. Structural, and
  3. Behavioural design patterns
# Let us have a look at each individually
  ## A. Creational Design Patterns in Java
  Creational design patterns in Java give an answer to instantiate an object within the very best approach for specific things.
  
  # i. Singleton Pattern
  Singleton design patterns in Java restrict the instantiation of a class and ensure that just one instance of the class exists within the Java virtual machine. It looks to be a really easy design pattern, however, once it involves implementation, it comes with a lot of implementation concerns. The implementation of the Singleton pattern has always been a disputable topic among developers.
  
  # ii. Factory Pattern
Factory design patterns in Java are used once we have an excellent class with multiple sub-classes and a super input. In this, we need to define the interface or abstract class for creating an object. Subclasses are responsible for the creation of an instance of the class. The Factory Pattern is also called as Virtual Constructor.

# iii. Abstract Factory Pattern

Abstract factory Java pattern can compare to factory pattern and its factory of factories. A single factory category returns the various sub-classes supported by the input provided and the factory class uses an if-else or switch statement to attain this.

In the Abstract factory pattern, we tend to eliminate the if-else block and have a factory class for every sub-class and so an Abstract factory class which will return the sub-class supported by the input factory category.

# iv. Builder Pattern

Builder patterns in Java solve the problem with the sizable amount of ex gratia parameters and inconsistent state by providing how to create the item in small stages and supply a method that will really return the final Object. Examine the Builder Pattern as an example program and a new employed in JDK.

# v. Prototype Pattern

Prototype design patterns in Java employes once the object creation could be an expensive affair and needs a lot of your time and resources and you’ve got the same object already existing. Therefore this pattern provides a mechanism to copy the initial object to a replacement object and so modify it per our wants. This pattern uses Java cloning to copy the object.

The prototype design pattern mandates that the object that you’re copying should provide the super feature. It mustn’t be done by the other class. But whether or not to use a shallow or deep copy of the item properties depends on the necessities and it’s a design call. Examine paradigm Patterns for a sample program.

## B. Structural Design Patterns in Java
Structural Java patterns give alternative ways to form a class structure, for example, mistreatment inheritance and composition to form an outsized object from small objects.

# i. Adapter Pattern
Adapter design patterns in Java, one of the structural design patterns and it’s used in order that 2 unrelated interfaces will work along. The object that joins these unrelated interfaces calls as an Adapter. As a true-life example, we can think about a mobile charger as an adapter as a result of a mobile battery that wants three volts to charge however the normal socket produces either 120V (US) or 240V (India). Therefore the mobile charger works as an adapter between the mobile charging socket and also the electrical outlet.

# ii. Composite Pattern
Composite Java pattern, one amongst the Structural design pattern and employs once we have to be compelled to represent a part-whole hierarchy. Once we ought to produce a structure in a very approach that the objects within the structure need to be treated identically approach, we can apply a composite design pattern.

# iii. Proxy Pattern
The proxy pattern in Java aims to provide a replacement r surrogate for one more object for control. Proxy pattern employed once we need to produce controlled access to a practicality.

# iv. Flyweight Pattern
Flyweight Java design pattern employs once we ought to produce a lot of Objects of a class. Since each object consumes memory space that may be crucial for low memory devices, corresponding to mobile devices or embedded systems, a flyweight design pattern applies to reduce the load on memory by sharing objects.

# v. Facade Pattern
Facade patterns are employed to help consumer applications simply act with the system. Suppose we’ve got an application with a set of interfaces to use MySQL/Oracle database and to come up with different types of reports, corresponding to hypertext mark-up language reports, PDF reports, etc. Therefore we’ll have a totally different set of interfaces to figure with differing types of database. Currently, a consumer application will use these interfaces to urge the specified info affiliation and generate reports. However once the complexity will increase or the interface behavior names are confusing, consumer applications can realize it is troublesome to manage it. Therefore we can apply the Facade pattern here and supply a wrapper interface on high of the prevailing interface to assist consumer application. Examine the Facade Pattern post for implementation details and a sample program.

# vi. Bridge Pattern
Bridge design patterns in Java are employed to decouple the interfaces from implementation and concealment the implementation details from the consumer programs. Like the Adapter pattern, it’s one of the Structural design patterns.

# vii. Decorator Pattern
Decorator design pattern employed to change the practicality of an object at runtime. At identical time alternative instances of the identical class won’t be full of this, therefore individual object gets the changed behavior. Decorator design pattern is one of the structural design patterns (such as Adapter Pattern, Bridge Pattern, or Composite Pattern) and uses abstract classes or interfaces with the composition to implement.

## C. Behavioural Design Patterns in Java

# i. Template method Pattern
Template method in Java defines the steps to execute a rule and it will give a default implementation that may be common for all or a number of the subclasses

# ii. Mediator Pattern
Mediator design patterns in Java are employed to produce a centralized communication medium between totally different objects in a very system. we can use it in an enterprise application wherever multiple objects interact with one another. If the objects act with one another directly, the system elements are tightly coupled with one another which creates a maintainability price higher and is not versatile to increase simply. The mediator pattern focuses on giving a mediator between objects for communication and facilitating in implementation of loose coupling between objects.

# iii. Chain of Responsibility Pattern
A chain of responsibility pattern is employed to attain loose coupling in software system design wherever asking from the consumer pass to a chain of objects to method them. Then the object within the chain can decide who is going to process the request and whether or not the request is needed to be sent to a future object within the chain or not.

# iv. Observer Pattern
Observer design patterns in Java are beneficial to you within the state of an object and need to urge notified whenever there’s any modification. In the observer pattern, the item that watches the state of another object is known as Observer, and also the object that’s being watched inbuilt Subject.

Java provides intrinsically platform for implementing observer patterns through java.util.Observable category and java.util.Observer interface. As a result of the implementation, most of days we tend to don’t need to finish up extending a category only for implementing the Observer pattern as Java doesn’t give multiple inheritances in categories

# v. Strategy Pattern
Strategy pattern is additionally referred to as Policy Pattern and has multiple rules for a specific task and the consumer decides the actual implementation to be used at runtime.

We tend to define multiple rules and let consumer applications pass the algorithm to be used as a parameter. one of the simplest example of this pattern is Collections.sort() method that takes the Comparator parameter. supported the various implementations of Comparator interfaces, the Objects have gotten sorted in numerous ways.

# vi. Command Pattern
Command Pattern employs to implement loose coupling in a very request-response model. Thus the request send to the invoker and the invoker passes it to the encapsulated command object. The command object passes the request to the acceptable method of the receiver to perform the particular action.

# vii. State Pattern
State design patterns in Java are employed once an Object changes its behavior supported by its internal state.

If we’ve got to alter the behavior of an object supported by its state, we can have a state variable within the Object and use the if-else condition block to perform totally different actions supported by the state. State pattern employs to produce a scientific and close-coupled thanks to achieving this through Context and State implementations.

# viii. Visitor Pattern
The visitor pattern employees once we have to compel to perform an operation on a bunch reasonably Objects. With the assistance of traveler patterns, we can move the operational logic from the objects to a different an.

# ix. Interpreter Pattern
Defines a grammatical illustration for a language and provides an interpreter to influence this grammar.
java compiler, the best example of this pattern, interprets the java ASCII text file into computer memory unit code that’s apprehensible by JVM. Google Translator additionally an example of interpreter pattern wherever the input may contain any language and that we will get the output in another language.

# x. Iterator Pattern
Iterator pattern in one amongst the behavioral pattern accustom give a customary thanks to traverse through a bunch of Objects. It employes in Java assortment Framework wherever Iterator interface provides strategies for traversing through a group

Iterator pattern doesn’t solely regarding traversing through a group, we can give totally different reasonably iterators supported our needs. Iterator pattern hides the particular implementation of traversal through the gathering and consumer programs simply use iterator strategies. Examine Iterator Pattern post as an example program and implementation details.

# xii. Memento Pattern
Memento design patterns in Java employees once we need to save lots of the state of an object in order that we can restore shortly. It employees to implement this in such how that the save state data of the item not accessible outside of the item, this protects the integrity of saving state data.

Memento pattern enforces with 2 objects – creator and Caretaker. The originator is that the object whose state has to save and restore and it uses an inner class to save lots of the state of Object. The inner category call as a reminder and its private, in order that it can’t access from other objects.
So, this was all about design patterns in Java. Hope you like our explanation.
