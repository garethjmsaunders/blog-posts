# How and why we QA

WEDNESDAY 30 AUGUST 2017

At a conference recently one of our team was speaking about how we organise our work using **[Trello](http://trello.com/)** and the Kanban-style workflow we have settled on. A number of people told her afterwards that they were impressed with both the simplicity and effectiveness of our rules around the QA (quality assurance) or testing phase.

As **[Wikipedia](http://en.wikipedia.org/wiki/Kanban_(development))** explains, “Kanban is a method for visualizing the flow of work, in order to balance demand with available capacity and spot bottlenecks.”

At its simplest level a Kanban board needs only three columns or lists to track your tasks:

1. To do
2. In progress
3. Done

We have added a fourth column, ‘QA’, between ‘In progress’ and ‘Done’.

This post explains why.

### **Backlog**

The first column we have is our ‘To do’ column; we name this ‘Backlog’ because the team has a **[Scrum](http://www.scrumalliance.org/why-scrum)** background.

First, we stack up work for the forthcoming, fortnightly sprint in the backlog. We have a team rule that nothing gets worked on unless there is a card in Trello to represent it. This keeps us accountable and transparent about the work we are doing.

On each card we include the minimum amount of information required by the person working on it, and the person checking it to know what to test it against. Broadly speaking, this means:

* Meaningful title
* Estimate (in hours, which includes time for QA work)
* Short description of the task
* Any supporting documents or files
* **[User stories](http://digitalcommunications.wp.st-andrews.ac.uk/2013/08/15/user-stories-the-impact-of-search-engine-optimisation-and-vestibular-disorders/)** (optional)
* **[Acceptance criteria](http://digitalcommunications.wp.st-andrews.ac.uk/2016/12/14/the-difference-between-acceptance-criteria-and-definition-of-done/)**
* Contact details for those involved
* Who is responsible for the task?
* Who will test it?

When a card has this information we mark it with a ‘READY’ label. It is now ready to be started.

### **In progress**

When we start working on a piece of work we move the Trello card representing it into the ‘In progress’ column.

The card should now be fairly self-contained. From the description, user stories and acceptance criteria it should be clear what is required and the task can now be iterated on by the solutions developers and business ambassadors and advisers.

Once the task has been completed we move it into the ‘QA’ column.

### **QA**

We didn’t always have a QA column or testing phase. When we first started using a Kanban-style approach, work that we considered finished was moved straight into the ‘Done’ column and we cracked on with the next task on the backlog.

But we noticed that quite often we would have to fish cards back out of ‘Done’ into ‘In progress’ when errors were later spotted.

Releasing code or content that contains errors is not agile. Agile strives to create a ‘zero bugs’ approach (_The Art of Agile Development_ (O’Reilly, 2008), p.160). In other words, build in quality from the start. Or as the fourth principle of Agile DSDM project management states: “never compromise quality”.

We addressed this shortfall in our process in a **[retrospective](http://digitalcommunications.wp.st-andrews.ac.uk/2015/03/11/continually-improving-our-work-habits-with-retrospectives/)** at the end of a particularly error-prone sprint. We decided to introduce a ‘QA’ (quality assurance) column between ‘In progress’ and ‘Done’. This has proved very successful.

So now, once a piece of work has been completed it is moved into the QA column and the team member responsible for the task finds _someone else_ to check it for them.

This is an important part of the workflow: you must not check your own work, you must find someone else to check it for you.

And of equal importance, the person who checks the work must have the right skill set to be able to verify its accuracy.

#### **Why you can’t QA your own work**

It’s a well-known fact in writing circles that **[it is very difficult to edit your own writing](http://goinswriter.com/writers-cant-edit/)**. The same thing can be said for writing code, or producing video or audio, or the many other steps required to create websites.

When you try to edit or QA your own work you are emotionally too close to it. As soon as you have put effort into creating something you feel some degree of attachment to it, you lose objectivity and find it hard to criticise it. As you know what you _intended_ to write, you often read what you _think_ you have written, rather than what you _actually_ wrote and so typos get missed.

(Of course, there will be situations where it is necessary to edit your own work. Lifehacker offers some tips: **[How to edit your own writing](http://lifehacker.com/5968996/how-to-edit-your-own-writing)**. But wherever possible, we try to ensure that you don’t.)

#### **What if it fails QA?**

If errors are found then we have two options.

If it’s a fix that can be done by the person doing the QA then we encourage the tester to fix it, and update the Trello card explaining what has been done. We believe in what Shore and Warden in _The Art of Agile Development_ (O’Reilly, 2008) call collective code ownership: “everyone shares responsibility for the quality of the code. No single person claims ownership over any part of the system, and anyone can make any necessary changes anywhere.” (_ibid_, p.191). Obviously, this isn’t restricted to code, it applies to other types of content, too.

If the fix requires input from the original creator then we update the Trello card to explain what needs to be done, and move the card back into ‘In progress’. Then we let the person responsible for the task know that there is something to fix.

### **Done**

Once we are certain that the piece of work is to the highest quality required, that it meets its acceptance criteria and has been checked by someone else, we move the card to ‘Done’.

And start again on another task.

### **What we have learned**

As the conference goers noted, adding a QA column and the simple rule: ‘do not QA your own work’ has been a very simple but effective addition to our workflow.

The most immediate consequence, thankfully, is that fewer errors now make their way to live websites. But there are a few hidden benefits too.

All work now feels more like a collaborative, team effort. And because more than one person has worked on the feature (or more than two in the case of pair-programming or pair-writing) then it benefits from a wider input and wider experiences.

Work is now less likely to be done in silos. More team members get to review it before it goes live, which helps with both familiarity and future maintenance. And spreading the maintenance burden further empowers team members to own and fix bugs as they find them.

It is a practice that we fully endorse. Sure, be proud of the work you do, but once it’s done, let it go, allow others to review it and improve it, and in the end through **[the wisdom of crowds](http://en.wikipedia.org/wiki/The_Wisdom_of_Crowds)** you will end up with better code, better content, and fewer mistakes.

### **Example Trello board**

Example Trello board

To give you an idea of what our project boards look like in Trello, I have created an **[example project board](http://trello.com/b/1vUwB4Sn/example-project-board)**.

You will see next to the backlog column we also have a ‘Sprint 1’ column. This allows us more focus, allowing us to move from the backlog cards that are scheduled for this sprint.

We also create a new ‘Done’ column for each sprint, named with the sprint number and name and dates, where appropriate.

Feel free to use this board as an inspiration for your own project boards.