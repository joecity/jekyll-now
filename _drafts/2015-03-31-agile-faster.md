---
layout: post
title: Agile makes you go faster... or does it?
excerpt: "There is often a large focus on Agile increasing speed and productivity... but does it?  And is this healthy?"
modified: 2015-03-31
tags: [agile, speed, productivity]
comments: true
image:
  feature: posts/2015-03-31-header.jpg
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

I am a little happy, and a little sad, because I have just come back from a really great snowboarding trip.  I would class myself at intermediate level - I can make my way down a mountain, not at Olympic speeds, but fast enough to really hurt a skier if they happened to randomly and decisively turn into my path as they seem to like to do.

<figure>
	<img src="../images/posts/2015-03-31-snowboarding.jpg">
	<figcaption>Luckily for this skier, I manage to avoid collision</figcaption>
</figure>

## Agility is more important than speed

The thing is, I have been able to go quite fast on a snowboard pretty early on - I could face straight down the mountain and didn't have too much fear of going for it.  If I had to change direction when going at speed though - let's just say I am lucky that situation never came up back then :)

Morale of the story is, going fast on a snowboard is pretty dangerous if you do not also have the ability to be agile - or to make turns and change direction *quickly* when you need to.  Once you have mastered being agile, *then* you can think about going fast.  It's much safer for you, and everyone else on the mountain that way!

It is no different with Software Development.  The very definition of agile is not just that we can develop faster, but that the software we produce should be able to quickly and easily change direction as the business needs it to.  Once we have that mastered, then we can end up going fast.

Unfortunately though, in the software world, just like me on a snowboard, it is very easy to focus on going fast without actually being agile as well - which can be dangerous for the team, the business, everyone involved.

## How software development can be dangerously fast

Developers have been masters of going fast using time tested techniques like these:

### Drop some automated tests

Automated tests take time to write, and anyway the business won't know if we don't do them, let's save some time!

### Let technical debt mount up

The business cannot see the code underneath the software, they only see the features we implement on the surface.  We can quickly implement some features, leave the code a little messy, but the business will love us for implementing what they need quickly!

### Work longer hours

If we stay a little later and work through lunch, we can deliver more... After all the business doesn't make money from sustainable pace and developer happiness!

### Form information silos

A developer will be more productive working on a story by themselves so that they don't have to waste time talking to anyone else.  Also, let's assign the most qualified person for each story and not worry about knowledge sharing and T-shaped skills.

## The risks of speed without agility

Sometimes these techniques might be necessary; perhaps we have a prototype to deliver, or a legal compliance deadline to make, and speed is the most important factor.  Situations like this should be the exception however.

If we miss some automated tests, the feature we just implemented will become a breeding ground for bugs.  Letting technical debt mount up will slow down the speed of development exponentially in the long run, culminating with the only too common "big rewrite".  Working at unsustainable paces leads to lower quality work, less developer happiness, higher staff turnover.  Knowledge silo's might seem faster in the short run but fosters an environment of an unproductive group of individuals rather than a high performing team.

With all of these techniques it might seem like we gain some initial speed, but in the mid to long term, the problems mentioned above are serious enough that they can and they will bring the pace of software development down to a grinding halt.

## Warning signs of harmful speed

There may already be an unhealthy focus on speed if you notice some of these things:

* Velocity is very stagnant, and starts to make a steady decline
* The delivery team constantly exhibits signs of pressure; working through lunch, staying late, not interacting and working together very much,  morale is very low
* Defect rates start to soar, old defects continually reappear, it is common for defects to lie undetected for a long time, confidence in the software starts to drop and releases start to take longer and longer

## Bring the focus back to agility

Scrum masters, agile coaches and managers, it is our responsibility to ensure that the team remains committed to being agile, and not just fast.  Delivery teams can easily fall into the trap of focusing on speed; in fact they are incentivised to.  Delivery teams don't get praise for invisible achievements like writing high quality, well tested software.  They get praised for delivering features tangible to the business, regardless of the level of quality that lies under the surface.

This means sometimes we might need to do more than just remind delivery teams to remember to focus on quality.  Teams are praised and rewarded for their output, perhaps they should also receive recognition for high quality practices.  Some ideas on how we could help encourage this:

* Keep track of the number and quality of automated tests.  There should be at least one test per behaviour, and tests should be small, fast, and not brittle (they should aid refactoring not hinder it, more on <a href="../tdd">testing strategies here</a>)
* Run code analysis tools that can check the code remains simple and clean, with low cyclomatic complexity, and without obvious flaws and duplication
* Place high importance on continuous integration and automated deployments; measure how quickly and easily a feature can be developed, regression tested, demoed and released
* Encourage pair programming

Perhaps we could measure such quality metrics, and advertise the teams code quality success stories.  Emphasise, highlight, and celebrate team achievements where high quality is maintained.  Tell and even demonstrate the automated test coverage, announce how many builds and releases the team can now achieve each day, raise awareness when the team refactors and cleans a significant portion of the code base and say how much faster the team can now make updates to that business rule.

## Summary

It is very easy, and often the norm, to focus on speed alone.  We don't want to be that snowboarder who ploughed into a tree going 70kms an hour because we were going really fast but could not turn when we needed to.

Once a team has established good agile practices and a culture of high quality output, the speed increase will come naturally, and more importantly safely and sustainably.  This means instead of having the software devolve into a slow, unmaintainable system that can hold the business back, we end up with a system that will continue to deliver value and an adaptable, competitive edge that can continue to drive the business forward.