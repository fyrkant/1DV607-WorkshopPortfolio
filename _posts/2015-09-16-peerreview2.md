---
layout: post
title:  "Workshop 1 - Peer Review 2"
date:   2015-09-16 11:30:00
categories: 1dv607
---
Peer review regarding Adam Österlunds groups domain model. ([Link](https://github.com/ao222qc/1DV607_Workshops/blob/master/Workshop%201/domainmodeluppgift1.png) )

## As a developer would the model help you and why/why not?
No it would not. As stated by Larman (1, p.9), a domain model should be a visualization of the concepts from the real world domain - NOT a description of software objects. Looking at this model as a map over the organization does not help me as a developer.

## Do you think a domain expert (for example the Secretary) would understand the model why/why not?
No, important relationships and classes are missing, for example there is no relationship between secretary and member, it is not possible to understand the secretarys role in assigning berths to new boats.

Examples of parts missing:
* All payment/fee procedures are left out of the model.
* How many boats can a member own?
* It is not possible to understand the relationship between the calendar and the member. Are the members allowed to view the calendar?
* How will the secretary know if two berths are close to eachother or not?


## What are the strong points of the model, what do you think is really good and why?
The few objects that are present are named in a correct way and the relations between them are easily understood.

## What are the weaknesses of the model, what do you think should be changed and why?
The model is too simplified, and it is not possible to see the bigger picture. It lacks many important features as the payment and the treasurer role. The model should be made with better UML notation. The relationships between some parts of the model should be done. For example the relationship between secretary and the member. That relationship is essential for understanding of real-world problem. Use relationships instead of some attributes(1. p161).


## Do you think the model has passed the grade 2 (passing grade) criteria?
No, it should be completed in many areas.


References:
1. Larman C. Applying UML and Patterns 3rd Ed, 2005, ISBN: 0131489062
