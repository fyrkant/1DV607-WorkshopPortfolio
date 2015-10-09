---
layout: post
title:  "Workshop 2 - Peer Review 2"
date:   2015-10-09 11:30:00
categories: 1dv607 workshop2
---

### Regarding Alexandre Driaguines group

[https://github.com/ad222kr/1dv607](https://github.com/ad222kr/1dv607)

#### Test the runnable version of the application in a realistic way. Note any problems/bugs.
Application crashes, unable to start. 

#### Try to compile/use the source code using the instructions provided. Can you get it up and running? Is anything problematic? Are there steps missing or assumptions made?
Able to compile in Visual Studio, although breakpoints are still present which could have been removed to make it easier to run. 

#### Does the implementation and diagrams conform (do they show the same thing)? Are there any missing relations? Relations in the wrong direction? Wrong relations? Correct UML notation?
The class diagram uses correct UML notation and no wrong relations or relations in the wrong directions seems to be present. Sequence diagrams are easy to follow and understand. 

#### Is the Architecture ok?

Each controller could be a method inside AppController instead to make the application less complex.

* Is there a model view separation?
There is a visible separation of model/view.

* Is the model coupled to the user interface?
No!

* Is the model specialized for a certain kind of IU (for example returning formated strings to be printed)
It is not. It throws exceptions, but the strings are not formated. We assume that it is good.

* Are there domain rules in the UI?
No, overall model/view separation is done good.

#### Is the requirement of a unique member id correctly done?
It is done good, but the implementation is complicated. Instead of order of array, it is possible to use Max method on array.

#### What is the quality of the implementation/source code?

* Code Standards
Implementation is not optimal (see previous question as example).

* Naming
Naming is good(1).

* Duplication
There is no duplication in code.

* Dead Code

There is no visible dead code.

#### What is the quality of the design? Is it Object Oriented?
Correct MVC implementation. *Objects are connected using associations and not with keys/ids.*

* Is GRASP used correctly?
As far as we can see, the GRASP patterns are followed (2 p291).

* Classes have high cohesion and are not too large or have too much responsibility.
The number of controller classes are too high in our opinion.

* Classes have low coupling and are not too connected to other entities.
Controller classes are too connected to other entities. This should have been done better. We wrote about this on following questions. 

* Avoid the use of static variables or operations as well as global variables.
There are no static variables or operations.

* Avoid hidden dependencies.
There is no hidden dependencies.

* Information should be encapsulated.
Information is encapsulated in private fields and there are access methods (getters and setters) to them.

* Inspired from the Domain Model.
Largely, yes.

#### Primitive data types that should really be classes (painted types)
There is no primitive data types that should be classes.

####As a developer would the diagrams help you and why/why not?
Sequence diagrams would help me understand the flow of application. They are the strongest point of whole project.

#### What are the strong points of the design/implementation, what do you think is really good and why?
Good Model/View separation. There is no dependencies between model and view.

#### What are the weaknesses of the design/implementation, what do you think should be changed and why?
The code is a little bit messy with a lot of classes which makes it a bit hard to get into. Controllers could perhaps have been limited to one master controller without any real change in functionality and would have made the code a lot more readable. As it is now it is a little bit confusing to go through the flow of the program with all the small controller classes. 

#### Do you think the design/implementation has passed the grade 2 criteria?
There could be some small corrections (for example .exe doesn’t works) but design/implementation has passed the grade 2 criteria.

#### References:

1. Naming Guidelines, [https://msdn.microsoft.com/en-us/library/ms229002(v=vs.110).aspx](https://msdn.microsoft.com/en-us/library/ms229002(v=vs.110).aspx)

2. Larman C. Applying UML and Patterns 3rd Ed, 2005, ISBN: 0131489062

