---
layout: post
title:  "Workshop 3 - Peer Review 2"
date:   2015-10-27 13:48:42
categories: 1dv607 workshop3
---

Peer review regarding Hatem Housseins group.

[https://github.com/SaulSilver/blackjack_java](https://github.com/SaulSilver/blackjack_java)

#### Try to compile/use the source code provided. Can you get it up and running? Is anything problematic?

Our group has no prior experience with Java and compiling the code into a runnable version. Therefore we were not able to get the code up and running and this review has been based purely on inspecting the code and the diagram.


#### Test the runnable version of the application in a realistic way. Note any problems/bugs.

See previous answer.

#### Does the implementation and diagrams conform (do they show the same thing)? Are there any missing relations? Relations in the wrong direction?

No, there should be a relation between RulesFactory class and Soft17Strategy.

####Is the dependency between controller and view handled? How? Good? Bad?

The logic is moved from the controller to the view but now the view is doing the controllers job. Could be solved with enums instead.

#### Is the Strategy Pattern used correctly for the rule variant Soft17?

Yes.

#### Is the Strategy Pattern used correctly for the variations of who wins the game?

Yes.

#### Is the duplicate code removed from everywhere and put in a place that does not add any dependencies (What class already knows about cards and the deck)? Are interfaces updated to reflect the change?

It is removed but put in the Player instead of Dealer-class. Should be placed in the Dealer instead since it is only used by the dealer.

#### Is the Observer Pattern correctly implemented?

The observer is implemented corrrectly but the pause in updateHand method should be moved to an own method in the view instead and called from the controller.


#### Is the class diagram updated to reflect the changes?

There is Interface Observer on the class diagram and relations points in good direction.
There is relation between RulesFactory class and Soft17Strategy in code, and there is no relation on diagram. In our opinion, there should be relation in the same way as relation between RulesFactory and BasicHitStrategy. It should show dependency.


#### Do you think the design/implementation has passed the grade 2 criteria?

After the class diagram is updated and the pause is moved from the controller to the view, the grade 2 criteria would be passed.

