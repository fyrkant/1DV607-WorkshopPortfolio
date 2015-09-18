---
layout: post
title:  "Comments regarding peer reviews for Workshop 1"
date:   2015-09-18 11:50:00
categories: 1dv607 workshop1
---

#### There is some classes that are unnecessary, for example the boat description class can be added directly into the boat class and is more an attribute than a separate class [3].
Boat description is a complex concept (it contains attributes that has no direct relation to “boat”) and we think that it should be a separate class.

#### There is no information showing what assumptions or changes was made regarding the requirements.
#### If the assumption were made that they have an authentication system then it should be written somewhere that they have made that assumption themselves.
An alternative would be to make a model with a “User” class that explains the authentication, but we think that in that case it would make the model more understandable to developers not a domain experts. The authentication is self-explanatory in our opinion.

#### The model is not displaying the member’s ability to add/remove/change boats.
The model is showing that a member may own one or many boats. We think displaying ability to add/remove/change boats is connected to the software and should not be included in the domain model.

#### The weaknesses we found was that it was hard to tell in what direction the associations is heading.				
Good point, could make the understanding of the model easier but is not necessary. We think that the model is understandable without direction.
