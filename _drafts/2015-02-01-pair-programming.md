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

## Why we should still try it

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

## Summary

Pair programming might be a hard sell to start with, but it has gotten popular because it has a large number of benefits.  Are you now interested to try it?  My next post will run through some key tips on how to get the most out of pair programming.