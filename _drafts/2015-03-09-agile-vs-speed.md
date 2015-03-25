---
layout: post
title: Agile vs Going Fast
excerpt: "Agile is often sold to increase speed and productivity... but does it?"
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

I have just come back from a snowboarding trip.  I would class myself at intermediate level - I can make my way down a mountain, not at Olympic speeds, but fast enough to really hurt a skier if they happened to randomly turn into my path down the mountain.

## Agility is more important than speed

The thing is, I have been able to go quite fast on a snowboard from about day two - I could face straight down the mountain and didn't have too much fear of going fast.  If I had to change direction when going at speed though - let's just say I am lucky that I never got in that situation :)

Morale of the story is, going fast on a snowboard is pretty dangerous if you are not agile - or have the ability to make turns and change direction *quickly*.  Once you have mastered being agile, *then* you can think about going fast.  It's much safer for you, and everyone else on the mountain that way!

It is no different with Software Development.  The very definition of agile means that the software we produce should be able to quickly change direction as the business needs it to.  Our software should be very responsive to the market place.  Once we have that mastered, then we can end up going fast.

Unfortunately though, in the software world, just like me on a snowboard, it is very easy to go fast without actually being agile - which can be dangerous for the team, the business, everyone involved.

## How software development can be fast but not agile

Developers have been masters of going fast for a long time using techniques like these:

### Drop some automated tests

Automated tests take time to write, and anyway the business won't know if we don't do them, let's save some time!

### Let technical debt mount up

The business cannot see the code underneath the software, they only see the features we implement up the top.  We can quickly implement some features, leave the code a little messy, but the business will love us for implementing their features quickly!

### Work longer hours

If we stay a little later and work through lunch, we can deliver more... After all the business doesn't make money from sustainable pace and developer happiness!

### Form information silos

A developer will be more productive working on a story by themselves so that they don't have to waste time talking to anyone else.

## The risks of speed without agility

Sometimes these techniques might be necessary; perhaps we have a prototype to deliver, or a legal compliance deadline to make, and speed is the most important factor.  This should be the exception however.

If we miss some automated tests, the feature we just implemented will become a breeding ground for bugs.  Letting technical debt mount up will slow down the speed of development in the long run; it can get so bad that the entire system will need the "big rewrite".  Working at unsustainable paces leads to lower quality work, less developer happiness, higher staff turnover.

In the short term we might gain speed, but in the mid to long term, the problems caused will bring the pace of change down to a grinding halt.

## Warning signs of too much focus on speed

* Velocity makes a steady decline
* The delivery team constantly exhibits signs of pressure; working through lunch, staying late, not interacting much, drop in morale
* Defect rates start to soar, old defects continually reappear, or are found very late in the process

## Bring the focus back to agility

Scrum masters, agile coaches and managers, it is our responsibility to ensure that the team remains committed to being agile, and not just fast.  Delivery teams can easily fall into the trap of focusing on speed; in fact they are incentivised to.  Delivery teams don't get praise for writing high quality, well tested software.

We might need to do more than just encourage delivery teams to focus on quality though.  Teams are praised and rewarded for their output, perhaps they should also receive recognition for high quality practices.  Some ideas on how we could encourage this:

* Keep track of the number and quality of automated tests
* Run code analysis tools to check the code remains simple and clean, with low complexity, and without obvious flaws and duplication
* Place importance on complete automation tools like continuous integration and automated deployments; measure how quickly and easily a feature can be released to production
* Encourage pair programming

Perhaps we could measure these, and advertise our success stories.  Emphasise, highlight, and celebrate a culture where high quality is maintained, and not just high speed.

## Summary

It is too easy to focus on speed alone.  We don't want to be that snowboarder who ploughed into a tree going 70kms an hour because we could go fast but could not turn when we needed to.

Once a team has established good agile practices, the speed increase will come naturally, and more importantly safely and sustainably.  This will result in a much better result for the business in the long run.