# The difference between acceptance criteria and definition of done

WEDNESDAY 14 DECEMBER 2016

Back in August I wrote a post called “[How do you know when you’re done?](http://digitalcommunications.wp.st-andrews.ac.uk/2016/08/31/how-do-you-know-when-youre-done/)” in which I explored the agile concept of the “definition of done” or “done done”. However, in conversations with developers over the last few weeks I’ve observed a confusion between acceptance criteria and definition of done. So, let’s use this post to tease out the differences.

## **tl;dr**

In a nutshell, the differences are subtle but simple. While both are used to prove that a feature is complete, the scope of each is different.

The definition of done is, generally speaking, a list of requirements that must be satisfied for all user stories. These are set at the start of the project and rarely change.

Acceptance criteria (or user story acceptance criteria), however, are particular to each feature being developed. They are set at the start of a sprint and may change as development progresses and more is discovered about that feature.

## **Building a house**

Who would live in a house like this?

To explain this, let me move away from software and website development, and consider houses.

Let’s imagine for a moment that you are a building contractor and have been commissioned to build 10 new homes.

You have a plan for each house. They will be small, single storey houses each with two bedrooms, a living room, a kitchen, bathroom, and a walk-in cupboard for storage. Each house will have four outer walls, four windows, and a sloping roof. They will be powered by electricity (no gas), and plumbed in for water and waste.

### **Definition of done**

A definition of done for building these houses, then may initially look something like this:

* Must have four outer walls of brick.
* Must have a sloped, tiled roof.
* Must have a secure front door (high security level lock as minimum)
* Must have four windows.
* Must be wind- and watertight.
* Must be wired for electricity.
* Must be plumbed in (water and waste in kitchen and bathroom).
* Must pass building control inspections and receive a special certificate.

As you can see, this list is fairly generic. It could apply to any of the 10 houses on the street. If the house was built with wooden walls, or a flat roof, then it wouldn’t pass. But regardless of what else was done to the house, if it passed those eight criteria then it could be regarded as done and the house could be put on the market.

### **Acceptance criteria**

Now, let’s imagine that we have a customer, Nigel, who wants to buy house number four. Nigel is particular about the kind of house he lives in, so he takes a look at the brochure and picks out a few options that he likes:

* The front door must be mahogany, and be painted blue.
* Front door lock must be a Yale platinum 3 star (maximum security level) lock.
* The window frames must also be mahogany.
* One window must be a Velux® window fitted in the roof.
* One window must be round and situated above the front door.
* The electrical sockets must also be fitted with CAT-5 computer network ports.
* The kitchen must have a double oven and oak worktops.
* The bathroom must have a bath and shower.

This list is very specific and applies only to house number four. These details don’t need to be gathered until just before the house is built. Not every house needs to be built to these exact specifications. This is the acceptance criteria only for this particular house. If these criteria are not met then Nigel isn’t going to buy this house, regardless of whether the definition of done criteria are met or not.

Now, let’s imagine that there is a national shortage of mahogany doors and window frames. As the building contractor, you contact Nigel and explain the situation. Nigel isn’t particularly happy but accepts that this is outwith your control, so he takes another look at the brochure and selects a nice oak door and matching windows. Here, one acceptance criterion has changed due to something that was discovered during development.

Development continued until all the acceptance criteria and the definition of done criteria were met. After which the house was sold to Nigel who was delighted with his house, and lived there happily for many years with his cat, Haggis.

## **Our definitions**

For the digital pattern library project we have the following criteria defining done:

* Must adhere to code standards and style guidance.
* Must be accessible, including using WAI-ARIA landmark roles.
* Must include print CSS rules.
* Code must be well-commented to explain why it has been done in a particular way not what it does — that can be gleaned from the code itself: prioritise the why over the what.
* Documentation needs to comply with house style and writing for the web guidelines.
* Drop the ‘related patterns’ section of each pattern as the new interface for categorising patterns will make this redundant.
* Need to convey how a pattern relates to another e.g. breadcrumb pattern must only be used after a navigation pattern.
* Code must be version controlled, with each feature in its own branch, and a pull request created to merge into master.
* The change log must be updated.
* Merge to master may only take place after a peer code review, and deployment to live environment for testing.
* Must meet acceptance criteria for the feature.

These are generic guidelines that may apply to every pattern we create or edit in the code base. They ensure a consistency of approach and quality.

We often copy this list into each feature card in Trello as a reminder about what we need to check before we move the card into testing, or again into done.

The acceptance criteria is then defined within the card for each feature, and is different for each pattern. For example, the accordion must work equally with one accordion or six; the header pattern must also include a condensed header for web applications; the footer pattern must use social media icons from the Font Awesome set rather than Glyphicon, etc.

## **Conclusion**

As you can see, both the definition of done and acceptance criteria are used to ascertain whether a particular feature is complete or not but they are defined at different times, and have different scopes.

Definition of done is defined up front before development begins, and applies to all user-stories within a sprint, whereas acceptance criteria are specific to one particular feature and can be decided on much later, just before or even iteratively during development.