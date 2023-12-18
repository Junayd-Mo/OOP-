OOP notes:
Object-Oriented programming is a programming paradigm used in many real life programming solutions.

An object, AKA an entity, is an instance of a class and can have many different attributes and methods.

A class is essentially the blueprint of the object, it sets the structure that an object will follow.
It is used to make many objects of the same type. Creating an object in a class is called instantiation.

A contructor initialises an object and is used to set up the class attributes.

Public, Private and Protected methods are used to provide an easy interface for classes. 
They also allow protection of sensitive data.

Public methods are accessible both inside and outside the scope of a class. 
Any instance of the class can have access to a public method and can call upon them.
They are used when displaying info for everyone to see.

Private methods cannot be accessed from outside the class scope.
This should be used when dealing with: sensitive info, methods that do not collaborate with other classes
and methods that don't dispaly inforamtion and add to the interface.

Protected methods are private and cannot be accessed outside the scope of the class 
however, objects of the same class can access them.
They are used when you want to compare and/or transfer data between objects of the same class and dont 
want that data to be public.



The four principles of OOP are:
Encapsulation, Abstraction, Inheritance and Polymorphism

Encapsulation/Information hiding is the hiding of data and complexity of the inner working of an object from others.
Data can only be accessed through accessors and mutators.

An accessor is a method (get method) used to ask an object about itself and gives info about the state of an object.
These are set to a Read-Only state

A mutator is a public method used to modify the state of an object while hiding how the data gets modified.
These are set to a Write-Only state

Encapsulation protects data integrity by preventing users from changing internal data to an invalid state.

Abstraction is to show the necessary details to the user and hides internal functionality that is not needed.
Only shoes the available methods.

Data abstraction pertains to abstracting data entities

Process abstraction hides the underlying implementation of a process

Inheritance is a way to reuse code of existing objects or establish a subtype from an exsisting object.
Classes can inherit variables, properties and methods or functions from a pre-existing class i.e. a Super-CLass.
Resulting classes are called Child classes or Subclasses. 

Polymorphism means one name but many forms. It has multiple methods all with the same name, but slightly different 
functionality.



