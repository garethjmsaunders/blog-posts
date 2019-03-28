# INVEST in good user stories

Thursday 28 March 2019

A couple of months ago, I walked the Vision Tasks team through an agile maturity matrix — like a kind of agile health check — to give me an idea of where they were on their agile journey and highlight areas to focus on. One area was in the use of the acronym INVEST when working with user stories.

This post looks briefly at what user stories are and how the INVEST acronym can help.


## User stories

Unlike traditional, waterfall-style project management methodologies which gather full requirements near the start of the project and does a lot of up-front planning, agile projects rely on user stories.


### User-centred

As the name suggests, user stories are user-centred. They describe functionality that a user will find valuable.

One common way to write user stories, to help focus on this user-centred approach, is using the formula:

As a [user]
I want [feature]
So that [value]

For example, 'As a [GP] I want to [be able to attach a patient to a task] so that [an administrator doesn't have to waste time looking up their contact details in another application before phoning them.]'.


### Three parts

A user story comprises three parts:

* A card with a written description of the required functionality.
* Conversations about the story that help to tease out the details.
* Acceptance tests that document these details to help developers and testers understand when a story is complete.

Ron Jeffries summed this up as the three Cs: card, conversation, confirmation.


## Writing user stories

When working with user stories in an XP environment, Bill Wake came up with the acronym INVEST to help development teams write better user stories.

INVEST stands for: independent, negotiable, valuable, estimatable, small, testable.

The maturity matrix considers five levels of a team's maturity in the use of INVEST:

* Little or no knowledge of INVEST.
* Team understands INVEST and is starting to follow parts of it on some stories.
* Following most of INVEST on many stories.
* Following INVEST for most stories.
* Following INVEST for all stories.

The Vision Tasks team is currently at the first level, little or no knowledge of INVEST.

### Independent

User stories should be (order) independent. That is, care should be taken to avoid introducing dependencies between user stories. Dependencies create problems when prioritising and scheduling stories.

An example. Imagine you have two stories, one is to create a new feature, the other is to create the coded UI tests for that feature. While this would create smaller stories, on a large backlog these two stories could easily get separated and one must happen before the other. It would be better to combine the two. If it's still too large, split it into smaller stories along the lines of alternative user paths, interfaces, data or business rules.

### Negotiable

User stories are negotiable. They are not contracts or formally defined requirements. User stories are reminders to have conversations to discover more; conversations with the product owner, customers, stakeholders, end-users, business advisors and other members of the team.

Agile relies on just-in-time planning so user stories don't need to include all the details. These details emerge from conversations during the sprint planning meeting and throughout the sprint. These details can be added as descriptions, comments and acceptance criteria.

It is an acquired skill knowing just how much detail is required. Remember, this is a cue card for a conversation so when writing the user story include cues about what questions should be answered during the conversation.

### Valuable

User stories are valuable to customers (those who buy the software) and/or end-users. Some user stories will include legal or technical requirements that only those commissioning the software are concerned with, other stories will offer features that get users excited*. (*Other emotions are also available.)

This focus on building only valuable features into the software reduces over-production, over-processing, and lessens the risk of introducing more, unnecessary bugs. It also places the focus very much on the users.

### Estimatable

User stories are estimatable. It is important for developers to be able to guess how complex a user story is, and once more is learned about it roughly how long it will take to complete.

If a user story cannot be estimated it is usually because the developers lack business or technical knowledge or the story is simply too big and therefore too complex or complicated.

### Small

Getting the right size of story is important. Like the size of Goldilocks' bed, the right size will be different for every team.

Too small or too large and user stories become difficult to plan into a sprint. Stories that are too small will often introduce dependencies (story A must be completed before story B) that should be combined into larger stories. Stories that are too large are often epics: they contain other, smaller stories.

### Testable

Stories should be written in such a way that they are testable. This is often done by provided acceptance criteria—rules that the application must follow, for example: currency conversion must be offered in US dollars and Euros only. By setting acceptance criteria, agreed with the customer, the developers can better judge when they are finished coding.

## Conclusion

While not a silver bullet, when writing user stories with the INVEST acronym in mind — independent, negotiable, valuable, estimatable, small, and testable — it encourages good habits that have positive knock-on effects throughout the project.

---

Originally published on the internal blog.
Banner image was taken from The Noun Project, searching from [user story](https://thenounproject.com/search/?q=user%20story).
