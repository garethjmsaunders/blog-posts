# Planning poker: supporting agile practice

Friday 7 June 2019

Next in my short series on supporting agile practices is planning poker (sometimes called the planning game).

Planning poker may be used when estimating the relative size of a user story, during backlog refinement or sprint planning.


## How to play

Let's assume that a team wants to use planning poker to agree on estimates during a backlog refinement session. They take a look at the backlog and the next story they have to discuss reads, "As a buyer I want to use PayPal to pay for purchases so I don't need to enter my credit card details into a website I've never used before".

The team discusses with the product owner and any customers or business ambassadors available the ins and outs of the story to fully understand what is required. They craft some acceptance criteria which will help guide them during development and testing.

Once the team feels they understand enough about the story to estimate how much effort and time will be involved they reach for their planning poker cards.

Their planning poker cards use an adapted Fibonacci sequence: 0, ½, 1, 2, 3, 5, 8, 13, 20, 40, 100. It also includes an infinity card (for impossibly huge tasks), a question mark and sometimes one with a cup of tea that indicates that they feel they need a break.

In a previous session, the team had defined for themselves what they understood a typical 1, 2, 3 and 5 story looks like. They each use this as a guide when deciding on their estimate.

Each member of the team evaluates what they've understood about the story against their experience, the effort they think is required, the risk and uncertainty still contained within the story and how long they think the story will take to develop. They each, secretly select a card.

"Well, this seems to me to be a...," starts Jonny.

The scrum master cuts him short. "No discussion until after the first vote, Jonny, remember?"

"Oh yeah, sorry," says Jonny and focuses on his cards again.

The scrum master looks around the room. "Is everyone ready?" he asks.

Everyone nods.

"Three, two, one, go!"

And with that everyone spins their card around to reveal a number. There is one 2, four 5s, a 13.

The scrum master then asks the outliers, those who had scored it the lowest and highest, to explain why they had scored that way.

Danny explains that he thought it was a 2 because he'd worked on a similar story with one of the other feature teams a few months ago. He thought it would be a simple case of adapting their code, taking into account a little overhead of generating new credentials, etc.

Louise points out that that other application was on a separate server and there might still be some network and firewall configurations to be done to open up the ports to the PayPal API.

"Ah yes, thanks Louise," says Danny, "I've forgotten about that."

"Andy," says the scrum master, "Why did you think it was a 13?"

Andy explains that he's a very junior developer and while he understands what is being asked to do he has no experience of working with online payments and isn't entirely sure of the security elements involved. "I'd be happy to pair programme, though," he says, "so I could learn it."

"Shall we vote again?" asks the scrum master.

Everyone nods and turns back to their cards.

"Three, two, one, go!" says the scrum master again.

This time there are five 3s and one 5. Andy, the junior developer had changed his 13 to a 5.

"Andy, would you be happy with a 3?"

"Erm, sure..." says Andy, with a little uncertainty.

"It's okay," reassures Aileen, "we wouldn't expect you to work on this on your own. We'll pair for this story anyway."

"That's a good idea," says the scrum master (who oddly doesn't yet have a name in this little drama and so I'm not going to start giving them one now!) and makes a note of that on the card in Jira. 

"Okay, we're agreed that it's a 3?"

Everyone nods.

"How sure are you about this estimate, 50/50 or 90%?"

Everyone says 90%.

"That sounds good," says the scrum master and adds 3 story points to the Jira card.


## Why planning poker is useful

The main benefits in using planning poker, in my experience, are two-fold: 1) initial estimates can be made independently, without influence from other developers, and 2) it levels the playing field so that everyone has a voice.

Many of us will have been in teams or groups where there is someone who dominates the group; they are very vocal and have an opinion on everything. Many of us will also have been in groups where we are the newbie and may feel a sense of intimidation by older and/or more experienced group members. Planning poker tries to remove those elements of intimidation or influence by requiring team members to come to their own conclusions before there is any discussion—it gives everyone a good platform from which to start.

Similarly, because everyone has a secret vote it levels the playing field. Everyone at some point will always reveal the lowest or highest estimate. This approach gives everyone, from the most junior to the most senior engineer an equal voice.


## My experience

I remember the first time I introduced planning poker to my team at St Andrews. We had just hired a new junior developer to join our team of three; he'd been in the job for about a month.

The user story was about re-architecting an area of the University website, maybe 20 or so pages. To my mind it seemed like a pretty straight-forward task.

We voted: 13, 13, 13, 100.

Duncan, the new guy, had voted 100. Once we explain to him how simple this is, I thought to myself, he'll understand that it's not a 100. He's just new, I thought.

"Why did you think it's a 100, Duncan?" I asked.

"Well, I've just been in that section of the media library, while working on a support call and it's a mess! There is no consistency in folder or file names, I'm sure a lot of the files are in the wrong folders, the actual files have spaces in the filenames and none of them follow our style guide for filename standards. I mean... it's a real mess. And there are maybe... 300, 400 files. There's no easy way to see if any are duplicates or are even up-to-date."

I immediately appreciated why planning poker works. Duncan could easily have been influenced by our prejudices about how easy the task was and gone along with our much lower estimates. We could very easily have dismissed his higher estimate based on our prejudices about him being a new developer. But this levelled the playing field and gave Duncan a voice.

When we re-voted everyone revealed a 100.


## Conclusion

I have found planning poker to be a really helpful tool that gives everyone a voice, allows the whole team to get involved and facilitates conversation.


---

Originally published on my work internal blog.

Header photo by 