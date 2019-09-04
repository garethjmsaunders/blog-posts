# The importance of small user stories

Thursday 29 August 2019

I've been thinking a lot recently about the size of user stories in agile projects. The idea that I've been reflecting on is what if teams only worked with small, similarly-sized pieces of work, rather than exponentially larger blocks of work?

In theory, small user stories should be more predictable, should include less risk, less uncertainty and less complexity. They should, therefore, take less time to complete than larger user stories... you would think! Or as Mike Cohn put it in _Agile Estimating and Planning_ (Prentice Hall, 2006), "small stories keep work flowing".


## Cycle time

Cohn points to a Poppendieck and Poppendieck study about queuing theory from 2003 about the importance of cycle time in development teams. Cycle time measures how long something takes from the beginning to the end of a process. In software development that's the time it takes from agreeing to create a new feature to the end user being able to use it.

> A key influence on cycle time is the variability in the time it takes to develop a new feature. One of the best ways to reduce variability is to work with reasonably small and similar size units of work.
(_Agile Estimating and Planning_ (Prentice Hall, 2006) by Mike Cohn, p.252)

This idea doesn't get the same amount of attention as other more exciting ideas like story points and activities like planning poker, but it may well be one of the most important to improve the flow of work through a team and the team's overall agility.


## Small slices of high value

Two blog posts, "[Story points revisited](https://ronjeffries.com/articles/019-01ff/story-points/Index.html)" and "[Some thoughts on estimation](https://ronjeffries.com/articles/019-01ff/estimation-again/Index.html)" by agile manifesto signee Ron Jeffries inspired me to explore this further.

Ron Jeffries invented story points as part of a proposal to move away from estimating in ideal days. When asked whether he regreted inventing them he gave four responses:

* "I certainly deplore their misuse;
* I think using them to predict 'when we'll be done' is at best a weak idea;
* I think tracking how actuals compare with estimates is at best wasteful;
* I think comparing teams on quality of estimates or velocity is harmful."

A lot of, arguably wasted, energy goes into discussions around estimation. The use of a logarithmic scale such as the Fibonacci sequence reinforces the understanding that as user story estimates increase more uncertainty and complexity are expected. It makes sense, then to suggest that the simplest way we can reduce these risks is to break down user stories into smaller chunks.

Jeffries again, "To me, the important thing in Real Agile [his emphasis] is to pick the next few things to do, and do them promptly. The key question is to find the most valuable things to do, and to do them quickly. Doing them quickly comes down to doing small slices of high value, and iterating rapidly. Story cost estimation doesn't help much with that, if at all."

Identify small slices of high value and do them quickly. Large stories packed with multiple acceptance criteria use-cases cannot be done quickly. At best these are likely to be big slices of varying value – items of low value nestled alongside items of high value. Rather than arguing whether a user story is worth five points or eight, Jeffries would rather energy and focus were given to breaking down stories into "small slices of high value". That will also naturally identify any elements of low value that can be scheduled later or simply dropped—'could' or 'won't' in MoSCoW prioritisation parlance.

When you create small user stories, each one offering high value and deliverable within a day, the question of size eventually becomes redundant. Teams can simply measure their velocity by the number of stories completed. I like that idea.

## The wait

Smaller user stories create better flow. When you look at the cycle time of larger stories you discover that a lot of that time is spent waiting. John Cutler from Amplitude:

> "Let's consider the time it takes to go from agreeing to do something to a customer receiving value. It may come as a surprise, but most of that time is not spent working. It's spent waiting—waiting in backlogs, waiting for other people, waiting for feedback, waiting to be rolled out and adopted."
> 
> Source: [Creating flow and value in product development](https://amplitude.com/blog/creating-flow-value-in-product-development)

To reduce waiting time, Cutler advocates limiting work in progress. But this doesn't just mean limiting the number of items being developed at the same time, it can also mean limiting the size and complexity of what is being developed. With a five-developer team, there will be greater flow, better predictability and less risk with five one-point stories being worked on concurrently that each take a day to complete than five eight-point stories that take a week or more.


## Battleship

I ran an experiment with the Tasks team to demonstrate this. We played an adaptation of the classic, two-player strategy-type guessing game Battleship.

Each team was given a velocity of 21 story points, represented by 21 guesses. Team A's backlog was split into 21 one-point user stories (guesses); team B, however, had two larger user stories, a 13-point story and an 8-point story.

Team A went first. They would make a guess ("E5?") and get feedback immediately ("HIT!"). Then they made another guess ("F5?"... another hit) and so on, until all their 21 guesses had been used up. At the end of team A's go, they had sunk four out of the five ships. I couldn't have hoped for a better result.

Imagine each of these ships is a new feature, I told the team. By the end of this 21-point sprint, the team had managed to deliver four complete features. Small stories enabled the team to iteratively deliver value. The risk was low and the short feedback loops allowed the team to adjust their approach quickly and learn from their efforts.

Team B went next. They could choose which user story to work on first, 8 points or 13 points, but they wouldn't get feedback on their guesses until after all their guesses for that user-story were made. Team B hit two ships and sank nothing.

I swapped the teams over and ran the game again. The new team A sank two ships, new team B hit three ships and sank nothing. Although the new team A were not as prolific, they still shipped completed features.

I've been involved in many sprints in the past where that was the case—we had worked on a lot of stuff but had completed nothing. As someone once said to me, "You can't deliver in-progress".


## Single responsibility

When considering how to break down stories I've recently been thinking about the [single responsibility principle](https://blog.cleancoder.com/uncle-bob/2014/05/08/SingleReponsibilityPrinciple.html) from SOLID, the first five object-oriented design (OOD) principles by Robert C. Martin (aka Uncle Bob).

In programming, the single responsibility principle states that every class or module should have responsibility over a single part of the software's functionality: each should have one and only one reason to change. In other words, do one thing and do it well.

I wonder if we ought to be doing something similar with user stories: smaller stories, each with a single responsibility. Do one thing and do it well, each user story representing a single, small, testable feature. A small slice of high value.

It's certainly worth exploring.

---

Originally published on my work blog

Battleship photo "grey and black boat under grey clouds" by Will Esayenko on [Unsplash](https://unsplash.com/photos/i_s7yhOm7wc).