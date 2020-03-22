---
layout: default
title: Ethical Code, notes
slug: ehical code, notes
categories: project
status: public
description: notes for the ethical code project
date: 2020-03-22 13:30:50 -0500
permalink: /:categories/:slug/
---

Here are my notes, then zee notes, for zee to consolidate and announce.

#### Audience

1. Palantir as company and developers
2. non-developers (use laymen terms) 
3. maintainers 
   1. software is in use by palantir
   2. not on palantir and want to protect themselves

#### Funnels

1. maintainers with software in use
   1. change the licensing: point to the research
   2. pledge on README (badge)
   3. donate money to a group that opposes ICE (README that they did)
2. maintainers unsure if they are used by palantir
   1. github oauth to detect if (alerts? phase 2? discuss)
      1. if yes, check "maintainers with software in use"
      2. if no, how to protect yourself from it
3. dev non-mantainers
   1. raise an issue on ethical license (padding with warnings, how to behave)
   2. donate money to a group that opposes ICE (if you can afford)
   3. donate to repo (better contrast for repos on pledge)
4. non-dev
   1. dashboard, graphs, progress, bird-eye view: explain what they are seeing (phase 2?)

#### Arguments to expose

- open source traditionless
- overworked, underpaid maintainers (donation, thank you for your service, etc)

#### Tech to discuss 

- flags on CTAs so we can measure progress (of donation, of issues raised, etc)
- proxy mesure for repo popularity: reveal power curve, some repos are better than others (likes, follow, activity. it PROBABLY exists somewhere)
- dashboard



### Zee's notes

13:00

Zee

Coraline, you are the stakeholder for approval right?

13:01

Coraline

Yep!

13:01

Zee

Thank you :)

I am just a grunt

13:06

Zee

\1. Palantir (the company + group of developers)

???. Newbies / Non-Technical audiences

13:09

Zee

\3.  Project maintainers (whose projects are being used and maintainers who want their projects _not_ to be used by Palantir)

13:11

Zee

\4. Developers who are contributing to Open Source projects

13:13

Zee

Consider: Pledge to refuse contributions from Palantir; and link those pledges back to the Icebreaker website

13:16

Zee

Option: Maintainer may remove themselves from the list of publicized 

Option: Maintainer may request support for relicensing

Option: Maintainer may pledge to relicense?

13:18

Zee

Option: Link to organizations that are organizing against ICE (RAICES, etc)

13:18

Coraline

(Mijente)

13:20

Zee

Option: Maintainer may publicly share their contribution(s) to Mijente/RAICES/etc. 

13:21

Zee

Option: Developers may open an issue on libraries to request a change to an ethical license.

13:23

Zee

Question: How do we address the people who do not care?

13:25

Zee

Design Consideration: Mitigate random people "inflicting help" for overwhelmed maintainers.

"Maintainers are overworked and underpaid and being exploited by big companies. We're in this together"

13:28

Zee

Design Consideration: Avoid casting the people who believe "Free for all uses" is a valid position, and provide next steps for maintainers or  developers who wish to priorritize human rights over property rights

Design consideration: Reducing the 'barrier to caring' may encourage people to start caring because of a smaller cost-to-participate

13:31

Zee

Design consideration: If we can grab the visitors github and cross-reference  it with the projects they contributed to or maintain that Palantir uses.

13:32

Zee

Design consideration: Show trend of usage of opens ource by palantir over time

Design consideration: The value or utility of a repository within a project is difficult to determine. We can use "Stars" or "Followers" for a  repository

13:35

Zee

Design consideration: Link to the sponsorship pages for maintainers who have pledged / began the relicinsg process 

13:37

Zee

Design consideration: Demonstration of how we are sending financial aid to projects who are transitioning to ethical licenses

(Maybe also non-financial, assuming we know who is contributing to what))

13:39

Zee

Step 1: Determine the intersection between the design direction and the  desired techincal implementation. Nicholas will do some pie-in-the-sky  wireframes and share with developers

13:41

Zee

Step 2: Determine the complexity of linking visitors github accounts for performing further analysis

Step 3: Determine if we can programmitcally detect people who have pledged to reject contributions from Palantir

13:42

Zee

Step 4: Enumerate why we recommend each organization we are encourging people to sponsor

Step 5: Determine the voice we want to use and begin to fill in copy

13:43

Coraline

"It's not good guys vs bad guys

13:44

Zee

Step 5: Find "Semi-friendly" maintainers to request feedback from (perhaps in the #maintainers channel)

Design consideration: FIGMA is free for 1 editor; so we can use it for comment without issue.

13:47

Zee

Email to zee@zincma.de + coraline@idolhands.com