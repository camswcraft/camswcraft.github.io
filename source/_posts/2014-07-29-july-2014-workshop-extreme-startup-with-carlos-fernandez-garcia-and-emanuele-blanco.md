---
layout: post
title: "July 2014 Workshop: Extreme Startup with Carlos Fernandez Garcia and Emanuele Blanco"
date: 2014-07-29 19:17:56 +0100
comments: true
author: Alastair Smith
categories: 
---

Our workshop this month was Rob Chatley's "[Extreme Startup](https://github.com/rchatley/extreme_startup)", run by 
[Carlos Fernandez Garcia](https://twitter.com/villademor) and [Emanuele Blanco](https://twitter.com/manub) of the 
[London Software Craftsmanship Community](http://www.meetup.com/london-software-craftsmanship/). Extreme Startup is
based on a question-and-answer format: you register an HTTP server with the Extreme Startup game, and it sends you
questions as HTTP requests. 

After a few technology hiccoughs with the internet connection (note to future self: check this beforehand!), we were
underway with the warmup round, and had seven teams registered with the server. 

The first round focussed on keeping the application running: we learned that the customer is more upset to get no
response at all than to get an incorrect response. The questions in this round were fairly simple maths-based questions:
"what is 1 + 10", "what is the largest of these numbers: 99, 3, 67", etc.

The next round introduced a change in requirements; there's no room to get complacent in this exercise! Suddenly we were
hit with harder maths questions like "which of these numbers are a cube and a square"? One team, taking the innovative
approach of handing off to Wolfram Alpha to answer the questions, quickly took the lead; another team, opting for an
interactive approach to answering the questions, were in second place. Luckily there's no bonus for a quick answer!

The third round upped the stakes further: now we had to handle non-maths questions, like "Who played James Bond in Dr.
No?". This stretched even the hardiest of solutions.

Overall it was a great workshop, which everyone attending enjoyed very much. Unsurprisingly the Wolfram Alpha team
scored the most points, and with a large lead. There was strong competition between one implementation that always
returned *something*, whether or not it was correct, and the team calculating the answers by hand. If you get a chance
to participate in an Extreme Startup workshop, I highly recommend you take it!

## Retrospective

Interestingly, only two teams wrote tests for their solution, and no teams used any kind of source control. Of the
pairs, most were using driver-navigator pairing, but one used ping-pong pairing. 

Starting again, people would choose the technologies they are familiar with to ensure a solid start. 

**Want to share your experience?** [Fork this blog on GitHub](https://github.com/camswcraft/camswcraft.github.io). 

## Thanks

Thanks to Carlos and Emanuele for running the workshop so well and remaining cool under pressure, and to 
[Granta Design](http://www.grantadesign.com/) for hosting us!