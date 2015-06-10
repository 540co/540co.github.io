---
layout: post
title:  "It's not about the App, It's about the APIs"
date:   2015-05-09 15:20:15
author: John OBrien
author_image: john.png
excerpt: "Sometimes I feel like a broken record when evangelizing the importance of data sharing (even within the secure walls of the Pentagon) and how important it is to ensure that data is available via an API..."
---

![HEADER IMAGE](http://cdn.meme.am/instances/500x/50238076.jpg)

###"It's not about the Apps, It's about the APIs"

**Sometimes I feel like a broken record when evangelizing the importance of data sharing (even within the secure walls of the Pentagon) and how important it is to ensure that data is available via an API when deploying new systems / etc.**
 
But last week at the [DC API Meetup](http://www.meetup.com/DC-Web-API-User-Group/), Denise Ross [@dianewross](http://twitter.com/dianewross) reminded us that “it’s not about the APPS, it’s about the APIs” as she described successes, iterations and learnings from [Department of Energy’s (DOE) Project Lantern](http://archive.federaltimes.com/article/20141202/FEDIT03/312020016/Feds-developing-plan-crowdsourcing-citizen-science) mobile app.   

We even talked (err, rambled) about it at last week’s [540-15](https://www.youtube.com/watch?v=hGdToyFBnO4) as we discussed the importance of an API-first strategy to collecting and sharing data.

Government leaders nodding their heads at the importance of data  / APIs, telling story’s where API-first approaches were taken and/or should have been taken, etc. - **all in all it was a successful week for us government API evangelists out there.**

**Then the week came to a close and I started getting emails / messages about the [Defense Technical Information Center DTIC](http://www.dtic.mil/)’s release of the [DoD Investment Budget Search](http://www.dtic.mil/dodinvestment/#/home).**


--

As many of you know,  I have been in the trenches parsing DoD Budget data for awhile - so this was exciting for me.  #dontJudgeMe

**I have worked with our client’s to grab key "needles" out of the XML "haystacks" (manufacturing data, R-3 items, etc)** as well as painstakingly harvested / parsed all of the [DoD Justification Book XML’s exhibits into manageable line items / program elements](https://fedapi.io/www/overview/dodbudget) as part of our [FedAPI platform](http://fedapi.com) and published [flat versions of the exhibits on Github for business analysts.](https://github.com/540co/dod-president-budget-procurement-rdte-data)

**I had heard DTIC was working on de-constructing the XML and making the data available...**

- Could this be the point in time when the data was finally ready for simple consumption from the data provider?

- Will there be an API to get to the data so we don’t have to re-parse / index to simply use the data to build apps and support analysis, or at least some CSV files so we can easily download and index the data?

- Will I be able to stop waking up in the middle of night every year around February to fetch the PDFs, extract the XMLs designed for printing the PDF's and hope that the XML schema didn't change too much?

--

**Unfort, it wasn’t any of that - as I was confronted to just a search app with some graphs - limited to the R-2 and P-40 exhibits - that seems to really just help me get to certain sections of the PDF.**

No easy way to download the data and definitely no APIs.

**Sure - I can see some value in the Budget Search - and I can see how it can help functional users / analysts search and retrieve the data in those exhibits.**

- But I see no clear path to get to much of the structured data that our DoD analysts are often starved for (the last thing they need to see is another PDF that they have to copy / paste from)...

- Or for app / common operating picture (COP) builders across the DoD who want to use this **common operating data** with other data sets - to readily consume / query the data in a programmatic way...  

**Sure, it gives me work to do - but I would so much rather be using those hours to build value on top of the data vs. parsing it.**  

And how many other folks are out there doing the same thing?  I keep finding pockets of folks every few weeks that have been working to parse this data... or say it is too hard and don't leverage the data.

**Looks like when I walk into the Pentagon this week, I'll have to restart that broken record...**