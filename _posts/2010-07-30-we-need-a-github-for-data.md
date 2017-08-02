---
layout: post
title: We Need a GitHub for Data
permalink: /blog/read/we-need-a-github-for-data
---
 The biggest problem many data-driven apps contests have is that it’s too hard to get started. A developer has to download some strange dataset off of a website like data.gov or the National Data Catalog, prune it, massage it, usually fix it, and then convert it to their database system of choice, and then they can start building their app. It reminds me of being a Linux user before APT existed. While fun, it was still a hassle to get all dependencies and compile everything from source.

 It’s also too difficult to put data onto the web. You can put source code on a web site like Github or Bitbucket. With data, sure, I can ftp or scp something to a server — or, as I did with my obesity and partisanship data, just stick it in dropbox. But that doesn’t do half of what I get out of publishing my source to Github .

 It’s too hard to put data on the web. It’s too hard to get data off the web. We need a Github for data.

 With a good version control system like Git or Mercurial, I can track changes, I can do rollbacks, branch and merge and most importantly, collaborate. With a web counterpart like Github I can see who is branching my source, what’s been done to it, they can easily contribute back and people can create issues and a wiki about the source I’ve written. To publish source to the web, I need only configure my github account, and in my editor I can add a file, commit the change, and publish it to the web in a couple quick keystrokes.

 Plus, you get all the other things the web comes with. Just as github has source highlighting baked right into the service, data viewing can be baked right into the Github for data. Since most people can’t view large datasets — the best thing they have is usually Excel, many versions of which can’t handle more than 65,000 rows. But the web has great tools like Socrata or even simpler tools like Congrelate which make it easy to view and search large or complex datasets.

 Getting and integrating data into a project needs to be as easy as integrating code into a project. If I want to interface with Google Analytics with ruby, I can type gem install vigetlabs-garb and I’ve got what I need to talk to the Google Analytics API. Why can I not type into a console gitdata install census-2010 or gitdata install census-2010 —format=mongodb and have everything I need to interface with the coming census data?

 To make data more engaging to the public, it’s first got to be more engaging to developers. Take this discussion on the Sunlight Labs google group. I’d bet that we’d have a lot more people actually engaging with the Wikileaks data on Afghanistan if we had a github for data. Not only would developers have an easier time integrating the data into their projects (though wikileaks does a good job with file formats), but the public would be able to see forks and branches of the dataset and perhaps the projects built upon it.

 Infochimps, Amazon, National Data Catalog, Socrata, and Github (though git might not be the best solution) all have a piece of this puzzle. All the components are there. Hopefully one of them will fill out the rest. Or maybe a person reading this blog will create a new startup. It’d be great social venture, and a fairly defensible business.

 I neglected to put in ckan as one of the organizations setting out to solve this problem at writing. Purely an oversight. They’re doing good work there, too.
