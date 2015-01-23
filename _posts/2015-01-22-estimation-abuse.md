---
layout: post
title: Estimation Abuse
excerpt: "It is wide spread and everywhere.  Break the cycle!"
modified: 2015-01-22
tags: [agiletrack, agile, estimation, storypoints]
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

There is an insidious little problem out there that I have seen almost everywhere to varying degrees.  It starts small; little things here and there, but can rapidly spiral out of control into a full blown abusive relationship.  I want to write about this to help break the cycle now!

I am talking about Estimation Abuse.  The misuse and abuse of the humble story point estimations, and can range from just small grievances to huge developer soul destroying monstrosities.

## What are Story Point Estimations

Without getting too side tracked, Story Points are just one method a team may use to help give an indication of what they think the size and relative effort of their <a href="http://en.wikipedia.org/wiki/User_story" target="_blank">User Stories</a> might be.  These points usually go in a Fibonacci sequence (1,2,3,5,8) to show that as the estimates of User Stories to larger, there is more uncertainty about the exact size of that story.

Assigning estimates to stories are supposed to be a very quick exercise for the team, without too much time and detail going into the exercise.  More of assigning a gut feel, if you will.

Teams may use any measure to indicate story sizes; T-Shirt sizes, story points, dog breeds, or they may choose not to estimate at all.  As it stands at the moment however, many teams do use Story Point estimations on the Fibonacci scale.  And this can open a tiny evil little door.

## Story Points get abused?

Oh yes they can and they do.  Story points can go from a seemingly inconsequential, harmless exercise to a dangerous black hole that threatens the sanity of any team.  Let me give some examples of estimate abuse that I know has happened in the real world.

* Managers who ask the team to estimate 6+ months worth of stories.  "Can you estimate these 237 stories so we can calculate when the project will finish?". 
 * Back to big design up front
* A Dollar per Point formula has been made to calculate cost per story.  "A point roughly takes this much time, time = money, WHAM".  *Those numbers we slapped on just became part of a complicated budget*
* Teams start being compared based on how many points they complete *points to measure productivity*
* The bonus salary for the team was based on how many points the team could achieve *points to measure productivity*
* Stakeholders start making demands on how many points a team must complete *points start to become the focus over business features*
* Managers start micro managing and getting involved with estimating stories
* Teams are told they have no choice, they have to estimate all stories using points *the erosion of the self managing team*
* The backlog has some kind of "Point Lockdown", where nobody can add any more story points to the backlog as there is no more budget for them *Back to big design up front*

Hopefully you can see the problems with these scenarios above.  Most of them come from putting too much emphasis on estimations.  Interestingly, many of the problems listed sound like a subtle return to the Waterfall ways, where project managers micro manage and scope is planned and set in stone up front!  The simple story estimation can start with good intentions, but can be like a sneaky back door that allows the dirty old habits of Software Development in the 90's creep back in.

<figure>
	<img src="../images/posts/2015-01-22-egg.jpg">
	<figcaption>Story point estimations - the hammer that can break the delicate Agile egg</figcaption>
</figure>

## The whole point of Story Points

Most of these problems are born out of a complete misuse of Story estimations.  So what are estimations supposed to give us?

### Help the Product Owner prioritise

The Product Owner is the one who is in charge of writing User Stories and then prioritising them for the team.  Knowing about the size of a User Story will help the Product Owner with this task; the smaller, yet higher value User Stories should rise to the top.  Everyone wants a Ferarri - until they see the price tag.  Then they settle for Grandma's old moped instead.

### Help the team to Inspect and Adapt..

Teams can inspect an adapt in two ways.

#### ...on a story

When teams add an estimation to a story, they have to think about it a bit more.  Stories that are too large and need to be broken down may be identified here.  Also if a team is trying to plan how many stories they forecast they can do, points can help them determine this based on what they have achieved in the past.

#### ..on a sprint, or iteration
After a while, a team can calculate a velocity.  This is how many points the team can achieve in a certain period of time, on average.  This can help a team become more predictable; they can have some level of confidence to guess what they are capable of outputting.
It can also be useful to see if a team velocity starts to decrease; the team may want to inspect and adapt to try and address a supposed drop in velocity.

While teams may inspect and adapt on their velocity, allowing those outside the team to do the same may lead to dire consequences, see below.
{: .notice}


## Caution: Using estimations as a measure of Productivity
Measuring developer productivity is always tricky, and velocity seems like a great measure to use; after all, the numbers are already sitting there begging to be put into an Excel chart.  In practise though, it does not work out too well.

Think about it; we are asking teams to quickly guess a number, and then use that number to measure their performance later on.  This will inevitably lead to a natural point inflation.  You may then feel a need to implement measures to help counteract this effect, such as a tech lead or manager vetting all of the estimated points.  Putting too much pressure on the point estimations may lead to excessively detailed, drawn out planning sessions.  All of a sudden the estimation process has gone from a quick activity that can help the team, to a political, team morale destroying exercise.

## How can we practise safe estimates?

You may notice from the list of benefits of estimations, that all of the benefits are for the team.  Once these harmless little numbers leave the team though and get into manager / stakeholder hands, the benefits can fall drastically and the potential problems can go up.  This has led me to one rule I try to apply:

> Story Estimations are to be used and kept within the team *only*

Treat the estimates like code; code is usually kept internal to the team as the business doesn't understand it, treat estimates the same way.  When the team wants to communicate what they have completed or what they forecast next, just don't use the (made-up by the team) story point estimations.  List the business features, or goals, or actionable metrics - anything other than points.

## Summary

A lot of time and energy can go into the estimate debate.  Do we estimate, do we not, do we use tasks and hours, do we use points, t-shirt sizes or Chuck Norris kick heights?  If we keep points in their rightful place - as a tool to benefit the team only, then the debate should not be so strong and the burden not so heavy.  Let the team decide what to do, and in the true spirit of empiricism, try each method.  Try points, try t-shirt sizes, try #noestimates... and let the team decide what works best for them.