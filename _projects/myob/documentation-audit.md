---
company:  MYOB
position: Senior Technical Writer
thumbnail: images/MYOB.jpg
project: Documentation audit / information architecture restructure
---

Working with the project, QA and business analyst teams, I scoped and analysed requirements, and performed content audits ready to implement an information architecture redesign and update the documentation tools. This project is still in flight, so I have documented my strategy as an example.

## User audit process
The first step is user surveys; internal and external. The survey scope was based around the following three areas:

* How easily can you find and use information?
* Which information are you accessing regularly, and why?
* If you could change one thing, what would it be and why?

Below I've documented the single biggest internal and external issues identified by my internal and external user review.

### Issue one: internal tooling issues
The existing help centres are created in Framemaker, compiled via WebWorks and copied to servers that host the information. This is incredibly slow- to copy a single help centre takes around an hour (manual copy to a server).
Changes need to be bundled together as it is inefficient to spend three hours copying for one change (3x help centres).
Often issues and bugs remain live in the content long after they are identified, waiting for the next content update.

### Impacts
This impacts real time content delivery and updates but also the team deliverables. Small bugs and issues are sometimes forced to be carried over to a new iteration to be included as part of a larger piece of work, as a full content update for a single issue may not be severe enough to fix. This impacts the backlog and causes frustration both for the tech comms team and the project team.    

### Issue two: external content usability issues
The desktop product is very old and the help content is enormous. Users want it to be more streamlined and usable but internally, nobody knows where to start. There is a real FOMO attitude with content creation for this product: the SMEs are scared that if they leave one single thing out, it will be the one thing the user needs. So they add everything.
This issue is compounded by an inadequate search engine which is configured as part of Webworks. The search engine does not sort, there is no weighted results and all partial results are included. I tested this with a copied and paste section from the help itself: 164 results before the relevant page was found and that was for an exact search.  
### Impacts
Nobody can find anything.

##Content audit process
After the feedback was collated and assessed, qualitative and quantitative audits are performed on the content to help shape the content strategy.
An early sample of quantitative audit results:

* There are three main help centres in the desktop product, each help centres is single sourced from one Framemaker book, consisting of 24 files, the equivalent of 2500+ A4 pages of content.
* There are more than 15 different conditions and more than six expressions to generate the three help centres from, depending on the various release states.
* More than 50 variables, which are manually updated each year.
* Google analytics were also analysed for the qualitative data.

An example of issues found during the qualitative audit:

* There are hundreds of external links, which were once automatically redirected urls. I'm guessing over the years technical writers in a hurry have replaced those with embedded urls and as the external links have been changed, the links are now broken. Hundreds and hundreds of broken links.
* At one point, someone copied a 2014 helpcentre, called it 2015 and has not modified or updated any of the links. This is a particular challenge, as the incorrect links are not broken or incorrect, so a link crawler tool cannot identify these issues. They are pointing to legitimate 2013-2014 pages, which is incorrect for the 2015 product.

The content audit is continuing. Two strategies that will be used to shape the content strategy and information architecture plan are below.

## Minimalism
Four minimalist principles to help cut back the content are:

* Choose an action-oriented approach for content
* Focus on the users real goals (what does the user want to do?)
* Support error recognition and recovery (troubleshooting)
* Accessibility: support information access

## User survey defining if content is used
Any content identified via Google analytics and user feedback as "not being used" will be reviewed.
The internal audience will help define the reason for why it is not being used- out of date, lacks relevance, no longer required etc.

After this process is complete the content will be more relevant, streamlined and usable. Estimates of the post-review content anticipate a content reduction of at least one third (or approximately ). Usability will be increased and customer satisfaction should increase.
The project is currently tracking well with no major issues.
