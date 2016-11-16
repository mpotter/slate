---
title: Able's Product Development Process

language_tabs:
  - Producer
  - PD
  - PE
  - Designer
  - Tech-Lead
  - QA-Manager
  - SE
  - QA-Tester

toc_footers:

includes:

search: true
---

# Introduction

<pre class="highlight Producer">
  <p>Hello Producer!</p>

  <p>Your focus is on communicating effectively with internal and external
  stakeholders. You reduce the risk of our work connecting effectively to
  the priorities of external Partners. You lower the cost of communication
  for our builders within the organization by normalizing and providing
  an easy conduit for requirements.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

This document is the source of truth for critical consistencies in our product
development process.

The goal of this document is to establish ownership and accountability for
every individual involved in building our products by clarifying their
responsibilities and establishing expectations _between_ roles. By focusing on
what's expected of you from other members of your project team at various
stages of our process, our goal is to get out of the way of you doing your best
work while putting you in a position to support your peers to do the same.

Products are not built by individuals; Products are built by teams. Here is
how our team works together.


# Planning

<pre class="highlight markdown Producer">
  <p>During Planning, your principal focus will be on identifying and
  communicating requirements. On Partner projects, this will primarily involve interviewing Partners to understand their needs.</p>

  <p>You will communicate the requirements and constraints that you identify
  from stakeholders to the Product Designer and Product Engineer in order for
  them to consider appropriate solutions.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

The goal of Planning is to translate assumptions about how a problem or set of
problems can be solved by a product into requirements for software development.

The process is successful when members of the Planning team spend less than 20%
of their time on the project in Production.

The risks to success in this process:

- The Planning team isn't thorough enough in specifying requirements and they
end up spending more than 20% of their time focused on this project in
Production clarifying requirements.
- The Planning team spends more time specifying and conditioning requirements
for a release than they would if they just designed and coded everything
themselves.

This section attempts to provide the Planning team with a framework for
achieving the goal while addressing those risks.

## Document problems

<pre class="highlight Producer">
  <p>Ensure that the problem statements reflect your understanding of the
  feedback and input that's been provided by all stakeholders. Play the role
  of the stakeholder when they're not in the room.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

We believe a product release should organize around a clear understanding of
what problems it's trying to address. Write down what problems you're solving
and, if helpful, which ones you're acknowledging but choosing _not_ to solve.
This will make future debate and discussion of scope and functionality much
more efficient because criticism can occur on the merit of a feature's ability
to solve a particular problem, not their general merit (which is much harder
and subjective).

Problem statements should be easily understood not just by the Planning team,
but every contributor to the product, including potential future contributors.
It's usually easier to understand problems that are organized _discreetly_ and
without too much dependency knowledge or overlap. Now is also a good time to
define any domain-specific language that you're running into since it'll be
fresh in your mind.

Recall that the primary purpose of your problem statements is for them to be
useful in prioritizing and iterating on functionality so, if you have important functionality in mind, work back to understand why you think it's important and
what problem it's solving.

Lastly, it's not always true that you will _only_ be solving problems that the
end-user of the product has. In some cases, the needs of a Partner, a sales
organization, or other stakeholders should be considered in the problem set as
well, if not as a principal concern.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Add problem statements to README
</aside>

### Areas of Investment

None

## Document KPIs

<pre class="highlight Producer">
  <p>You will be responsible for creating alignment around the effectiveness
  by which the KPIs represent success for the project. Essentially, these
  KPIs will form a scoreboard. So, whatever each of the stakeholders whose
  interests you represent consider success should be captured here.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

In Planning, you will form _assumptions_ about how the problems you've
identified are best solved. We ask you to document how you will measure your
success in solving the problems by explicitly identifying any of the
quantitative or qualitative metrics you'll use. We call these metrics "Key
Performance Indicators" (KPIs).

Each problem you're solving must have one or more KPIs.

The best KPIs should help settle debates on scope. One should be able to use
the KPIs to argue in favor or against scope on the basis of its impact on the
KPIs.

The best KPIs are subjective and easily understood without the need for
extensive domain knowledge. If you do have a KPI that doesn't relate to a
problem in an obvious way, take care to explain the relationship to an audience
that may not have extensive knowledge of the product's market.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Add KPIs to README
</aside>

### Areas of Investment

None

## Prototype critical assumptions

<pre class="highlight Producer">
  <p>Make sure you understand how the assumptions relate to the problems that
  the team is trying to solve. If this were your startup, and the stakeholders
  are your potential investors, you should be able to construct a flawless
  pitch for the features the team has come up with.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Here the team turns their attention from the problems the product is trying to
solve to the potential solution they'll build.

We consider any product feature that is required to address a problem you've
identified a *critical assumption*. Every other feature is called a "table
stakes feature." Another way to think about the difference between the two is
that critical assumptions are what makes the product uniquely valuable. Table
stakes features, on the other hand, _need_ to exist as to not detract from the effectiveness of the critical assumptions. In almost every case, you expect to
see a table stakes feature in many other products in many different domains.

We separate critical assumptions from table stakes features to help ensure the
Planning team spends 80% of their time in Planning on the "critical" features.
They should only spend 20% of their time making sure table stakes functionality
is captured.

We believe the best way to express these critical assumptions is by designing
features within a Prototype. We _only_ fall back to other mediums when there's
ambiguity that can't be adequately documented in Prototype form. This is rare
but when it happens it should be documented or otherwise clearly referenced in
the README.

These assumptions will inherently put forward a hypothesis as to how they are
going to solve the problems you previously documented. If you find yourself
prototyping functionality at this point that doesn't have a substantial impact
on one or more of those problems, either you're missing a problem or you're
designing a table stakes feature and you should file it away for later so that
you remained focused on what's critical for the product's success.

Another check you can perform to ensure what you're working on is a critical
assumption is to identify it's relationship to the KPIs. If a feature doesn't
relate to a KPI, you're most likely working on something that's less than
critical.

For benefit of your current and future team members working on this project as
well as the implementation of analytics, identify the metrics behind each of
these features and their relationship to the KPIs.

Lastly, try to have as few critical assumptions as necessary to solve the
problems you’ve outlined. If there are features that overlap in solving a
problem or problems, attempt to prioritize one of the features and push the
others to a future release. This will reduce the cost and speed at which you'll
be able to test your assumptions.

### Examples

- "Results from acceptance test runs should be posted to GitHub for successful
integration with a software engineer's workflow" (from Fino)

### Required Deliverables

<aside class="success">
  Articulate your critical assumptions by adding functionality to Prototype
</aside>

<aside class="success">
  List your critical assumptions in the README and their metrics for success
</aside>

### Areas of Investment

None

## Prototype table stakes features

<pre class="highlight Producer">
  <p>Ensure that the features identified here encompass any concern for
  functionality that the stakeholders have expressed. If you think a feature
  listed here _is_ critical from the stakeholders perspective, be sure to
  express that argument to the team to ensure they're considering the degree
  of its importance properly.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Any product feature whose implementation doesn't directly affect a problem
you've identified is a *table stakes* feature. Said differently, if the feature
just needs "to exist" but, the details for how it's implemented (assuming
general best practices are met) don't have an impact on how successfully the
problems are addressed.

These assumptions have minimal impact on directly solving the problems but
are important to either meet market expectations or otherwise avoid impacting
the effectiveness of the critical assumptions. They need to exist but the UX/UI
of how they’re implemented is not seen as a meaningful risk to testing the
assumptions.

Document _all_ of the table stakes features within the Prototype. Describe any
ambiguity that can't be adequately documented in the Prototype in the README.

You should invest as least as possible in these assumptions. You should work
hard to reduce scope. The solutions should have a strong bias to using
pre-existing patterns.

### Examples

- "A user needs to be able to recover their account if they forget their
password" (from Fino)

### Required Deliverables

<aside class="success">
  Add table stakes features to Prototype
</aside>

### Areas of Investment

<aside class="info">
  We think we can build a component library with common templates and patterns
  that could make the design and development of table stakes features faster.
</aside>

## Identify user paths

<pre class="highlight Producer">
  <p>Help make sure the team isn't missing anything. Provide a fresh set of
  eyes.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

A "user path" is a complete thought for something the user is able to
accomplish in the product. The goal of creating user paths is to break a
large software project into sensible units of work and thereby, reduce risk.

How user paths are best broken up is somewhat subjective. We believe the most
useful delineation considers the needed collaboration between all stakeholders.
Our best governing thought to this end is to consider paths from the
perspective of what a user is trying to accomplish with a feature or set of
features. We think this is the easiest framing for everyone to understand.

User paths should be one sentence and phrased as actions the user takes to
accomplish an objective. Please use sentence case for consistency and be
mindful of your spelling and grammar.

After a first pass on creating your paths, read them through a few times in
relationship to the prototype. Take care to explore the product interface by
interface and look for gaps. If you find that you've created a path that, once implemented, is only partially useful for the end user to accomplish something,
the path might be too small and/or should be combined with paths that unlock
the entire functionality that the user would need to accomplish the intended
outcome. If instead you can consider useful features within a path that are
discretely valuable to the user, the path is perhaps too broad or long.

Once you've settled on what all the paths are, traverse each path from the
perspective of the end-user from every possible entry point and precondition
and take every possible action. Each precondition and entry point, combined
with the branch formed by a sequence of actions form the "scenarios" within the
path.

Your goal in identifying scenarios is to articulate all the _boundary_ cases
for a path. Boundary cases are useful in specifying how the product should
behave when one of its inputs is at or just beyond its maximum or minimum
limits. By discovering and documenting all boundary cases within a feature, you
will have simulated the stress a user will eventually bring the product,
surfaced any needed clarification before software is written, and established
an actionable the outline for all the subsequent acceptance tests to be written.

_[To help generate scenarios and potentially boundary cases, consider the "best
practices" list we provide and include e.g. error state considerations, etc.]_

### Examples

TODO

### Required Deliverables

<aside class="success">
  List all user path titles and corresponding scenario titles in the README
</aside>

### Areas of Investment

None

## Identify prereqs

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Prereqs are units of work that are specifically called out as opportunities to
operate with higher concurrency in Production. We take care to identify prereqs
to avoid blockers in Production.

Generally, a prereq is work that "just needs to get done" that is usually best
completed by one person in a particular domain and is the dependency for other
work. Many prereqs concern developer operations and establishing technology
stack design patterns.

To identify prereqs, use our [list of common prereqs](#) and ask "what tasks
can and should be done by one or few individuals first that, once completed,
would mean the team could double in size and grow more productive?"

### Examples

- "Setup staging environment"
- "Set up CircleCI to run specs"
- "Document use of React and Redux"

### Required Deliverables

<aside class="success">
  List all prereqs in the README
</aside>

### Areas of Investment

None

## Identify topics

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

A "topic" is a collection of user paths and prereqs within a common area of the application that should, for efficiency's sake, be completed by a specific
engineer and/or in a specific sequence, e.g. Jane is the best person to develop
this feature because she has or will develop that other feature.

Topics should be as small as possible to encourage higher concurrency and
fewer dependencies. A topic is too big if a subset of its tasks can be
completed efficiently by two different engineers with the same skill-set. A
topic is too small if it excludes related functionality that, for efficiency's
sake, is best completed by that same engineer.

### Examples

- [Fino v1.0 topics](https://github.com/ableco/fino/issues?q=is%3Aissue+label%3Atopic+is%3Aclosed)

### Required Deliverables

<aside class="success">
  Organize all prereqs and user paths into topics in the README
</aside>

### Areas of Investment

<aside class="info">
  Tracks could help us better understand how topic dependencies affect the
  overall schedule and level of concurrency in Production.
</aside>

## Create issues

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Create GitHub issues for all topics, user paths, and prereqs. With each topic,
list all of its user paths and/or prereqs. With each user path, list all of the
path's scenarios.

Initially, these Issues will serve as placeholder units for requirements to be
documented within. For now, they're just high-level user flows with scenario
titles and prereqs. We create them now so that they can be flushed out as the
project progresses to contain all requirements for software development
(Scenarios, UI Flow, Acceptance Tests, Planning Estimate, Subtasks,
Implementation Notes).

When creating them, use a label system to delineate which issues have all the
requirements necessary to begin software development and which do not, e.g
`needs UI`, `needs acceptance test`, `needs planning estimate`.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Create GitHub issues for all user paths and prereqs
</aside>

### Areas of Investment

None

## Add Planning Estimates

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

We add a Planning Estimate to all of our work as a necessary prerequisite to
determining our staffing, schedule, and budget.

Make the estimate by considering the sum complexity of all the scenarios
within the path.

Use person-hours and consider the full-stack.

For any estimate that is longer than 4 hours, break the path out into
subtasks and ensure each isn't estimated to take longer than 4 person-hours.
Total the estimate for each of the subtasks to generate the Planning Estimate
for the entire path. Document all subtasks and any assumptions you have about
the implementation within the GitHub issue under sections called "Subtasks" and
"Implementation Notes" respectively.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Add a Planning Estimate to all GitHub issues
</aside>

### Areas of Investment

None

## Create Contributor Tracks

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

We use contributor tracks to determine the optimal sequence to address work,
reflecting intra and inter topic efficiencies.

By definition, all prereqs should come first, globally.

Use GitHub Milestones and GitHub Projects to document the intra and inter topic
Issue sequence.

Make note of which paths need to be completed in Pre-production. A completed
path requires an Acceptance Test and a UI Flow for all scenarios. The goal is
to maintain a greater than one week buffer between completed requirements for
user paths (Scenarios, UI Flow, Acceptance Tests, Planning Estimate, Subtasks,
Implementation Notes) and software development. Whichever software development
comes first should have these requirements prioritized in Pre-production.

When you're finished, update the Planning Dashboard (Forecast) to communicate
your staffing plan and timeline.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Organize all GitHub Issues into Milestones
</aside>

<aside class="success">
  Update Planning Dashboard (Forecast) with staffing estimates
</aside>

### Areas of Investment

<aside class="info">
  We're considering how a custom solution like Tracks could lower the cost of
  reinforcing our expectations for generating contributor tracks, estimates,
  and sequencing work.
</aside>


# Pre-production

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

The goal of Pre-production is to complete tasks that will allow for higher
quality software to be created with higher concurrency in Production.

The process is successful when more team members are introduced in Production
in a manner that doesn't compromise efficiency or software quality.

The risks to success in this process:

- The Pre-production team doesn't just focus on Prereqs and spends more time
than they need to before starting production.
- Production is staffed too early and team members end up blocked by missing
Prereqs.
- Code patterns are missing causing the code base to grow inconsistent and
more costly to develop and maintain.

## Start acceptance tests

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Write Acceptance Tests in Fino for whichever user paths and corresponding
scenarios have been prioritized for Pre-production.

Tests should specify pre-requisite application condition and data for each
scenario. Document this information in the GitHub Issue to be implemented
manually using Planter.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Completed Acceptance Tests for at least 1-week of software development
</aside>

### Areas of Investment

<aside class="info">
  Fino 1.0 requires you to write one test to cover all scenarios. Fino 2.0 will
  allow you to create multiple tests for each issue. In either case, each
  scenario within the path should have action/assertions testing that scenario.
</aside>

<aside class="info">
  We might explore a way for Fino to natively document prerequisite data in a
  way that Planter can execute directly.
</aside>

## Start UI Flows

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Design UI Flows for all user paths that are prioritized for Pre-production.

For any scenario within a user path that has a dramatic effect on the UI Flow,
design a UI Flow specifically for it.

Add UI Flows as links in the GitHub Issue.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Completed UI Flows for at least 1-week of software development
</aside>

### Areas of Investment

<aside class="info">
  A future version of Fino might make attaching UI Flows to scenarios much
  cleaner.
</aside>

## Complete prereqs

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Sometimes these will have a PR, sometimes they won't.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Complete and close all prereq issues on GitHub
</aside>

### Areas of Investment

None


# Production

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

The goal of Production is to create high-quality software reliably.

The process is successful when we deliver quality code on time.

The risks to success in this process:

- Misunderstood requirements
- Software development outpaces design and/or QA
- Bad estimates

## Complete UI Flows & Acceptance Tests

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Write Acceptance Tests for all user path scenarios in Fino. Tests should
specify pre-requisite application condition and data for each scenario.
Document this information in the GitHub Issue to be implemented manually using
Planter.

Design UI Flows for all user paths. For any scenario within a user path that
has a dramatic effect on the UI Flow, design a UI Flow specifically for it. Add
UI Flows as links in the GitHub Issue.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Design and attach all UI Flows to all user paths
</aside>

### Areas of Investment

<aside class="info">
  A future version of Fino might make attaching UI Flows to scenarios much
  cleaner.
</aside>

<aside class="info">
  We might explore a way for Fino to natively document prerequisite data in a
  way that Planter can execute directly.
</aside>

## Open PRs to satisfy user paths

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

After you familiarize yourself with the user path, add a Production Estimate to
the Issue to let your team know when to expect your work to be completed and
escalate risk. We may eventually use a custom solution like Tracks to escalate
estimation risk and reinforce expectations for team communication.

Write the code to address the user path (communicated in the GitHub Issue) on
*one branch.*  If you are intending to collaborate across areas of the stack
(i.e. front-end and back-end), coordinate or pair with the other engineer and
use the same branch.

PRs should target the `stable` branch.

Code should meet AbleCop expectations.

PRs eligible for QA should include both front-end and back-end.

PRs should include Planter seed file.

You should communicate what you're working on.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Open PR with code to satisfy a user path
</aside>

### Areas of Investment

<aside class="info">
  A future version of Fino might understand prerequisite data in a way that is
  executed automatically by Planter.
</aside>

<aside class="info">
  We're exploring how a tool like Tracks might help us identify estimation
  risk and reinforce expectations for team communication.
</aside>

## Run acceptance tests

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Use Fino to run the acceptance tests for the user path addressed by the PR.

### Examples

TODO

### Required Deliverables

<aside class="success">
  Pass or fail the Fino build
</aside>

### Areas of Investment

None

## Merge PRs

<pre class="highlight Producer">
  <p>Here's something the Producer should consider.</p>
</pre>

<pre class="highlight PD">
  Here's something the PD should consider.
</pre>

<pre class="highlight PE">
  Here's something the PE should consider.
</pre>

<pre class="highlight Designer">
  Here's something the Designer should consider.
</pre>

<pre class="highlight Tech-Lead">
  Here's something the Tech Lead should consider.
</pre>

<pre class="highlight QA-Manager">
  Here's something the QA Manager should consider.
</pre>

<pre class="highlight SE">
  Here's something the SE should consider.
</pre>

<pre class="highlight QA-Tester">
  Here's something the QA Tester should consider.
</pre>

Follow our [best practices for code review](#).

### Examples

TODO

### Required Deliverables

<aside class="success">
  Merge PR that satisfies requirements
</aside>

### Areas of Investment

None
