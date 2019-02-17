# Planning poker—why and how we estimate

Friday 4 December 2015


![Planning poker cards](https://github.com/garethjmsaunders/blog-posts/blob/master/dct-blog/img/2015-12-04-planning-poker.jpg)

_All the tools you need to become an Agile planning ninja_

When creating a plan—whether it be a big project release plan or a smaller two-weeks’ timebox plan—you essentially need to know three things:

1. Tasks —What are the requirements? What do you need to do?
2. Size — How big are these tasks compared with one another? How long will these take to complete?
3. Priorities — Which tasks need to be done first because others depend on them? Which tasks are most important regardless of dependencies?

It’s very much like creating a recipe: assemble the right ingredients, measure them to the correct proportions, and then mix them together in the right order.

In an Agile project the prioritisation of tasks is done by the business. It is their project after all; they have the most information about value, they understand the market, they have an idea of what features should be delivered next. Prioritisation is not a decision to be made by the development team.

The size of each task, however, is something that the development team is qualified to estimate. If I want a new wall built in my garden whose estimate should I trust more: mine (the person who commissions the work) or the builders (who do this job day-in, day-out for a living)?

When planning, we use a tool called planning poker to help estimate the relative size of tasks.

## Planning poker

Planning poker, or Scrum poker, is a very effective, collaborative planning tool that was first defined by James Grenning in 2002, and made popular by Mike Cohn, founder of [Mountain Goat Software](http://www.mountaingoatsoftware.com/company/about-mike-cohn).

Each estimator takes a set of planning poker cards, consisting of a 0, ½, 1, 2, 3, 5, 8, 13, 20, 40, 100 and optionally a ? for instances where you simply have no idea), and ‘play’ progresses as follows, the rules are pretty simple:

1. Read out the next task.
2. Discuss the task: The task is discussed by those who understand what it’s about, so that the whole team gains clarity about what they are being asked to estimate.
3. Estimate: Everyone selects a card representing how big they think the task to be. Once everyone has selected, we reveal our score at the same time. This is to prevent other team members’ estimates influencing your own.
4. Lowest vs highest: If there is not universal consensus, ask whoever scored the lowest and highest why they thought this was.
5. Re-estimate: Given these new insights everyone re-estimates.
6. Gain consensus: Once consensus has been gained that score is recorded with the task to which it relates. This consensus can be done by repeatedly re-estimating, but more often in our team if most have scored, say 8, and one member still estimates a 5, then she may simply say that they are happy to go with the rest of the group.

## Benefits

### Relative

One of the immediate benefits of planning poker is that it allows you to estimate tasks relative to one another. You may not be in a position to know exactly how long something will take to do, but it should always be easier to estimate whether it would take more effort or less effort than a similar task that you have already completed and know how long it took.

Think of it this way, it doesn’t really matter if you measure the length of your desk in metres and centimetres, feet and inches, or even Post-it notes and pencils, so long as everyone on your team is also using the same scale.

Some teams use an arbitrary unit called ‘story points’ where they know the size of one story point, others measure in ideal days. We estimate in ideal hours.

We also take into account how many people we anticipate will be working on the task. So if we think the task will take one hour with three developers then we’d score it as a three. Although it only occurred to me a couple of weeks ago that we also need to build in quality assurance/testing time into our estimates.

One general rule we have is that if a task is scored as a 13 or above then it needs to be broken down into smaller tasks. Large tasks are generally more complex and therefore harder to estimate with any degree of accuracy. Breaking down the task into smaller pieces removes some of this risk.

### Equal voice

Another benefit is that this style of estimating gives everyone on the team an equal voice. I remember one of the first times we used planning poker when one particular task was discussed, it involved cleaning up a few directories in our media library. My colleague Steve and I estimated something small, like a 5 or 8. Duncan, who had only been in the job for about six weeks estimated 100.

Why so high, Duncan? Even though he was relatively inexperienced in terms of the job as a whole it turns out he had the most up-to-date experience of our media library, and he reported that it was a right royal mess. It would take a much longer time to sort out than either Steve or I had anticipated.

### Equal contribution

Related is the feeling by the whole team that they have all contributed to the plan. And people often feel more committed to a plan that they have had input on. The result is a more dedicated, self-organising team.

## Conclusion

We’ve found planning poker to be a very effective tool for estimating the relative size of project tasks. It allows the whole team to understand what work is coming up, and have their say on how simple or complex the tasks are.

It also allows us to chart the velocity of the team from sprint to sprint, which in turns helps us with future planning as it gives us a more accurate idea of how much work we are likely to complete from sprint to sprint.

## More reading

Luis Goncalves, co-author of the excellent book [Getting value out of Agile Retrospectives](http://luis-goncalves.com/books/) has written a really useful article about planning poker:

---

Published to https://digitalcommunications.wp.st-andrews.ac.uk/2015/12/04/planning-poker-why-and-how-we-estimate/