---
layout: post
title:  "Workshop 3 - Peer Review 1"
date:   2015-10-27 13:49:09
categories: 1dv607 workshop3
---

Peer review regarding Guillaume Fumeauxs workshop.

[https://onedrive.live.com/redir?resid=5E97C5C6460A4CCC!2259&authkey=!AHDtSPNgwoWAMKQ&ithint=folder%2c](https://onedrive.live.com/redir?resid=5E97C5C6460A4CCC!2259&authkey=!AHDtSPNgwoWAMKQ&ithint=folder%2c)


#### Try to compile/use the source code provided. Can you get it up and running? Is anything problematic?

Our group has no prior experience with Java and compiling the code into a runnable version. Therefore we were not able to get the code up and running and this review has been based purely on inspecting the code and the diagram.


#### Test the runnable version of the application in a realistic way. Note any problems/bugs.

See previous answer.

#### Does the implementation and diagrams conform (do they show the same thing)? Are there any missing relations? Relations in the wrong direction?

The class diagram conform the code. Relations are in good direction.


#### Is the dependency between controller and view handled? How? Good? Bad?

Handled nicely with an enum in IView.MenuChoice enum that is set in the specific views from key input.


#### Is the Strategy Pattern used correctly for the rule variant Soft17?

It seems that code is written correctly. We can not run the code and see if it works, as we explained in the beginning, but the function DoHit in class Soft17Strategy seems good (from the point of view of three people that never worked with JAVA).


#### Is the Strategy Pattern used correctly for the variations of who wins the game?

It is used correctly.


#### Is the duplicate code removed from everywhere and put in a place that does not add any dependencies (What class already knows about cards and the deck)? Are interfaces updated to reflect the change?

Yes, the duplicate code seems like it is removed in a good way, although I would have also renamed the Dealer.Deal-method to something that reflects the added show-functionality.


#### Is the Observer Pattern correctly implemented?

Looks like it is correctly implemented although the trigger of the observers .NewCard()-methods are triggered in Player.ShowHand, while I think that it should have been triggered from the DealHand-method. The hand should be redrawn every time a card is dealt, even if it is a hidden card for the dealer. 


#### Is the class diagram updated to reflect the changes?

There is GameObserver interface with correct relations and there is new class Soft17HitStrategy with correct relations. The class diagram seems updated and correspondent changes in the code. 


#### Do you think the design/implementation has passed the grade 2 criteria?

In our opinion it passes the grade 2 criteria.
