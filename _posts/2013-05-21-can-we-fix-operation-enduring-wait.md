---
layout: post
title: Can We Fix Operation Enduring Wait?
permalink: /blog/read/can-we-fix-operation-enduring-wait
---
Last night, the Daily Show ran a great segment (watch it!) on the billion dollar technical catastrophe called the VA and DoD's health record interoperability program. Essentially, it asks a good question: if the Obama campaigns of 2008 and 2012 could so quickly unite large disparate databases in order to elect our president, then why is it taking years and billions to streamline health IT for veterans? The segment ends with:

Well, only sort of. Because it's nearly impossible for government to just hire the guy who led that construction, Harper Reed, and to allow for Harper to hire the people he needs in order to get that done.

Let's talk about why it's so hard for government to do that.

"To the victor goes the spoils!"
--------------------------------

That was the old saying in American government up until the beginning of the last century. When elected president, the friends of the president got the cush government jobs and contracts that went alongside the victory -- a patronage system. Run loosely, this was a key cause of a lot of corruption, entrenchment, and even the assassination of James Garfield.

In 1883, we began to see move away from this patronage system to a "merit based" civil service with the passage of the Pendleton Act. From Wikipedia:

But today, especially in the world of engineering, those competitive exams seem to be competitive tests of will and patience, rather than merit-based engineering tests.

If someone like Harper Reed wanted to work for government as an employee, he'd have to go through an exhaustive series of background checks ranging from an extensive credit inquiry (why do you have a $200 outstanding debt from Verizon from 15 years ago in College) to international travel (do you have anyone who can vouch for all of your whereabouts when you backpacked through Thailand) to residency checks (please give us contact information for someone who can vouch for your good character in every place you've lived in the past 7 years). Applying to a federal position involves exhaustive background checks, but Harper wouldn't be asked for any code samples.

The spirit of the law is well intended. While the will of the people is important, it is probably important to the continuity of the business operations of government that the president does not get to fire everyone who disagrees with her or him. If you're an environmentalist: imagine a president firing the whole staff of the Environmental Protection Agency, and replacing them with the executive staff of BP America. If you're a war hawk, imagine the President firing the citizen staff of the pentagon and replacing them with volunteers from CodePink. But it also makes it so that people who are demonstrably under-talented or uncommitted to the job are difficult to terminate.

At the same time, it's made very talented people hard to hire. While many computer programmers may opt-out of higher education, not having a Bachelor's degree will effectively screen you out of the first round of hiring -- software will eliminate you before a human even gets to think about it.

If talented people are hard to hire, and untalented people are hard to fire, in a place as competitive as technology, how can government get anything done?

Do your bidding
---------------

A private business is allowed to hire and fire people as they (or they, in partnership with their employee union if that's the case) see fit. So in information technology, the federal government largely turned to the private sector. With the exception of edge-case programs like the Presidential Innovation Fellowship of which I was a part, real programmers (people who can write code in text editors and terminal windows) in government are hard to find.

So if the United States wanted to hire Harper for a federal project, such as the VA+DOD integration, it'd probably be easiest to hire Harper and his team to start HarperCo and contract with Government. But even if the president knew that Harper could do the job, and do it better than anybody else, he couldn't just hand over the contract to Harper. After all, that'd still be a significant patronage.

Instead, the VA and DoD would have to write a RFP for the exact requirements of the work and put that out to for public bid. Using a network of Contracting Officers (who are not technologists) and assisted by an appointed Technical Representative(who are rarely technologists), they draft up detailed specifications of what's needed. Sometimes, they seek outside community guidance in the form of public requests. However, should HarperCo start providing direct feedback on this RFP, HarperCo would likely be disqualified from bidding on this contract. So because government cannot hire people to figure out the solutions, and cannot ask qualified people what solutions to ask for, government tends to ask for a lot.

Which is why Recovery.gov ended up costing 18 Million Dollars. Take a look at the RFP they came up with. Data Cubing? XML Firewalls?

But let's say that government miraculously asked for exactly the right thing, and HarperCo responded to RFP with the lowest bid. Would Harper win? Not likely. Harper's firm is less than 2 years old (strike one), and owned and operated by a white male who is not a disabled veteran (strike two), and has no experience in federal contracting (strike three).

Instead, government would use the Alliant Governmentwide Acquisition Contract for a procurement like this. A Government Wide Acquisition Contract(GWAC) is a way for government, through the General Services Administration to pre-negotiate hourly rates, profit margins, and costs with outside contractors. Alliant is the largest of this kind of contract in information technology, with a ceiling of $50 Billion. There are about 60 companies (Raytheon, Accenture, IBM, etc) who have negotiated this kind of contract with GSA. It's not open to any new businesses.

So Harper would have to partner (or "team" in industry speak) up with one of these existing firms (we'll call our hypothetical one PrimeCo) to do the work. The prime contract would go to one of these 60 firms, and they, in turn, could subcontract out to Harper.

Harper, being a generally honest fellow inexperienced to government contracting, would probably estimate the number of hours it would take him to do the job to be similar to the campaign. Let's assume that HarperCo assumes it will take 12 developers, one designer, and two project managers one year of full time work. That's 30,000 man-hours. Let's say the billable rate for the project is an average of $200 per hour. That's a $6,000,000 cost. But government has mandated in its negotiation that PrimeCo is bound to a pre-negotiated profit margin of ~10%. There's no way that one of these companies can survive its largesse by doing projects like this and walking away with just $600k.

So what they can't get in hourly margin, they make up in volume. Before sending on his proposal to government, PrimeCo decides that Harper needs an additional 30 developers for support, and 20 new project managers. Remember, these are publicly held corporations. It's their legal, fiduciary responsibility to return as much profit to shareholders, not to save the tax dollars of citizens. Now we're getting somewhere with the profit we can generate. We've still only got the contract up to a measly $2.6 Million in profit, but you can see where we're going, and how it's done. Now that we've added all these people to the process we've created layers of bureaucracy and expense, and additional points of failure. Enough to chase off guys like Harper from even doing this.

You can see the policies and behaviors that end up causing billion dollar IT fiascoes, and more importantly, the good intentions that got us here.

Nobody Likes Incompetent Government
-----------------------------------

I can already hear a chorus of libertarians singing praise of this post. "See! Government can't do stuff effectively! That's why there should be limited government!"

Listen: unless you're an anarchist, you have to believe in some form of government. Whether you believe government should be very small, or that government should be an instrument of good, you obviously want the people running it to be the brightest and the best. These problems aren't a question of this very tired national argument of whether government should be big or small, but rather whether government should be competent or not. If nothing is done about this, even if Grover Norquist was able to shrink government down to the size where it could be "drowned in a bathtub," you can bet that the bathtub would cost ten billion dollars.

So we have to fix this -- the way that government hires and the way government buys are the central nervous system and circulatory system of government. They're vital to working well. We all want government to be a platform but the truth is, the platform's held together with duct-tape and billion dollar toothpicks.

So the question is, how?

Well, first it's by giving up on the nonsense of our current political debate. It's a lot like our obsession with our bodies being fat vs. thin rather than sick vs. healthy. It's a gross frame that doesn't do anybody any well, and as long as that's our frame we'll continue to make stupid decisions. As Stewart implies, it lets us off the hook -- where we'll knock on 5 million doors to elect a president, but won't lift a finger to help soldiers get access to their own medical records. We've got to start caring a lot less about electing, and a lot more about governing.

Once you do, then it becomes about two policies inside of government: Procurement and Human Resources. How government buys things, and how it hires. I'm helping to fix the former that through The Department of Better Technology -- by building tests that prove that governments can buy better technology by avoiding these huge primes and going directly to the HarperCos of the world. We'd love your help, either by contributing to the open source software, deploying it in your community, or by asking your local government to enroll in the pilot.

But obviously "helping my project" isn't the only way to help -- that'd be self serving. Government can be a platform but we've got to start advocating for sensible change in policy that opens government's doors to innovators and new businesses. While federal policy may change, it's easier to start with your local city or county. Start asking questions: how much did yourcity.gov cost? Who made it? How did they win the contract? Why?

Fixing this problem isn't a question of policy, it's a question of will and attention. Should the public start paying real attention to these problems, and start questioning these policies that make government and the private sector partner up so poorly, we may have an opportunity to make change. But as long as the word "procurement" causes eyes to grow full of glaze rather than action, we'll see no progress.
