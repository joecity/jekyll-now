---
layout: post
title: Agile vs Going Faster
excerpt: "There is often a large focus on Agile increasing speed and productivity... but does it?  And is this healthy?"
modified: 2015-03-25
tags: [agile, speed, productivity]
comments: true
image:
  feature: posts/2015-03-25-header.jpg
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

I am a little happy, and a little sad, because I have just come back from a really great snowboarding trip.  I would class myself at intermediate level - I can make my way down a mountain, not at Olympic speeds, but fast enough to really hurt a skier if they happened to randomly turn into my path down the mountain as they seem to like to do.

## Agility is more important than speed

The thing is, I have been able to go quite fast on a snowboard pretty early on - I could face straight down the mountain and didn't have too much fear of going fast.  If I had to change direction when going at speed though - let's just say I am lucky that situation never came up :)

Morale of the story is, going fast on a snowboard is pretty dangerous if you do not also have the ability to be agile - or have the ability to make turns and change direction *quickly*.  Once you have mastered being agile, *then* you can think about going fast.  It's much safer for you, and everyone else on the mountain that way!

It is no different with Software Development.  The very definition of agile means that the software we produce should be able to quickly change direction as the business needs it to.  Once we have that mastered, then we can end up going fast.

Unfortunately though, in the software world, just like me on a snowboard, it is very easy to go fast without actually being agile - which can be dangerous for the team, the business, everyone involved.

## How software development can be fast but not agile

Developers have been masters of going fast using time tested techniques like these:

### Drop some automated tests

Automated tests take time to write, and anyway the business won't know if we don't do them, let's save some time!

### Let technical debt mount up

The business cannot see the code underneath the software, they only see the features we implement on the surface.  We can quickly implement some features, leave the code a little messy, but the business will love us for implementing what they need quickly!

### Work longer hours

If we stay a little later and work through lunch, we can deliver more... After all the business doesn't make money from sustainable pace and developer happiness!

### Form information silos

A developer will be more productive working on a story by themselves so that they don't have to waste time talking to anyone else.  Let's put the most suitable people on each task and not worry about knowledge share and T-shaped skills.

## The risks of speed without agility

Sometimes these techniques might be necessary; perhaps we have a prototype to deliver, or a legal compliance deadline to make, and speed is the most important factor.  This should be the exception however.

If we miss some automated tests, the feature we just implemented will become a breeding ground for bugs.  Letting technical debt mount up will slow down the speed of development exponentially in the long run, culminating with the only too common "big rewrite".  Working at unsustainable paces leads to lower quality work, less developer happiness, higher staff turnover.  Knowledge silo's might seem faster in the short run but fosters an environment of an unproductive group of individuals rather than a high performing team.

It might seem like we gain some initial speed, but in the mid to long term, the problems mentioned above are serious enough that they can and they will bring the pace of development down to a grinding halt.

## Warning signs of harmful speed

You might already be in this cycle if you notice some of these things:

* Velocity makes a steady decline
* The delivery team constantly exhibits signs of pressure; working through lunch, staying late, not interacting and working together very much,  drop in morale
* Defect rates start to soar, old defects continually reappear, it is common for defects to lie undetected for a long time

## Bring the focus back to agility

Scrum masters, agile coaches and managers, it is our responsibility to ensure that the team remains committed to being agile, and not just fast.  Delivery teams can easily fall into the trap of focusing on speed; in fact they are incentivised to.  Delivery teams don't get praise for invisible achievements like writing high quality, well tested software.  They get praised for delivering features tangible to the business, regardless of the level of quality that lies under the surface.

This means we might need to do more than just encourage delivery teams to focus on quality.  Teams are praised and rewarded for their output, perhaps they should also receive recognition for high quality practices.  Some ideas on how we could encourage this:

* Keep track of the number and quality of automated tests.  There should be at least one test per behaviour, and tests should be small, fast, and not brittle
* Run code analysis tools to check the code remains simple and clean, with low complexity, and without obvious flaws and duplication
* Place high importance on continuous integration and automated deployments; measure how quickly and easily a feature can be developed, regression tested, demoed and released
* Encourage pair programming

Perhaps we could measure such quality metrics, and advertise the teams code quality success stories.  Emphasise, highlight, and celebrate a culture where high quality is maintained, and not just high speed.

## Summary

It is too easy to focus on speed alone.  We don't want to be that snowboarder who ploughed into a tree going 70kms an hour because we could go fast but could not turn when we needed to.

Once a team has established good agile practices and a culture of high quality output, the speed increase will come naturally, and more importantly safely and sustainably.  Ultimately, this is a much better result for the business that is investing a lot of money into their software.