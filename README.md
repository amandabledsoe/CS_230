# CS 230 – The Gaming Room

This repository includes my software design document for Draw It or Lose It. I completed Projects One and Two, but I did not finish Project Three. The Recommendations section is still incomplete.

## Client and Software Requirements

The Gaming Room wanted to take its Android game, Draw It or Lose It, and make it available through a web browser on different devices. The application needed to support teams with multiple players, check for duplicate names, and give records unique IDs. Since the game uses timed rounds, the design also needed to consider how players would receive consistent updates.

## What I Did Well

I think one of my stronger areas was looking at how the game would work for someone actually playing it. In the platform comparison, I included details like making sure a phone’s keyboard would not cover the guess button. I also considered what should happen if someone switched apps during a round. These might seem like small things, but they could make the game frustrating if they were overlooked.

## How the Design Document Helped With Coding

The domain model gave me something to refer back to when working with the classes. It helped me keep track of how games, teams, and players were connected and what each class needed to handle. Having the shared ID and name information in Entity also made sense because I did not have to repeat those same fields in every class.

## What I Would Revise

I would start by finishing the Recommendations section. I spent time comparing the platforms, but I still needed to explain which approach I would choose for this particular game and why. I would use that comparison to make recommendations for hosting, storage, memory, networking, and security. That would make the document more useful to the client when deciding how to move forward.

## Considering the User’s Needs

I looked at what the client wanted and tried to connect those requests to specific design decisions. Supporting different devices meant considering smaller screens and touch controls. Timed rounds meant planning for a shared server timer so players would not each be relying on their own device’s clock. To me, considering the user matters because getting the code to run is only part of the job. People also need to be able to use the application without fighting with it.

## My Approach to Software Design

I worked through the requirements, constraints, class relationships, and platform differences in smaller pieces. The UML diagram was useful because I could look at the relationships instead of trying to keep all of them straight in my head. Next time, I would also make a checklist connecting each requirement to a test. I would want to check situations like duplicate names or two players trying to create records at the same time, along with the cases where everything goes as expected.
