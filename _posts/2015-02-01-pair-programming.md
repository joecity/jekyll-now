---
layout: post
title: Reasons to Hate or Love Pair Programming
excerpt: "Two Developers, one computer.  How can that be justified?"
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

I begin with a warning - that almost everyone hates pair programming... at first :)  I know I did!

I am talking about the XP practice where you have two developers at one machine.  One developer becomes the driver at the keyboard, and the other observes and navigates, being the copilot.

## Why the Business / Managers hate it

The very notion of it sounds ridiculous - two expensive developers at one machine?!  So we *halve* our potential developer output?

You wouldn't give one hammer to two builders, so why should developers be any different.

## Why Developers hate it

<figure>
<img src="../images/posts/2015-02-01-copilot.png">
<figcaption>At that moment, Rodger instantly hated both Pair Programming and Steve</figcaption>
</figure>

Nobody... ok aside from the odd show pony... nobody likes to be watched while they work.  We have all had the experience where we know we are good at something, but the moment someone watches, we feel like someone just whipped our pants down in front of the school.  Which most people don't like.  Programming with someone watching is no different, and that awkward feeling sticks for a while.

There are a number of other reasons, spoken out loud or not, that may include:

* I am used to working on my own and am at my most productive on my own
* I like being able to work at my own pace, taking breaks when I need to
* I want to listen to music
* I don't like watching someone else program, I like being in control
* Someone else will just slow me down

## Why should we try it?

But the benefits of pair programming are being preached the world over.  Despite my own initial hatred of pair programming I have experienced these benefits first hand and have come to realise that pair programming can be very powerful.


### Far Fewer Defects

Code that is written by pair programming tends to have far less defects, from silly typo's through to more complex logic errors.  Programming is highly susceptible to human error, and having an extra set of eyes that check everything you do really helps.

I have personally noticed the phenomenon where after pair programming, everything just seems to work without a hitch.  And I cannot count the number of times the co-pilot has caught something that would have proved costly later on.

We all know that defects can prove incredibly expensive the longer they live - so finding them immediately can help negate the on paper productivity loss of pairing.

### Code that is easier to read

Fun fact: All code is read far more than it is written and edited.  Another fun fact: one of the people that have to read your code will probably be you, 12 months from now.  Ever seen some code, think that it looks like the inside of the TARDIS, only to realise you wrote it?

When we write code, everything is really clear to us at that time, even though we may be making it unnecessarily complex.

When pair programming though, the developer has to write and design code for another person to understand right there and then.  This subtle but powerful mindset continually encourages the code to be easier to understand and more readable by other developers.  Readable, maintainable code pays dividends later on.

### Less technical debt

No developer will admit to doing hacks or code that they aren't proud of; but it is a simple fact that often, when writing code, we are human and we may take dirty short cuts.  We may intend to fix them up later but then we get sent a YouTube video of a cat playing the piano.

I can attest that the temptation to cut corners or to skip some tests when someone is watching over your shoulder is greatly reduced!  You both exert a healthy influence on each other to do everything well.

What is  'Technical Debt'?  It is the dreaded 'T' word that Developers always bring up and everyone else likes to turn a blind eye to.  The fact is, technical debt is a very real threat to your software.  It means that while your software works, underneath the surface in the depths of the code there are some problems that should be addressed.  It might mean you have missing regression tests, or some inefficient code, or just ugly code that is harder to read and update than it should be.  Let this build up too much, and it can cripple the ability to make changes to your software.
{: .notice}

### Knowledge share goes through the roof

My rate of learning went through the roof when I started pair programming.  Different developers have different experiences, knowledge, libraries, and techniques to solve things.  There will be a wide range of knowledge and experience of your code base as well.

There is no better way to share this knowledge around and dramatically increase the collective skill of your team than pair programming.

### No more key man dependency

Ever had the experience where a developer called in sick, and so the story they were working on becomes blocked?  Or the only person that knows how a part of the system works is away?

With pair programming, you have one, potentially many, backup developers to call on.

### A truly cross functional team

The most productive teams are ones where everybody on the team can do a little bit of every thing.  This is not to say that we don't have our specialists; some people will always be better at front end, others at the database, etc.  However - the team will be at its most effective when everybody is capable of at least understanding every part of a story themselves.

We learn best by doing, and what better way to get closer to a cross functional team than pair programming.  Have the QA's pair with the developers, the back end developers work on Javascript with the front end developers.

It might seem slow at first, however the combined learning and capability will lift your team productivity in the long run.

### Heightened productivity from maintained focus

You might think that with two people at one machine, they could easily distract each other.  In fact the complete opposite is true - they actually keep one another with an intense focus on the task at hand.  As a side benefit, others in the office are also far less likely to interrupt pair programmers.

It is far more likely that a solo developer will get distracted by checking emails, their phone, browsing, etc.  I noticed that when pairing, we have a laser like focus on our goal, with neither person taking the time to deviate from it.  This is the place affectionately called "the zone" where developers are in a hyper productive state, producing much more and much better work than normal.  Pairing makes it easier to get in there and stay there.  This is why pairing for a long period of time is mentally draining on both developers.

### Shared ownership of the code

This benefits the developers, reducing the chance for a blame driven development culture where people are named and shamed for making mistakes.  Sharing ownership of your code with another developer or 3 is actually a great feeling.  It makes the team feel collectively responsible for the code rather than just individuals.  More team work, more better.

### More innovative, creative solutions

The sum of the pair is greater than the sum of the parts.  This is particularly true of programming.  Combining the experience, knowledge and brain power of two developers will likely produce a far better solution than either developer could on their own.

## Summary

Pair programming might be a hard sell to start with, but there is a reason that it is popular.  It brings a huge number of benefits.

Are you now interested to try it?  My next post will run through some key tips on how to get the most out of pair programming.

If you want further reading on the subject, you can take a look at the <a href="http://collaboration.csc.ncsu.edu/laurie/Papers/ESE%20WilliamsPairProgramming_V2.pdf" target="_blank">research paper from Laurie Williams and Alistair Cockburn</a>.
{: .notice}