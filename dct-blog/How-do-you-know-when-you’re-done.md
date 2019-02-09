# How do you know when you’re done?

WEDNESDAY 31 AUGUST 2016

IMAGE: Icons that suggest ‘done’, from The Noun Project.

How do you know when you’ve completed something?

Not just nearly finished it -- not a simple shrug of the shoulders and a mutter of “I guess that’ll do”, but absolutely certain that what you’ve created is (to the best of your knowledge and skills and ability) fit for purpose, has been adequately tested, and is ready to go into production without any more work needed on it. Which, note, is different to wanting to add extra features to it in the future. This post looks at the Agile concept of the ‘definition of done’ and the repetitious ‘done done’.

### Done done

Agile has this interesting concept of ‘DONE’ or ‘done done’. Not just done, but ‘DONE’… ‘done done’. The term suggests a more complete version of complete. Like belt and braces.

Let me explain how it works with a real-world example from my family.

Growing up, after my Mum had been preparing the evening meal, she would shout through the house, “Dinner’s ready!” And my brother and sister and I would race down the stairs expecting to find our evening meal dished out on plates, and ready to eat. Instead, we learned pretty quickly that when Mum shouted “Dinner’s ready!” what she actually meant was, “I’ve finished cooking dinner.” And so we learned to wait another five minutes before appearing in the dining room.

Mum’s definition of ‘ready’, her definition of ‘done’, was that the food had been cooked. It didn’t also include draining the potatoes, or removing the haggis from the oven (because obviously being Scottish we had haggis, neeps and tatties every evening), or serving it on plates. Our expectation as food end-users was that when called, when told that dinner was ready, then it was prêt á manger, ready to eat: that we could arrive at the dinner table, sit down and immediately start eating (again, obviously after we’d washed our hands and said grace -- we weren’t barbarians!).

My dad’s approach was entirely different. On the rare occasion that he cooked, when Dad shouted “Dinner’s ready!” we discovered that his definition of ‘ready’ was the same as ours. We learned this because after giving our usual five minutes wait, we’d arrive to our food getting cold.

Dad’s definition of ‘ready’ included serving and plating it up, so when we arrived at the table we could tuck-in straight away. (When Dad cooked we definitely were barbarians).

As Kelly Waters wrote in an article entitled ‘[Done means DONE!](http://www.allaboutagile.com/agile-principle-7-done-means-done/)‘:

> Too often in software development, ‘done’ doesn’t really mean ‘DONE!’. It doesn’t mean tested. It doesn’t necessarily mean styled. And it certainly doesn’t usually mean accepted by the product owner. It just means developed.

So, going back to family dinner’s for a moment, Mum’s meals were ‘done’ but not ‘DONE’, or ‘done done’ if you prefer (even if, occasionally, they were well-done); whereas Dad’s were ‘DONE’.

‘Done done’ is ready to go: built, tested, and ready to go into production.

### Defining done

What could have helped make the user-experience of our family meals more consistent would have been a definition of done: a simple list of value-adding steps that describe everything that needs to be completed before we can truly say that the task has been completed, that it is truly ‘done done’. This would have resulted in less waiting and less uncertainty about when we could begin eating.

In the case of “Dinner’s ready!” this could have been:

1. Table is set (knife, fork, spoon, glass, and side plate for each person).
2. Food is cooked thoroughly.
3. Food is drained (if required) and dished onto plates.
4. Plates (loaded with food) are placed on the table.
5. Pots, pans and cooking utensils are placed in or near to the sink or dishwasher, ready for the next task (washing up).
6. Now call for the family to come to the table, using the phrase “Dinner’s ready”.

If these steps had been agreed and written down, then regardless of who prepared dinner, dinner would always be served up and ready to eat.

### Translating this for digital

Obviously this is a bit of a silly example, but I hope you can begin to see where this may be useful in a team context.

The definition of done presents to the developer a very specific checklist of things that must be completed (or, in some cases, at least considered) before you can truly regard this feature as completed.

It also presents to whoever is testing or QA-ing a very definite list of criteria to check against to verify that the development of the feature is indeed complete.

When considering definitions of done, it can be helpful to think in terms of categories of work such as writing content, creating designs, or writing code. You can also think of defining what done means for a sprint (write a list of actions that must be done at the end of a sprint, before you can move on to the next one) or a release (perhaps the release is complete when it has been pushed out to the production server, and the code has been tagged in the version control system).

An example of ‘done’ for coding might be:

* Acceptance criteria of the user story are met.
* Code is adequately commented.
* Code is tested for accessibility.
* Code is reviewed/tested by another member of the team.
* Known technical debt is recorded in a new card.
* Documentation is written and reviewed.
* Code is committed and merged into the distributed version control system.

You will note that references to acceptance criteria are acceptable -- encouraged, even.

Definitions of done are subtly different to acceptance criteria. Acceptance criteria are essentially test cases for user stories. A definition of done ought to be applicable to all user story cards -- it should be repeatable; acceptance criteria should be limited to how one particular user story can pass testing.

### Conclusion

Defining ‘DONE’ (or ‘done done’) is useful, but takes practice and discipline. Don’t agonise too much over your definitions. Start with something simple and practical, and commit to reviewing it after a few months.

We are currently in a position of needing to review our definitions of done for design, content and code development, which haven’t been updated significantly since we built our prototype.

I’d be interested to learn if you use formal definitions of ‘done done’, and what they are. Do you find them useful?