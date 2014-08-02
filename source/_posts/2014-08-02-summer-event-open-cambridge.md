---
layout: post
title: "Summer Event: Open Cambridge"
date: 2014-08-02 21:00:32 +0100
author: Alastair Smith
comments: true
categories: 
---

Today saw us run our 2014 summer event, entitled *Open Cambridge*, an [Open Space](http://www.openspaceworld.org) on the subject of Software Craftsmanship. This format of event was familiar to me from the excellent [SoCraTes UK](http://www.socratesuk.org) conferences, and I wanted to bring a little of that goodness to our own Craftsmanship Community.

After an initial opening and welcome explaining the open space format, we started generating ideas for things to talk about, play with, etc., to form the agenda for the day. Each person who came up with an idea (or ideas) had to briefly introduce the session so that everyone knew the purpose of it and what they were likely to get from it, and then place it on the agenda wall in a given time/room combination. It ended up looking a bit like this:

![The agenda for Open Cambridge](http://static.ow.ly/photos/original/6qFhI.jpg "The day's agenda")

## Swift - Let's take a look
Before lunch I ran two sessions. The first was on [Swift](https://developer.apple.com/swift/), the new language from Apple for iOS/Mac development. I gave a tour of the basic syntax and some of the nice features of the language, such as its multi-paradigm nature (both Functional and Object-Oriented), and the fact that, unlike C#, it has proper first-class functions. As it has first-class functions, Functional Programming concepts such as currying and monads are available, and one of my favourite features in Swift is its monadic nil checks.

We also had a bit of a discussion about frameworks for cross-platform development in the mobile arena, looking at [Xamarin](http://www.xamarin.com) and [Unity3D](http://www.unity3d.com/) for mobile game development. Xamarin in particular looks like a very nice solution for writing your mobile apps only once and minimising the amount of platform-specific code you have to write. 

## nand2tetris

The second session I ran was an introduction to [nand2tetris](http://www.nand2tetris.org/), a project I was introduced to by, and have been working through with, the [Cambridge Programmer's Study Group](http://www.meetup.com/Cambridge-Programmers-Study-Group/). It's a really cool project that builds up a simulated computer from the logic gates upwards. Starting with a NAND gate, you first build NOT, AND, OR and XOR operations, and then progress to more complicated chips like a Multiplexer (Mux) and Demultiplexer (DMux), chips that take an input bus rather than pin such as an Or16, and multi-way chips like a four-way Mux. That's just chapter 1! Later chapters introduce Boolean arithmetic, sequential logic (i.e. clocked gates), to build a simulated CPU, then a virtual machine to run on it, a basic operating system, and a high-level language with compiler. Ultimately, you have all the tools at your disposal to build Tetris on your simulated computer. 

I ran this session to introduce more people to the project and encourage them to come along to the Programmer's Study Group meetups. 

## Cross-database management tool
After lunch, I attended a session by an attendee who wanted some feedback on an application he was building to allow access to data stored in both a relational database (MySQL) and a NoSQL database (DynamoDB). The motivation for the application was to allow non-technical users to edit the frequently-changing data in the DynamoDB store, and technical users to edit the more static data in the MySQL store. We spent some time discussing this motivation and the problems associated with giving users direct access to a database, and convinced the person to build the functions into the application itself. We touched briefly on some [Domain-Driven Design](http://en.wikipedia.org/wiki/Domain-driven_design) topics, particularly [Bounded Contexts](http://martinfowler.com/bliki/BoundedContext.html). 

## Extreme Startup Dry Run
The next session I attended was a more practical session, with the intention of getting people set up with the Extreme Startup. This was mostly a Ruby headache: the Extreme Startup code-base requires Ruby 1.9.3, but I had Ruby 2.0.0 installed by Xcode. Reverting to the older version or running the two side-by-side both appear to be quite difficult. Eventually I resolved my issues and managed to run the app successfully under Ruby 1.9.3.

## How to improve the Extreme Startup Event
This session rolled on quite nicely from the previous one, and turned into a bit of a discussion about things that we could have done better with the [Extreme Startup workshop run earlier in the week](/blog/2014/07/29/july-2014-workshop-extreme-startup-with-carlos-fernandez-garcia-and-emanuele-blanco/), such as providing a set of pre-requisites for the workshop and providing a bit more up-front information about what it would involve. We also discussed some ways of reducing the impact of the Wolfram Alpha "cheat" utilised by one team in that workshop. 

After I while I exercised the Law of Two Feet, and moved on to another discussion.

## Down Tools Week, Improvement Days, and other ways to put the fun into coding
This discussion was already half-way through when I arrived and I found the topic had strayed somewhat from the original topic of Down Tools Week/Improvement Days and into ways of promoting self development and learning within a software team. I contributed more to this topic based on my experiences in a previous job than I took away from it, and found it an enjoyable discussion with some thoughts on how I might do things better/differently next time. 

## Retrospective
We closed the day with a retrospective of what had happened in each session and the key outcomes from each, and what each person felt had been most surprising, and their key take-away from the day. We then retired to the Haymakers in Chesterton for a beer or two. :)

All in all, it was a good day and I was pleased to see the Open Space format working well outside of the SoCraTes UK context and  with much smaller numbers too. I will definitely keep the format in mind for future events!