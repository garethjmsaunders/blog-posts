# Simplicity and maximizing the work not done

Thursday 14 March 2019

The other day in a meeting, I quoted one of the statements in the Agile Manifesto.

"Wow! Do you know the Agile Manifesto off by heart?" they asked me.

To be fair, not including the 12 principles, it is only four sentences long but I joked that I read it every night before I went to bed. I mean, obviously I don't... it's every second night.

The last few times I've read through the [Agile Manifesto principles](http://agilemanifesto.org/principles.html), though, one of the principles has grabbed my attention. It's not one that gets too much attention. It's this one, number 10:

> "Simplicity—the art of maximizing the amount of work not done—is essential."


## Simplicity

Simplicity is big at the moment, which isn't much of a surprise given how complex and complicated modern life is. Look at the attention people like [Marie Kondo](https://konmari.com/) and [The Minimalists](https://www.theminimalists.com/) are having.

A couple of years ago, I sat down and wrote a number of goals for my life, how did I want to live my life? The first item on that list was to live a simpler life. "Live a simple life," I wrote, "Be aware. Live in the now. Observe yourself. Be kind to yourself. Love yourself and those around you. Slow down. Observe. Be curious. Go deep."

Simplicity is good for development teams too. There are maybe things here that we can apply to Scrum teams.

One of the reasons that agile teams employ user stories rather than detailed requirements documents is that user stories promote simplicity. User stories are reminders to have conversations. User stories encourage us to leave some decisions as late as possible.

By focusing on the 'why' of a particular requirement, the team is encouraged to ask questions to get to the heart of the problem, rather than blindly following a checklist of requirements.

Slow down. Observe. Be curious. Go deep.

By focusing on the 'why', teams are encouraged to build what the customer needs as simply as possible and then iterate until the customer is happy.

Be aware. Live in the now. Observe. Be kind.

Simple code will have fewer bugs. Simple code is easier to understand later. Simple code that solves your immediate problem is better than complicated code that future proofs your application for scenarios that may never happen. Simple code is cheaper.


## Maximize the amount of work not done

Let's follow an example. Imagine that your customer says they need you to build them a car. So you gather all the requirements and you get to work. A year later, you present them with a car. It is a work of engineering genius. It has everything they dreamed of when you quizzed them about it 12 months ago. It has heated seats, a heated windscreen, a massive car stereo, eight gears, seven seats and has an enormous amount of storage in the boot. Brilliant!

Except, you learn that your customer only needs it to transport themselves the 17 miles from St Andrews to Dundee, on a daily commute with minimal luggage, and only during the summer. So they have waited a year to get something that is over-specified and over-engineered for their needs.

Let's restart this scenario and write a user story to capture why the customer needs a vehicle.

> As a commuter I want a method of transport that will enable me to travel the 17 miles from St Andrews to Dundee so that I can travel to my work (Monday to Friday) during the summer.

(Ignore that I've included some acceptance criteria in the user story to speed things up here.)

The engineers think, it sounds like they could do with a car but what if we start simply and first build them a pedal bicycle?

It takes them two sprints and deliver the bike to the customer. After four weeks the customer has something usable. They try it out. It does the job but it takes them 90 minutes to cycle to Dundee.

"Hmmm... could I have something a little bit faster, please?"

The engineers discuss it, agree that it still sounds like they could do with a car but what if we just motorise the bicycle and create a scooter?

Three sprints later (6 weeks) they deliver their scooter to the customer. The customer tries it out. 

"This is brilliant! I can now do my commute in 40 minutes, and I love how I can weave in and out of traffic! I can use a pannier for my briefcase and wear waterproofs if it rains. I thought I was looking for a car but I'm really happy with this solution, let's stop here."

By thinking simply, the engineers have delivered a solution the customer is happy with in just 10 weeks, rather than an over-engineered solution that they had to wait 52 weeks for.


## Example

I remember when I was the Assistant Web Manager at the University of St Andrews working on some JavaScript code. I had a form validator to build that required a number of libraries. I got it working in a couple of days and was really pleased with it.

But I didn't leave it there. I could see its potential, how this solution might be used throughout the website. So, I refactored my code to make it easier to use with other forms and included it within our core JavaScript file that loaded on every page. I wrote some code to detect whether such a form was on that page and if there was then it dynamically pulled in the required libraries. I was delighted with it. It had only taken me an extra three days. I deployed it.

Yeah... you've guessed it, we never used it again, anywhere else on our 300,000-page website. What a waste of three days; what a waste of money. If I had been aware of the Agile Manifesto principle "Simplicity—the art of maximizing the amount of work not done—is essential." I would have stopped and deployed after two and moved on.


## Over to you...

What would benefit from being thought of more simply in your product? What would benefit from having less work done?

---

Originally published on the Vision blog.

Photo by Klemen Vrankar on [Unsplash](https://unsplash.com/photos/F_7Z1A6Jp_s)
