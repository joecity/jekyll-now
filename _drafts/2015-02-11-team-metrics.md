---
layout: post
title: Metrics in an Agile team?
excerpt: "Lines of code per developer, function points... metrics have never really worked out that well for Software Development"
modified: 2015-02-24
tags: [techtrack, team, metrics]
comments: true
image:
  feature: posts/2015-02-24-header.jpg
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

An interesting question that often gets asked is "what metrics should we use to measure the performance and progress of a team"?

I am not talking about measuring the product.  Innovation accounting, actionable metrics, outcomes, impacts, whatever you may be using, are ultimately the most important measure and motivator for a team.  This is for another post.

I am talking about a step earlier than that, measuring how the team is performing and working together.  Measuring performance of developers has always been a difficult task, and it doesn't get any easier with the modern day collaborative, self organising, cross functional agile team.

So what things should be keep in mind?

## Beware: the Heisenburg Effect

Noble-laureate physicist Werner Karl Heisenberg stated that in particle physics, the very act of observing alters the position of the particle being observed.  To quote another physicist (these guys seem to be quite profoundly clever) on this topic:

> Tell me how you measure me, and I will tell you how I behave - Eli Goldratt

So the mere act of observing and measuring metrics will most likely produce side effects in how the team may behave.  And I suppose in a way, that may be some of the motivation for people wanting metrics in the first place.  We just need to remember that all metrics can be gamed and can cause counter productive side effects.  Measuring defect rates?  We could be encouraging the team to hide real defects!

Metrics are a sharp tool and need to be closely inspected.  Most importantly they need to come from place of being transparent and helpful for the team to improve.

<figure>
<img src="../images/posts/2015-02-24-kpis.jpg">
<figcaption>Although well intentioned, newly married Jimmy did not yet know the world of pain his love of metrics were about to take him to</figcaption>
</figure>

## Beware: using estimates or velocity to measure productivity

So with the above said, I have already written a post expressing my thoughts on <a href="../posts/estimate-abuse">using estimates and velocity as a measurement of productivity</a>.

In a nutshell, estimates are a quick and easy tool for the team to use.  It is fine for a team to track the velocity themselves so they can inspect and adapt on their team process.  Place too much importance on these figures though, or let them get into the wrong hands, and they can quickly lead to toxic results.

## Metrics: the goals of an agile team

One of the aims in agile is to get a high performing team.  This should take greater importance than encouraging high performing individuals.  Truly collaborative teams will in the long run be more productive and produce better quality work than they could as the sum of individuals.

So, we want to encourage things like:

* Team work, collaboration, swarming together on to stories
* Cross functional skills
* Focus on high software quality
* Less defects
* Reduced time to market for new features
* Empowerment and encouragement towards being a self managing team

All of these things will lead to higher team productivity.  The tricky part is, that some of them may actually lead to a short term *drop* in productivity.  Things like improving cross functional skills, or having a higher focus on software quality will actually seem slower right now, but will pay dividends later on.

We want to encourage that uber developer not to put his headphones on and furiously type out code alone for 5 days while hardly breathing, but to contribute, share and impart his skills with the rest of the team.

## Ideas for metrics that can help encourage the goals

If you must use metrics, or want to try and work on some of the goals above, these are some idea's that I have tried to varying levels of success.

Note that in the best case scenario, that mature self managing teams should be able to decide their team metrics themselves; I like to call them team goals.  Sometimes, they may need some ideas to help get the ball rolling; the important thing is to have buy in from the team.

If you are in a company that must have individual performance reviews (sigh), you could also use these team goals to access how much each individual has contributed towards them.

### What was the average time from when a story was picked up to when it was done?

Story cycle time.  As an agile team, our aim should be to get the stories that are in progress to done as quickly as possible.  It is better to have 9 stories done, than 10 stories that are 90% done.

This means our stories should be nice and small.  It also means when a team member is freed up, before they pick up a new story they should first check - can I help, and swarm on any stories in progress to get them over the line?

A fun twist on this metric is to give your stories a mini life span.  When a story is picked up, put on a sticker of a baby; it's just been born.  As the story stays on the board it can grow to a child, then an adult, then an elder, then a grave stone.  The goal might be to minimise the number of "deaths"!

### How many stories were pair programmed?

Pair Programming is one technique that brings many benefits as outlined in my past post the <a href="../pair-programming">reasons to hate or love pair programming</a>.

The team may want to introduce pair programming but struggle to remember to do it.  Metrics like how many stories were pair programmed, how many different pair programming partners were there, etc. might help keep the goal in mind.

### The average number of people that worked on each story?

Swarming is a very powerful technique where multiple people can "swarm" onto a story to get it done.  Perhaps multiple developers worked on it at once, or had huddles on major tech questions, or multiple people helped to test it.

It might not be reasonable to have the entire team work on every story (though this can be an interesting team exercise to try), however a light metric here might help encourage collaboration on stories.

### How many times did someone on the team work outside of their skill of expertise?

Cross functional, or "T shaped" teams, are the most productive and predictable teams.  Yes people will always have their primary skill set - but it helps if everyone has a vertical skill set all the way though the product; "T shaped" skills.

Why T shaped skills?  Cross functional teams can be much more flexible; if the board is full of front end stories, or QA stories, everyone on the team can swarm on those stories rather than having a resource bottleneck.  Also when working on stories, it is beneficial if everyone has knowledge of the full vertical stack - they can better align their work, and they don't have to throw anything over the fence or wait for the back end dev to become available.
{: .notice}

To get to cross functional teams is very difficult though.  It puts people outside their comfort zones and can really slow down output in the short run.  To encourage this behaviour we may want a metric to show whether we are making progress in becoming more cross functional.

### How many new defects have we created - or recreated?

It is likely the team will already be trying their best to minimise defects.  Sometimes however, the team may be pushing for speed of delivery over things like regression tests, or cleaning up their technical debt.  Too much of this results in much lower agility in the long run, so we want to make sure we stay focused on following good XP practices and having good clean code.

Ideally automated tests should limit how many new defects we introduce.  They should also stop defects that we have fixed from reappearing.  If new defects keep coming up, or past defects keep coming back, we may want to try and make sure we are investing enough time in automated tests and to improve quality in the long run.

### How often are we releasing?

Releasing often is a great way to stay agile; it means the cost of releasing is low and efficient, and means that code is constantly being integrated.

It also means assumptions and ideas can constantly be validated in front of customers.  I went to a talk by lastminute.com, and they gave an example where they could validate a simple idea of presenting the cheaper, value for money hotels to people who were searching for a room for that very same night.  Their ability to release to production quickly and easily meant they could release a quick experiment in a few days, and they saw an increase in sales of 419%.

A metric that measures the frequency of releases might help to bring team focus towards tools and practices that can help enable success stories like this, like learning script automation or using deployment tools like Octopus Deploy.

### Team Morale

<a href="http://www.fastcoexist.com/3028160/happy-workers-are-more-productive-science-proves-it" target="_blank">Happy people are (12%) more productive people</a>.  Above all, we want to ensure that the *team morale* remains happy and productive.  The way to measuring this is another topic in itself.  You can leverage one of the tools like the <a href="https://www.happinessmetric.com/" target="_blank">happiness metric</a>, or ask pertinent questions in the retrospective, or even just have a small paper form team members can fill in and put in a box.

## Summary

These are just some ideas on metrics that we might consider using for our team.  It is by no means exhaustive or bad-side-effect-proof, and your team may likely think of many more team goals they may want to try.  It is important to let the team buy in with these, rather than push goals on to them.  And remember, metrics need to come from a place for positive change; inspect and adapt as often as needed!