# The importance of small user stories

Thursday 29 August 2019

I've been thinking a lot recently about the size of user stories in agile projects. The idea that I've been reflecting on is what if teams only worked with small, similarly-sized pieces of work, rather than larger exponentially larger blocks of work?

In theory, small user stories should be more predictable, should include less risk, less uncertainty and less complexity. They should, therefore, take less time to complete than larger user stories. Or as Mike Cohn put it in _Agile Estimating and Planning_ (Prentice Hall, 2006), "small stories keep work flowing".


## Cycle time

Cohn points to a Poppendieck and Poppendieck study from 2003 about the importance of cycle time in development teams. Cycle time measures how long something takes from the beginning to the end of a process. In software development that means the time it takes between agreeing to create a new feature and the end user being able to use it.

> A key influence on cycle time is the variability in the time it takes to develop a new feature. One of the best ways to reduce variability is to work with reasonably small and similar size units of work.
(_Agile Estimating and Planning_ (Prentice Hall, 2006) by Mike Cohn, p.252)

So writes Cohn, nearly 60 pages from the end of his book. It's a simple idea that is worth exploring deeper.


## Small slices of high value

Two blog posts, "[Story points revisited](https://ronjeffries.com/articles/019-01ff/story-points/Index.html)" and "[Some thoughts on estimation](https://ronjeffries.com/articles/019-01ff/estimation-again/Index.html)" by agile manifesto signee Ron Jeffries inspired me to explore this further.

Ron Jeffries invented story points as part of a proposal to move away from estimating in ideal days. When asked whether he regreted inventing them he offered four responses:

* "I certainly deplore their misuse;
* I think using them to predict 'when we'll be done' is at best a weak idea;
* I think tracking how actuals compare with estimates is at best wasteful;
* I think comparing teams on quality of estimates or velocity is harmful."

A lot of, arguably wasted, energy goes into discussions around estimation. The use of a logarithmic scale such as the Fibonacci sequence reinforces the understanding that as user story estimates increase more uncertainty and complexity are expected. It makes sense, then to suggest that the simplest way we can reduce these risks is to break down user stories into smaller blocks.

Jeffries again, "To me, the important thing in Real Agile is to pick the next few things to do, and do them promptly. The key question is to find the most valuable things to do, and to do them quickly. Doing them quickly comes down to doing small slices of high value, and iterating rapidly. Story cost estimation doesn't help much with that, if at all."

Identify small slices of high value and do them quickly. Large stories cannot be done quickly. At best these are likely to be big slices of varying value – items of low value embedded alongside items of high value, unless they are broken down into small slices and identified. Jeffries would rather energy and focus were given to breaking down stories into "small slices of high value". 

When you create small user stories, each one offering high value and deliverable within a day, the question of size eventually becomes redundant. Teams can simply measure their velocity in the number of stories completed. I like that idea.

Smaller user stories create better flow. When you look at the cycle time of larger stories, you discover that a lot of that time is spend waiting. John Cutler from Amplitude:

"Let's consider the time it takes to go from agreeing to do something to a customer receiving value. It may come as a surprise, but most of that time is not spent working. It's spent waiting—waiting in backlogs, waiting for other people, waiting for feedback, waiting to be rolled out and adopted."

Source: [Creating flow and value in product development](https://amplitude.com/blog/creating-flow-value-in-product-development)

To reduce waiting time, Cutler advocates limiting work in progress. But this doesn't just mean limiting the number of items being developed at the same time, it can also mean limiting the size and complexity of what is being developed. With a five-developer team, there will be greater flow, better predictibility and less risk with five one-point stories being worked on concurrently that take a day to complete, than five eight-point stories that take a week.


## Battleship

I ran an experiment with the Tasks team to demonstrate this. We played an adaptation of the classic, two-player strategy-type guessing game Battleship.

Each team was given a velocity of 21 story points, represented by 21 guesses. Team A's backlog was split into 21 one-point user stories (guesses); team B, however, had two larger user stories, a 13-point story and an 8-point story.

Team A went first. They would make a guess ("E5?") and get feedback immediately ("HIT!"). Then they made another guess ("F5?"... another hit) and so on, until all their 21 guesses had been used up. At the end of team A's go, they had sunk four out of the five ships.

Imagine each of these ships is a new feature, I told the team. By the end of this 21-point sprint, the team had managed to deliver four complete features. Small stories enabled the team to iteratively deliver value. The risk was low and the short feedback loops allowed the team to adjust their approach quickly and learn from their attempts.

Team B went next. They could choose which user story to work on first, 8 points or 13 points, but they wouldn't get feedback on their guesses until after all their guesses for that user-story were made. Team B hit two ships but sank nothing.

I've been involved in many sprints where that was the case—we had worked on a lot of stuff but had completed nothing. As someone once said to me, "You can't deliver in-progress".


## Single responsibility

It's similar, I suppose, to Uncle Bob's [single responsibility principle](https://blog.cleancoder.com/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html) in programming — the idea that each module, class or function should have responsibility over just one part of the software's functionality.

Just as Uncle Bob believes that developers should "isolate your modules from the complexities of the organization as a whole, and design your systems such that each module is responsible (responds to) the needs of just that one business function", perhaps we ought to be doing something similar with the user stories written to request this functionality: smaller stories, each with a single responsibility. These could be 



