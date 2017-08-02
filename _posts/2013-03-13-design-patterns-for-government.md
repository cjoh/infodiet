---
layout: post
title: Design Patterns for Government
permalink: /blog/read/design-patterns-for-government
---
The book "Design Patterns" sits on top of most a young programmer's bookshelf. It's almost a status symbol -- sort of a silent agreement between two professionals -- a display that says "I get it" even if it's gone largely unread by most of its owners.

To grossly oversimplify, imagine that there's two different kinds of programmers: cooks and chefs. Cooks understand recipes, they can follow them, and when they follow them, their food looks and tastes good. But only chefs really understand the food. They are the ones who make the recipes.

It's because chef understands how the food works together. They understand the fundamentals of flavor, and the interoperability of food. They understand the nuance of time and temperature, and how fat and protein work together. Asking a cook to change up a recipe is a recipe in trial and error. Asking a chef to do the same has a higher probability of success because the chef understands the patterns underlying the food.

For a programmer, putting Design Patterns on your desk at work means "I want to be a chef, not a cook." (This also explains why so many copies of this book have been sold, yet so few people have read the book)

As government increases its online capacities at the local and federal levels, it needs to make the transition from thinking like cooks into thinking like chefs. When you look at things abstractly, you start to see areas of opportunity to solve repetition.

Pattern 1: Vetting and Selection
--------------------------------

For example -- RFP-EZ is the project I worked on during my fellowship. It's intended to make it easy to post RFPs online, to make it easy for small businesses to bid on them, and to make it easy for people inside of the government. When we (the fellows) were asked what the ideal software would be to manage the application process for the next round of innovation fellows, we started designing some rudimentary software for it, but it turns out we'd already done it: RFP-EZ, abstractly, is a method for posting a request online, gathering feedback from that request, and collaborating on deciding which piece of feedback was best. It could work just as well in a hiring decision as it can in a procurement.

So if you've applied to become a Presidential Innovation Fellow, you've used a version of RFP-EZ with enough garnishes that we call it HIRE-EZ.

I think there are a bunch of abstract patterns inside of the open government movement that we should be moving towards. The RFP-EZ/Hire-EZ one is an example of one I like to call "Registration and Vetting." We make this kind of application and do this kind of work for government a lot -- whether it's selecting a new fellow, running a procurement, or ensuring that you're qualified to drive or that your business is qualified for the benefits it receives.

But government isn't particularly good at this process. It can take months to register your small business as a small business with the small business administration. Nobody likes going to the DMV. Perhaps if it thought of the process a bit more abstractly, efforts could be shared, repeated, and more innovation could happen where it matters. A cook says "let's upgrade the software at the DMV." A chef says "let's figure out the right recipe to make a basic piece of software, policy and process work great, then let's share that and let people add the right garnishes to fit their specific need."

Pattern 2: Information Collection and Analysis
----------------------------------------------

You would be shocked at the amount of time, effort, and money spent on government putting a form on the Internet and having the results of that form go into a spreadsheet for future analysis and policy making decisions. I would not be surprised if you could find the entire sequester budget cut solely in projects that simply do this. Millions of dollars in both time and budget are spent on convoluted systems that all do exactly the same thing.

This costs the rest of us zero dollars. Solving this problem inside of a government once will improve the citizen experience, and save the taxpayer billions of dollars.

Pattern 3: Redaction and Distribution
-------------------------------------

Remember the amazing costs of FOIA. It's a half-billion dollar problem that needs to get solved. Coming up with the right patterns (and software) for government to be able to quickly and properly release information is made for reusable components.

This goes beyond FOIA -- it needs to identify a dataset that should be open, to qualify it, to redact personally identifiable information from it, and to put it on the Internet. We need a technical process for releasing information and the open, interoperable software that goes along with our open government policies and directives.

Pattern 4: Service Requests
---------------------------

Open311 solves this at the physical municipal level. Services like SeeClickFix know this and are leveraging this design pattern into substantial businesses. But the pattern goes beyond potholes. How come there's no bugs.data.gov that allows developers to report back bugs in data from something that comes off of it? Any other open technical release is accompanied with an issue tracker. It's the same technical pattern.

Pattern 5: Performance Management
---------------------------------

Government spends a lot of time measuring how it's working. Whether it's via internal performance goals, or through services like Recover.gov, or through legislated mandates like the Paperwork Reduction Act's Paperwork Burden Esimations.

I'm probably the least versed in this pattern than anything else I've mentioned. But I know government spends a lot of time measuring itself, its employees, its contractors, and its actions. It's an area rife with failure, and failure here means retaining bad talent, enforcing bad policy, and managing things inappropriately.

Abstract doesn't mean Enterprise
--------------------------------

One might think that this is a great opportunity for "enterprise software" -- the case for more multi-million dollar IT projects that solve many problems poorly rather than a few, well, poorly.

These patterns are not nearly as much about technology as they are about process. It's likely, for instance, that it doesn't require a "data management system" from a ALLIANT QUALIFIED VENDOR to solve the redaction and distribution pattern. It probably just requires a dropbox folder installed on a government worker's desktop labelled "Open Data," and a technical and editorial process for what happens when a new file is added to that folder.

Talking about these types of patterns will be a boon to large contractors if you let it be. But in general, we're talking about figuring out playbook patterns to run, figuring out why they work, and reusing them. Usually they're small and simple, not large and complicated.

This is far from an exhaustive list -- but I'd imagine there are only a handful of repeatable patterns in the citizen/government space. And I think we ought to focus on identifying those patterns, and finding the right people to design the technology and process to implement them rather than shipping apps that fit niche needs for government.

Why you should care
-------------------

The debate in Washington over funding and budget is nonsensical. It's as though America is a sputtering car on the highway, and we all agree we need to get the engine really revving again. The republicans say that the problem is that we've got too many people in the car. To make the car speed up, we should just throw a substantial portion of the passengers out. The democrats say that the best way to do things is to put more fuel in the tank and hit the gas.

The real problem isn't the passengers or the gas tank. It's that the car's engine only gets 10 miles to the gallon, and we pay 10x more for gasoline than everybody else. These design patterns help increase the miles per gallon, and reduce the cost of gas.
