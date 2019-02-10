# Agile release planning with multiple projects

Wednesday 25 November 2015

One of the biggest challenges we faced when we started down the Agile path was how to accommodate working on multiple projects concurrently. This is a little insight into how we are currently managing ourselves across two projects plus business as usual tasks.

## The Agile ideal

Most Agile/XP/Scrum literature assumes a single, cross-functional team working on a single project for a single customer using a narrow range of technical disciplines. The primary reason for this is that task-switching is really expensive: it is much more efficient to remain focused on one project.

That way of working, though attractive, is more or less impossible in our situation; something that I’ve also heard from other university digital teams. We don’t just work on projects, we have business as usual commitments (which include meetings, support calls, personal development, blogging, editorial calendar updates, etc.), consultancy (where we work on approved institutional-priority projects managed by other teams) and portfolio mechanics (board meetings and related admin, writing up project ideas and terms of reference documents, etc.).

After all that excitement has been deducted from our working week, we are generally left with only about 40% of our time to dedicate to pushing projects towards completion. We therefore need to be careful to extract as much value as we can.

## BBC Interactive

A few years ago, when I first started investigating this particular conundrum (how to do Agile with multiple projects) I was delighted to come across this paper from [Karl Scotland](http://availagility.co.uk/), who at the time (2002) was development team leader in the BBC Interactive team: [Agile planning with a multi-customer, multi-project, multi-discipline team](http://availagility.files.wordpress.com/2008/04/xpu-paper-final.doc) (DOC, 225 KB). Scotland managed a small team of seven developers who, due to the nature of the BBC’s business, were required to work on multiple short projects, for multiple customers, using a wide range of disciplines.

The approach the BBC Interactive team took was to organise their sprints in such a way that it appeared there was only one customer, one project, and one discipline. They settled on three concurrent work streams and planned their sprints accordingly, in short bursts, no longer than four weeks at a time.

User stories and requirements for each project stream were prioritised, scored and then grouped together (taking into account their total capacity) into a single sprint for the whole team to work on. This way they could deliver value to multiple projects very quickly.

They managed this in a spreadsheet document as a long-term release plan:

![BBC release plan](https://github.com/garethjmsaunders/blog-posts/blob/master/dct-blog/img/2015-11-25-bbc-release-plan.gif)

_Long-term release plan from BBC Interactive, 2002_

As Scotland concludes in his paper:

> The team is able to manage the various complexities of multiple customers, projects and disciplines by working in a way which allows them to treat the work as if there were only a single customer, project and discipline. Thus, they work on a single pool of stories which are shared by all the different customers, projects and disciplines. The practices allow the editorial team to juggle all the projects, prioritizing and balancing the scope of each to maximize value for the business, while at the same time allowing individual producers the freedom to fine tune their propositions, either because of resource or time constraints or because they have changed their mind.

## What we do

Based on Scotland’ advice, the following is the how we currently implement things.

We work on a maximum of two project streams (this usually equates to one large and one small project, so that we also spread the risk) plus a maximum of two consultancy projects, and business as usual.

We create a [Trello](http://trello.com/) board for each project and consultancy, plus we have one for business as usual. That allows us to keep each area focused, and we simply track each project within its own board from initial planning to final deployment. At one point we tried moving cards from project boards to a central ‘this week we’re working on…’ board but it got too confusing.

And we also have a long-term release plan in a spreadsheet, which has been such a simple but effective planning tool. This is what ours looks like:

![Release plan spreadsheet](https://github.com/garethjmsaunders/blog-posts/blob/master/dct-blog/img/2015-11-25-dct-release-plan-updated.gif)

_Our current release plan_

## Naming sprints

Something we picked up from somewhere (I can’t remember now where it was, but if it was from your team: thanks) was to name our sprints. This began during our last project as a bit of silliness but it has proved to be really useful now that we’re working across multiple projects.

During our last project — which was the only project we were working on at the time — we named each two week sprint after a children’s TV programme from our youth. It didn’t occur to us to do this until sprint #14 so we started with Noggin the Nog (the fourteenth letter of the alphabet), and carried on through the alphabet: Only Fools and Horses, Parallel 9, Quantum Leap, etc. through to Upstairs, Downstairs and finishing with the Voyages of Dr Doolittle. It was fun and silly, and where possible we tried to match (in as contrived a way as possible) the TV show with the main focus of the sprint.

Over the summer it occurred to me that we could use these sprint names to create some continuity between the work we’re doing across multiple projects.

For example, we are currently in sprint #9 of project DC1001 (External website redevelopments) but sprint #4 of DC1004 (School of Economics and Finance). It would be misleading to keep the sprint numbers consistent across different projects; it would be tedious to have to refer to the sprints by date (e.g. 02 to 13 November) or academic week (e.g. week 8, semester 1); and it would be confusing to have multiple sprint names for each project (e.g. this sprint we’re working on Inch High Private Eye for DC1001 but Dogtanian and the Three Muskehounds for DC1004).

So, now we refer to the sprints by a common name across all projects and business as usual. Because it was Steve Evans and I that were doing the planning at the time, and we are both big cycling fans, our next 26 sprints are named alphabetically after famous cyclists, male and female. The last sprint was (Mark) Cavendish, the current is (Alex) Dowsett.

![Trello board showing sprint names](https://github.com/garethjmsaunders/blog-posts/blob/master/dct-blog/img/2015-11-25-trello-sprint-names.gif)

_Project DC1001 : sprints #6, #7 and #8 were Armstrong, Boardman and Cavendish_

I can’t emphasise just how helpful is has been to have the same sprint names and images across all the project boards. Don’t make me think, indeed.

## Conclusion

Although it was written over 13 years ago, I have found Karl Scotland’s paper still to be one of the most useful resources when thinking about how to manage multiple projects using an Agile methodology. I know there are lots of teams in the same situation, I’ve spoken with a few of them, it’s a shame there is not more written about it.

I’ve found the long-term release plan plus consistently-named sprints to be two very useful tools for creating cohesion while trying to juggle multiple project commitments within a growing and maturing Agile team.

#### More reading

Another really useful study is David Marquis’s blog post: [Small team, multiple projects: an Agile approach to planning](http://davidmarquis.wordpress.com/2011/12/03/small-team-multiple-projects-agile-planning/).

---

Published to https://digitalcommunications.wp.st-andrews.ac.uk/2015/11/25/agile-release-planning-with-multiple-projects/