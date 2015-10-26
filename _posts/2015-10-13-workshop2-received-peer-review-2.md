---
layout: post
title: "Workshop2 - Received peer review 2"
date:   2015-10-13 09:46:28
categories: 1dv607 workshop2
---

#### Workshop 2 by Mattias Wikström, Anna Losif & Jasmin Bejtovic
#### Peer-Review by Johan Landbris & Jonas Mattsson

It was very ambitious of you to implement three versions of the program. However, we have only
reviewed Mattias’s version.

#### Is the Architecture ok?

The architecture looks alright. Model-view separation is good and seems to be following the MVC pattern [1].

#### Is the requirement of a unique member id correctly done?

Yes. We had problems whit correct unique id’s when deleting a member and then adding a new one, but we tried that in your application and it handled it as it should.

#### What is the quality of the implementation/source code?

The code is good and easy to follow. Not so many comments but we don’t see any need for that
when the code is well written.

#### As a developer would the diagrams help you and why/why not?
All three diagrams are very well done.

#### What are the strong points of the design/implementation, what do you think is really good and why?

We couldn’t find any major bugs. Easy to understand the console view.

#### What are the weaknesses of the design/implementation, what do you think should be changed and why?

The menu says for example: “Press: S to show Simple List”, but it doesn’t work with ‘S’, only ‘s’. That’s not a major thing, though. Maybe you could do some spacing, since it gets a bit messy after issuing a few commands in a row.

#### Do you think the design/implementation has passed the grade 2 criteria?

Yes. You have done a really good implementation.

#### References:
1. Larman C., Applying UML and Patterns 3rd Ed, 13.7 Guideline: The ModelView
Separation Principle