
## Object Oriented Programming

The goal of OOP is scale. A program consisting of 100 LOC which will never change does not need OOP.
OOP delivers two important features:
- It scales with increasing LOC
    OOP ensures that the program can still be worked on as the program grows
- It scales with change
    OOP ensures that decisions can be made at a later date. OOP programs are easy to change

Rule of thumb:
20 000 LOC is the cutoff point when OOP is not only worth it, but essential for the project.

#### OOP traits
 - Polymorphism
 - Inheritance
 - Encapsulation

The they are valued as such:

| Polymorphism | Inheritance | Encapsulation |
|--------------|--------------|---------------|
| 30%          | 10%          | 60%           |


Encapsulation is the most important concept of OOP. Objects in a OOP system should hide their data from the surronding world.
When designing objects you should ask yourself; "What do I really want to ask this object?".

Dont suck the data out of objects. Ask them for what you really want to know!


#### Signs you have violated encapsulation

 - a object has to many public behaviors
 - getters, setters
 - law of demeter is broken
 - a class named something -er/-or
 - a data object
 - feature envy


## Inheritance
#### Only to be used when
- Almost all code is in the super class
- It passes the grandmother test
    You can explain the "is a" relationship to your grandmother

Remember: Classes should have behavior

## Polymorphism

Separate code, but implement contract

 
 ### Class Relationships

 [Class relationships](resources/class_relationships.png)

 An example of collaborating classes is the Iterator <-> Collection relationship (Python, Java, C++)



### Analysis Paralysis

It is easy to get lost trying to think and evaluate all possible solutions (models) to a problem.

##### Listen to the code

Time it, use 15 min to work on one of the possible solutions and listen to the code, does it solve the problem? Is it messy? How could it be improved?


### Important Patterns in OOP

 - Quantity Patterns
 - Analysis Patterns


## The Model

Discover the business model. UI and database should depend on this model as it can be much more stable than either of them.

[Mediator Pattern Image](resources/mediator_pattern.png)

