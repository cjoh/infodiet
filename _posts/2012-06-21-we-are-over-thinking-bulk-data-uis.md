---
layout: post
title: We Are Over Thinking Bulk Data UIs
permalink: /blog/read/we-are-over-thinking-bulk-data-uis
---
I'm pretty excited about the Consumer Financial Protection Bureau's new consumer complaints data. While they call it a "database" it's currently more of a spreadsheet of complaints against credit card companies from consumers, and the broad category of what that complaint is. It's minimal data right now. They only are releasing data past June 1, 2012, and so far I can only count 171 rows. But it will grow, and hopefully over time, it will become useful.

But more important than the data's release, the way that it's been released got me thinking that maybe we're overthinking how to provide online. To get to the data, you go to the consumer complaints database page, then click on the small "all data" link under the strange set of squares presumably to resemble a spreadsheet. This opens up a socrata instance, where you'll need to click up in the top right where it says "export" and then click where it says CSV underneath that.

That's a lot of software to put a 172 row CSV file on the Internet.

I think Carl Malamud has it right. With his projects, he's worried about suppliying the bulk data in as bulk data friendly of a way as possible. He's used mod\_index (built in to apache), and a little bit of light design, and there's a user interface that's nearly universal. Malamud's challenge isn't software, it's organization and discovery. That's where the real challenge lies anyhow. Try and find IRS Statistics of Income data on bulk.resource.org. As soon as you see it, you know exactly how to get to it, and exactly what you're getting. You don't need to learn how to use this website -- you already know.

Please do not misunderstand me: I think Socrata is useful. I'm happy they're doing what they're doing. For average people, I think being able to take a look at the data in a table is great. Most people can't load a 50MB spreadsheet on their computer, and Socrata makes it easy to view a large dataset over the Internet.

But for the people who will actually do things with this data -- whether they be academics, journalists, businesses or programmers -- will likely find the Socrata experience limiting compared to what they can get out of SQL or Excel. Delivery of data over the Internet should be aimed at trying to make it as easy as possible for people to get your data into those tools. An ineffective and costly strategy involves trying to replicate those tools. You're creating learning curves and user burdens where they ought not be.

I'd love to see a bulk.data.gov aimed at replicating the bulk model for data distribution -- it's common and simple. Malamud's using the model for distributing the code of federal regulations and GovTrack uses it to distribute bills. I would have loved to see it before we got Data.gov -- as it seems lots of development has happened on a platform that fewer than we'd hoped are using (both on the data supplier and provider).

The bulk model Tauberer's GovTrack and Malamud's Resource.org use also easily allow for freshness and more openness. They provide rsync support -- a way to make sure data stays fresh and up to date without consuming a whole bunch of bandwidth. As the files add up on Data.gov, how do we only get what's new?

Finally, the bulk model allows for vendor independence. Again, while I have much love for Socrata and what it's designed to do, it's also the case that this kind of data distribution must be as platform independent as possible. While we talk about how open data can power the next Weather industry or the next GPS, I suspect none believe that it will be with Socrata as a middleman. By relying entirely on Socrata for data distribution, we place government in a concerning position where it's dependent upon a proprietary vendor for data distribution, and the economics of success depend on them staying in business.

So if you're out there, govvies, and you're reading this: Please, rethink your data distribution strategy. Do you need to put that csv file in Socrata? Or can you just upload it to your web server?
