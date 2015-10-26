---
layout: post
title: "Workshop2 - Received peer review 1"
date:   2015-10-13 09:38:37
categories: 1dv607 workshop2
---

#### Peer Review of Mattias Wikström group mw222rs
Written by Frida Holmström fh222dt.
The parts about code is based on Mattias implementation

####Test the runnable version of the application in a realistic way. Note any problems/bugs.

It works well. I have added members, added boats, changed members and list them. I found 1 bug when entering a decimal value to boat length. The app crashed when entering 12,4.

#### Try to compile/use the source code using the instructions provided. Can you get it up and running? Is anything problematic? Are there steps missing or assumptions made?

Works perfectly.

####Does the implementation and diagrams conform (do they show the same thing)? Are there any missing relations? Relations in the wrong direction? Wrong relations? Correct UML notation?

The sequence diagrams are well made and easy to understand. [1, p177, ch10.5] The class diagram doesn’t show relations between them. [1, p251, ch16.2]

#### Is the Architecture ok?

The architecture is well made. Model-view separation is followed thru out. [1, p209 ch13.7]

#### Is the requirement of a unique member id correctly done?

Yes, you check what numbers has been used and add to that.

#### What is the quality of the implementation/source code?

The code has good standard. Not much duplication and good naming. A tiny bit of code in the DAL-classes are commented out. [2]

#### What is the quality of the design? Is it Object Oriented?

The code uses GRASP in a good way. The classes have high cohesion and low coupling. [1, p277, ch17.4]

#### As a developer would the diagrams help you and why/why not?

The sequence diagrams would help me understand the code in a good and fast way. But the class diagram is not there yet. [1, p176, ch10.3]

#### What are the strong points of the design/implementation, what do you think is really good and why?

You have a nice separation of model/view. Good cohesion of classes. [1, p277, ch17.4] What are the weaknesses of the design/implementation, what do you think should be changed and why?

The controller could maybe be split up into several classes for a higher cohesion. [1, p.291, ch17.8]

Perhaps the UI could be more readable with some color and empty lines between different tasks. But that’s not the main focus in this workshop.

#### Do you think the design/implementation has passed the grade 2 criteria?

Yes, when the class diagram is up to UML standard. All other parts are already there.

#### References
1. Larman C., Applying UML and Patterns 3rd Ed, 2012, ISBN: 978-81-7758-979-5
2. C# Coding Conventions, https://msdn.microsoft.com/en-us/library/ff926074.aspx