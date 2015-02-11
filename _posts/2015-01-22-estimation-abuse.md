---
layout: post
title: Estimates and velocity can be useful; but don't abuse them!
excerpt: "Abuse of estimates is wide spread and everywhere.  Break the cycle!"
modified: 2015-01-22
tags: [estimation, story points, velocity, agile, agiletrack]
comments: true
image:
  feature: posts/2015-01-22-header.jpg
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

There is an insidious little problem out there that I have seen almost everywhere to varying degrees.  It starts small; little things here and there, but can rapidly spiral out of control into a full blown abusive relationship.

I am talking about the misuse and abuse of the humble story point estimations, and it can range from just small grievances to soul destroying monstrosities.

## What are Story Point Estimations

Without getting too side tracked, Story Points are just one method a team may use to help give an indication of what they think the size and relative effort of their <a href="http://en.wikipedia.org/wiki/User_story" target="_blank">User Stories</a> might be.  These points usually go in a Fibonacci sequence (1,2,3,5,8) to show that as the estimates of User Stories get larger, there is more uncertainty about the exact size of that story.

Assigning estimates to stories are supposed to be a very quick exercise for the team, without too much time and detail going into it.  More of assigning a gut feel of relative sizes, if you will.

Teams may use any measure to indicate story sizes; T-Shirt sizes, story points, dog breeds, or they may choose not to estimate at all.  As it stands at the moment however, many teams do use Story Point estimations on the Fibonacci scale.  And this can open a tiny evil little door.

## Story Points get abused?

Oh yes they can and they do.  Story points can go from a seemingly inconsequential, harmless exercise to a dangerous black hole that threatens the sanity of any team.  Seen the below happen? I have, in the real world too.

* Managers who ask the team to estimate 6+ months worth of stories.  "Can you estimate these 237 stories so we can calculate when the project will finish?". *Back to big design up front*
* A Dollar per Point formula has been made to calculate cost per story.  "A point roughly takes this much time, time = money, WHAM".  *Those made up numbers are now used in a complicated budget?*
* Teams start being compared based on how many points they complete. *points are specific per team!*
* The bonus salary for the team was based on how many points the team could achieve. *points to measure productivity*
* Stakeholders start making demands on how many points a team must complete. *points became the focus over business value*
* Managers start micro managing and getting involved with estimating stories. *no one likes micro managing*
* Teams are told they have no choice, they have to estimate all stories using points because "management need the numbers". *the erosion of the self managing team*
* The backlog has some kind of "Point Lockdown", where nobody can add any more story points to the backlog as there is no more budget for them. *Back to big design up front*

Hopefully you can see the problems with these scenarios above. Interestingly, many of the problems listed sound like a subtle return to the Waterfall ways, where project managers micro manage and scope is planned and set in stone up front!

The simple story estimation can start with good intentions, but can be like a sneaky back door that allows the dirty old habits of Software Development in the 90's to creep back in.

<figure>
	<img src="../images/posts/2015-01-22-egg.jpg">
	<figcaption>Story point estimations - the hammer that can break the delicate Agile egg</figcaption>
</figure>

## The whole point of Story Points

Most of these problems are born out of a complete misuse of Story estimations.  So what are we supposed to get out of estimations and velocity?

### 1.  Help the Product Owner prioritise

Knowing about the size of a User Story will help the Product Owner prioritise, putting the smaller, higher value User Stories at the top.  Everyone wants a Ferarri - until they see the price tag.  Then they settle for Grandma's old moped instead.

### 2.  Help the team to Inspect and Adapt...

#### ...on a story

When teams add an estimation to a story, they have to think about it a bit more.  Stories that are too large and need to be broken down may be identified here.

#### ...on a sprint, or iteration
After a while, a team can calculate a velocity, or how many points the team can achieve in a certain period of time.  This can help the team when they plan how many stories they think they can forecast.

Velocity can also be useful to the team to diagnose whether they are continually increasing it, or inspect and adapt on how they are working if their velocity drops.

While teams may inspect and adapt on their velocity, allowing those outside the team to analyse it may lead to dire consequences.

## Caution: Don't use estimates and velocity as a measure of productivity
Measuring developer productivity has always been tricky, and velocity seems like a great measure to use; after all, the numbers are already sitting there begging to be put into an Excel chart.  In practice though, it does not work out too well.

Think about it; we are asking teams to quickly guess a number, and then use that number to measure their performance later on.  This will inevitably lead to a natural point inflation.  You may then feel a need to implement measures to help counteract this inflation, such as a tech lead or manager vetting all of the estimated points.

Putting too much pressure on the point estimations may also lead to excessively detailed, long drawn out planning sessions.

All of a sudden the estimation process has gone from a quick activity that can help the team, to a political, team morale destroying exercise.

## How can we avoid estimate abuse?

You may notice from the list of benefits of estimations, that all of the benefits are for the team.  Once these harmless little numbers leave the team though and get into manager / stakeholder hands, the benefits can fall drastically and the potential problems can go up.  This has led me to one rule I try to apply:

> Story Estimations are to be used and kept within the team *only*

Treat the estimates like code; code is usually kept internal to the team as the business doesn't understand it, treat estimates the same way.  When the team wants to communicate what they have completed or what they forecast next, just don't use the (made-up by the team) story point estimations.  List the business features, or goals, or actionable metrics, or impacts, or outcomes - anything other than points.

Disclaimer: There are no golden rules.  Perhaps you work in a great forward thinking environment where you can share the estimates everywhere and you don't get any problems coming back.  You must be in agile heaven :)
{: .notice}

## Summary

Estimates and velocity should be tools for the team only; they help the product owner prioritise the backlog, and they can help the team to inspect and adapt on the user stories and how they are working as a team.  Any other use of these numbers has very limited value and potentially harmful side effects.

A lot of time and energy can go into the estimate debate.  Do we estimate, do we not, do we use tasks and hours, do we use points, t-shirt sizes or Chuck Norris kick types?  If we keep points in their rightful place - as a tool to benefit the team only, then the debate should not be so strong and the burden not so heavy.  In the true spirit of empiricism, try each method.  Try points, try t-shirt sizes, try #noestimates... and let the team decide what works best for them.