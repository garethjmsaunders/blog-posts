# What is a Definition of Ready?

Wednesday 29 January 2020

While the [Scrum Guide](https://www.scrumguides.org/scrum-guide.html) encourages teams to create a Definition of Done so that everyone understands what 'done' means, it says nothing about creating a Definition of Ready so that everyone understands what pre-conditions must be met before a user story may be allowed onto a sprint.

This is the closest the Scrum Guide gets to mentioning a ready state:

> "Product Backlog items that can be 'Done' by the Development Team within one Sprint are deemed "Ready" for selection in a Sprint Planning. Product Backlog items usually acquire this degree of transparency through the above described refining activities." ([Scrum Guide](https://www.scrumguides.org/scrum-guide.html))

[Mike Cohn](https://www.mountaingoatsoftware.com/blog/the-dangers-of-a-definition-of-ready) compares a Definition of Ready to a bouncer standing at the door to a sprint, determining who may and who may not be allowed to pass.

More than simply ensuring that a user story is able to be completed on a sprint, a Definition of Ready contains wider criteria that any user story must pass before it is regarded as sprint-ready. For example,

* The user story contains enough background information for the team to understand.
* The user story is estimated and under a certain size.
* UX is mocked up/fully designed.
* User story has no external dependencies.
* Acceptance criteria are agreed and documented.

A team may have different Definitions of Ready for different issue types: epics, user stories, bugs, tasks, etc.

From a risk management perspective, having a Definition of Ready can be a good thing. The team mitigates against potential incidents by ensuring that a certain level of detail (or that particular issues have been considered) is already present on the user story before development beings. Ensuring that a user story is small enough to be completed within a single sprint sounds like a sensible idea. As does outlining acceptance criteria that may be used to direct both development and testing. It should be up to each development team to define their own depending on their needs and agile maturity.

The problems lie when the Definition of Ready is treated as a waterfall-type stage gate that insists on the previous stage being completed to 100% before moving on to the next. Mike Cohn explores this idea in a blog post called [A Definition of Ready could be a dangerous step towards a stage-gate process](https://www.mountaingoatsoftware.com/blog/the-dangers-of-a-definition-of-ready).

I have always found a short, practical Definition of Ready to be a useful tool during backlog refinement meetings and sprint planning meetings. They can act as gentle guidelines (rather than hard-and-fast rules) to ensure that a developer or tester has the right amount of information on a card before working on that user story. The iterative nature of agile development means that teams will often uncover unexpected insights during coding that couldn't have been considered during refinement or planning.