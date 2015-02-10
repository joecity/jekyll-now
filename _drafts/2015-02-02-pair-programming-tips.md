---
layout: post
title: Pair Programming Tips
excerpt: "How to get the most value from pair programming"
modified: 2015-02-02
tags: [agiletrack, agile, product owner]
comments: true
image:
  feature: posts/2015-02-02-header.jpg
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

## How to pair program effectively

In the <a href="../pair-programming">Reasons to Hate or Love Pair Programming</a> post we ran through some of the key benefits of pairing.  This post will try to help with some suggestions to get the most out of pair programming.

### One driver, one co-pilot

Let's start with the basics.  In my experience, pair programming is at its most effective when one developer is the driver with the keyboard and mouse, and the other developer is observing as the copilot.

As the driver, you have the obvious job of writing the code.  At first you will feel self concious and slow - but this feeling will go.  Try to talk out loud what your thought processes are so the copilot can follow.  The aim is to keep an open channel of communication and collaboration as you code.

As the copilot, you want to stay focused on what the driver is typing out.  Resist the urge to take over the keyboard.  Your job is to look out for any mistakes, and think about the bigger picture of how this will integrate in with the rest of the system, if the design could be improved, if the code is clear and understandable, etc.  You want to concentrate on the latter tasks here; think more about the big picture and don't be quick to jump in and correct typo's the moment they are made, that is just annoying.

### Rotate the Driver Frequently

You get the most benefit from pair programming when both the programmer and the co-pilot are engaged and focused.  As the co-pilot, it can be easy to drift off to never never land and end up clocking high scores in Flappy Birds on your phone.

To counteract this, the co-pilot will be most engaged when they feel that they are about to take over driving.  Ways of doing this include ping pong pairing where one person writes a test and the person writes the implementation, or just using a simple 20 minute egg timer.

### Rotate Pairs Frequently

You will learn the most from pair programming by working with a wide range of different people.  This also maximises the knowledge share and will help towards having a cross functional team.

People will naturally gravitate to pair with who they are comfortable with, so swapping pairs may need a little encouragement.

An extreme example, success has been reported with so called promiscuous pairing.  This is where the entire team pair programs, and all of the pairs must swap partners on a timer, say every 1.5 hours.  In an effort to spread knowledge, it is the most experienced developer that must move on.

<figure>
<img src="../images/posts/2015-02-02-promiscuous.jpg">
<figcaption>By the time the team realised they had totally misunderstood "promiscuous pairing", it was too late</figcaption>
</figure>

### Works best with complex code

Pairing when designing new, or complex code gets the most benefits from collaborative intelligence.  As developers though, there will always be boring scaffolding code that we have to write.  I can recall sitting down for the day and being able to see the next 500 lines of simple code that I had to write.

Tasks like this can be monotonous when pairing, and may reap fewer benefits from it.

### Don't force the issue

True to any agile team, we should let the teams self manage and not force any rules on them.  Rather than put arbitrary pairing rules in place, let the developers try it first and then decide how and when they want to pair program.

They may not want to pair 100% of the time, as the required focus is exhausting.  They may not want to pair on very simple tasks; then again they may want to pair on all production code.

Pair programming may need a slight kick start at the beginning, but whether it sticks and when it should be used is ultimately a team decision.

### Workstation set up

Having a pair programming friendly workstation can help a lot.  Have two monitors, two keyboards and two mice.  Two mouses?  Two chairs would be great, and a flat desk that allows the developers to comfortably sit together.  Remember when you are the driver - you own the keyboard, so have it in front of you rather than twisting and contorting uncomfortably.

### Experience levels don't matter

A common question, is it best for a senior to pair with a junior, or for both developers to be at the same level?

I have found it is most productive when both developers are at a similar level.  This keeps both developers engaged and offers more opportunity for innovation and creativity.

That said, there will be benefits from pairing regardless of the experience levels of the pair.  A senior will impart knowledge with a junior, and a junior will challenge established ways of doing things of a senior.  The key is still to share the driver and copilot responsibilities evenly, even in this scenario.

### Scrum values: Respect

Having two intelligent, technical developers working side by side can introduce challenges.  Differences in design and opinions will come up with great reasons on both sides.  Without trying to sound patronising or to spell out common sense, remember that when this happens to do so with respect.  If you want to criticise some ones code, or question their decisions, do so in a way that you would like someone to do that to you.  Don't open with "I don't like that..." or "What are you doing?" or "Your code is so bad, Adobe could optimise it", rather try leading with less confrontational phrases like "Do you think we should..." or "What about if we...".

When pairing, try to be open to try the other persons suggestion.  Think about it this way, you will learn more if you regularly try other peoples suggestions and ideas.  Sometimes though both people may feel very strongly their own solutions.  In this situation use common sense; if it is a small decision, just pick one.  Flip a coin.

However for more critical decisions, it may call for a time boxed team huddle.  Call the team together, with the two proposal's and their reasons on either side.  Then use simple dot voting where the team picks a solution.  The key here is not to get too hung up in the debate; we are agile and empirical after all.  The team can always just pick what consensus thinks is the simplest solution, and inspect and adapt later.

### Try and standardise tools and conventions

Finally, before we begin pair programming, or programming in general, it is good to try and get some coding standards in place.  Having a simple team standard for naming conventions, camel casing, etc is a good idea for any development team.  If you can standardise tooling as well, great, but its not the end of the world if you have to spend some time switching IDE's and settings when swapping.

## Summary

No body likes pair programming when they hear about it, or even after their first few sessions.

In the true spirit of agile, try it for a few sprints or weeks.  Stick with it, try it, keep it fun.  Give promiscuous pairing a try.  And after the team has given it a good go, let them decide how they think they operate the most effectively.

It is no guarantee, but from what I have seen, after most developers have tried pair programming, when it really clicks and they experience the full benefits first hand they end up loving it and don't want to work any other way.