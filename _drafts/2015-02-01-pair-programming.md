---
layout: post
title: Everyone hates Pair Programming
excerpt: "Two people, one machine.  How can this be 'Productive'?"
modified: 2015-02-01
tags: [agiletrack, agile, product owner]
comments: true
image:
  feature: posts/2015-02-01-header.jpg
---

<section id="table-of-contents" class="toc">
  <header>
    <h3>Overview</h3>
  </header>
<div id="drawer" markdown="1">
*  Auto generated table of contents
{:toc}
</div>
</section><!-- /#table-of-contents -->

Yes - everyone hates pair programming... at first.  I know I did!

I am talking about the XP practice where you have two developers at one machine.  One developer becomes the driver, or programmer, and the other observes, being the copilot.

## Why the Business / Managers hate it

The very notion of it sounds ridiculous - two expensive developers at one machine?!  So we *halve* our potential developer output?

You wouldn't give one hammer to two builders, so why should developers be any different.

## Why Developers hate it

<figure>
<img src="../images/posts/2015-02-01-copilot.png">
<figcaption>Rodger hated Pair Programming from the first time he heard about it</figcaption>
</figure>

Nobody... ok aside from the odd show pony, nobody likes to be watched while they work.  We have all had the experience where we know we are good at something, but the moment someone watches, we feel like someone just whipped our pants down in front of the school.  Programming with someone watching is no different, and that awkward feeling sticks for a while.

There are a number of other spoken, or unspoken reasons that may include:

* I am used to working on my own and am at my most productive on my own
* I like being able to work at my own pace, taking breaks when I need to
* I want to listen to music
* I don't like watching someone else program, I like being in control

## Why Pair Programming works

But the benefits of pair programming are being preached the world over.  Despite my own initial hate of pair programming I have experienced these first hand.  Don't take my word for it, you can even take a look at the <a href="http://collaboration.csc.ncsu.edu/laurie/Papers/ESE%20WilliamsPairProgramming_V2.pdf" target="_blank">research paper from Laurie Williams and Alistair Cockburn</a>.

### Far Fewer Defects

Code that is written by pair programming tends to have far less defects, from silly typo's through to more complex logic errors.  Programming is highly susceptible to human error, and having an extra set of eyes that check everything you do really helps.

I have personally noticed phenomenon where after pair programming, everything just works, and I cannot count the number of times the co-pilot has caught something that would have proved costly later.

We all know that defects can prove incredibly expensive - so this fact can help negate the on paper productivity loss.

### Code that is easier to read

Fun fact: All code is read far more than it is written and edited.  Another fun fact: one of the people that have to read your code will probably be you, 12 months from now.  Ever seen some code, think that it looks like the inside of the TARDIS, only to realise you wrote it?

Code needs to be maintainable and extendible, and readability is one of the number one factors that contribute to this.

When pair programming, the developer has to write code for another person to understand.  This subtle but powerful shift in mindset continually encourages the code to being easier to understand and more readable by other developers.

### Far less technical debt

No developer will admit to doing hacks or code that they aren't proud of; but it is a simple fact that often, when writing code, we are human and we may take dirty shortcuts.  We may intend to fix them up later but then we find a YouTube video of a cat playing the piano.

I can attest that the temptation to do this when someone is watching over your shoulder is greatly reduced!  You both exert a healthy pressure on each other to do everything properly.

### Knowledge share goes through the roof

I have never learnt as much as when I started pair programming.  Different developers have different experiences, knowledge, and techniques to solve things. There will be a wide range of knowledge and experience of your code base as well.

There is no better way to share this knowledge around and dramatically increase the collective skill of your team than pair programming.

### No more key man dependency

Ever had the experience where a developer called in sick, and so the story they were working on becomes completely blocked?  Or the only person that knows how a part of the system works is away?

With pair programming, you have one, potentially many, backup developers.

### A Truly Cross Functional Team

The most productive teams are ones where everybody on the team can do a little bit of every thing.  This is not to say that we don't have our specialists; some people will always be better at front end, others at the database, etc.  However - the team will be at its most effective when everybody is capable of at least understanding every part of a story themselves.

We learn best by doing, and what better way to enable this kind of capability than pair programming.  Have the QA's pair with the developers, the back end developer work on Javascript with the front end developer.  Cross functional teams are not just a dream!

### Maintained Focus

You might think that with two people at one machine, they could easily distract each other.  In fact the complete opposite is true - they actually keep one another with an intense focus on the task at hand.

It is far more likely that a solo developer will get distracted by checking emails, browsing, etc.  I noticed that when pairing, we have a laser like focus on the task at hand, with neither person taking the time to deviate.  This is why pairing for a long period of time is mentally draining on both developers.

### Shared Ownership of the Code

This benefits the developers, reducing the chance for a blame driven development culture where people are named and shamed for making mistakes.  Sharing ownership of your code with another developer or 3 increases the feeling of a shared, team ownership of the code.  More team work, more better.

## How to pair program effectively

So we have established some of the key benefits to pair programming, and now we want to try it.  Like everything, there are patterns to maximise success for pair programming.  Let's run through some of these now.

### Rotate the Programmer Frequently

You get the most benefit from pair programming when both the programmer and the co-pilot are engaged and focused.  As the co-pilot, it can be easy to drift off to never never land, or to check your phone, however.

To counteract this, the co-pilot will be most engaged when they feel that they are about to take over.  Ways of doing this include ping pong pairing where one person writes a test and another person writes the implementation, or a simple 20 minute egg timer.

### Rotate Pairs Regularly

You get the most benefits from pair programming by working with a wide range of different people.  This also maximises the knowledge share.

We need to really encourage people to swap partners often though to get true knowledge share and a cross functional team.

An extreme example, success has been reported with so called promiscuous pairing.  This is where the entire team pair programs, and all of the pairs must swap partners on a timer, say every 1.5 hours.  Interestingly, it is the most experienced developer that must move on.

<figure>
<img src="../images/posts/2015-02-02-promiscuous.jpg">
<figcaption>By the time Cindy realised she had misunderstood "promiscuous pairing", it was too late</figcaption>
</figure>

### Works best with complex code

Pairing when designing new, or complex code has a lot of benefits.  Sometimes though, as developers we will always have boring scaffolding code that we have to write.  Sometimes I would sit down for the day and see the next 500 lines of simple code that I had to write.

Tasks like this can be monotonous when pairing, and may enjoy fewer benefits from it.

### Don't force the issue

True to any agile team, we should let the teams self manage and not force any rules on them.  Rather than force them to have to pair all the time, let the developers decide when they want to pair program.

They may not want to pair 100% of the time, as the required focus is exhausting.  They may not want to pair on very simple tasks; then again they may want to.

Pair programming may need a slight kick start at the beginning, but it is ultimately a team decision.

## Summary

Pair programming has a large number of benefits.  No body likes it when they hear about it, or even after their first few sessions.

In the true spirit of agile, try it for a few sprints or weeks.  Stick with it, try it, keep it fun.  Give promiscuous pairing a try.  And after the team has tried it, let them decide how they think they operate the most effectively.

It is no guarantee, but from what I have seen, after most developers have tried pair programming, when it clicks they end up loving it and don't want to work any other way.







