# The importance of small user stories

Thursday 29 August 2019

I've been thinking a lot recently about the importance of creating smaller user stories in agile projects. The conclusion that I'm coming to is that teams should try to work with smaller, similarly-sized pieces of work.


## Battleship

Let me give you an example, an experiment I ran with the Tasks team.

A few months ago, I invited the Tasks team into a meeting room for a game of Battleship, that classic strategy-type guessing game for two players where each person tries to locate and sink their opponent's fleet, played on a 10×10 grid.

I wanted to demonstrate to the team why working on smaller user stories made you more agile—more responsive, they could learn from their mistakes more quickly.

Each team was given a velocity of 21 story points, represented by 21 guesses. Team A's backlog was split into 21 one-point user stories (guesses); team B, however, had two larger user stories, a 13-point story and an 8-point story point.

Team A went first. They would make a guess ("E5?") and get feedback immediately ("HIT!"). Then they made another guess ("F5?"... another hit) and so on, until all their 21 guesses had been used up.

At the end of team A's go, they had sunk four out of five ships. Imagine each of these ships is a new feature, I told the team. By the end of this 21-point sprint, the team had managed to deliver four complete features. Small stories enabled the team to iteratively deliver value. The risk was low and the short feedback loops allowed the team to adjust their approach quickly and learn from their attempts.





Jeffries, himself, invented story points as part of a proposal to move away from estimating in ideal days. When asked whether he regrets inventing story points he offers four responses:

* "I certainly deplore their misuse;
* I think using them to predict 'when we'll be done' is at best a weak idea;
* I think tracking how actuals compare with estimates is at best wasteful;
* I think comparing teams on quality of estimates or velocity is harmful."

A lot of (arguably wasted) energy goes into discussions around estimation. The use of a logarithmic scale such as the Fibonacci sequence reinforces the understanding that as user story estimates increase more uncertainty and complexity are expected.

The simplest way we can reduce these risks is to break down user stories into smaller blocks.

Jeffries again, "To me, the important thing in Real Agile is to pick the next few things to do, and do them promptly. The key question is to find the most valuable things to do, and to do them quickly. Doing them quickly comes down to doing small slices of high value, and iterating rapidly. Story cost estimation doesn't help much with that, if at all."

Identify small slices of high value and do them quickly. Large stories cannot be done quickly. At best these are likely to be big slices of varying value—items of low value embedded alongside items of high value, unless they are broken down into small slices and identified as such.

Jeffries would rather energy and focus were given to breaking down stories into "small slices of high value". With much smaller user stories, each one offering value and deliverable within a day, the question of size eventually becomes redundant. Teams can simply measure their velocity in the number of stories completed.

It's similar, I suppose, to Uncle Bob's [single responsibility principle](https://blog.cleancoder.com/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html) in programming — the idea that each module, class or function should have responsibility over one part of the software's functionality. Just as Uncle Bob believes that developers should "isolate your modules from the complexities of the organization as a whole, and design your systems such that each module is responsible (responds to) the needs of just that one business function", perhaps we ought to be doing something similar with the user stories written to request this functionality: smaller stories, each with a single responsibility.







Small user stories 

* more predictable
* less risk/uncertainty
* less complexity
* take less time












https://photos.google.com/photo/AF1QipNPQmgf_ofWvW1jATOfqzkxj2-FNmcJPvGdkWDP





Two blog posts, "[Story points revisited](https://ronjeffries.com/articles/019-01ff/story-points/Index.html)" and "[Some thoughts on estimation](https://ronjeffries.com/articles/019-01ff/estimation-again/Index.html)" by agile manifesto signee Ron Jeffries have inspired me to explore this further.




Small stories keep work flowing
From queuing theory (Poppendieck and Poppendieck 2003; Reinertsen 1997), we learn the importance of focusing on _cycle time_, the amount of time something takes to go from the start of a process to the end of that process. On a software project, cycle time is the time from when the team begins work on a feature until that feature delivers value to users. The shorter the cycle time, the better.

A key influence on cycle time is the variability in the time it takes to develop a new feature. One of the best ways to reduce variability is to work with reasonably small and similar size units of work. The estimating and planning process outlined in this book supports this by advising that teams estimate their short-term work within approximately one order of magnitude. Larger user stories can exist further down a project's prioritized requirements list. However, as those features near the top of the list (when they will be scheduled into an iteration that is beginning), they are disaggregated into smaller pieces.

_Agile Estimating and Planning_ (Prentice Hall, 2006) by Mike Cohn, p.252

