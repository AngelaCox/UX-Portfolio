---
company:  MYOB
position: Senior Technical Writer
thumbnail: images/MYOB.jpg
project: Documentation audit / information architecture restructure
---

Working with the project, QA and business analyst teams, I scoped and analysed requirements, and performed content audits ready to implement
an information architecture redesign and update the documentation tools. This project is still in flight, so I have documented the strategy I 
planned instead of providing samples. 

## Current Problems

### Issue One
The existing help centres are created in Framemaker, compiled via WebWorks and copied to servers that host the information. This is an 
expensive and insecure method. It's also incredibly slow- to copy a single help centre across normally takes around an hour. 
Changes need to be bundled together as it is inefficient to spend three hours copying for one change (3x help centres). 
Often issues and bugs remain live in the content long after they are identified, waiting for the next content update.

### Issue Two
The desktop product is very old and the help content is enormous. People want it to be more streamlined and usable but nobody knows where 
to start.

## Audit process
The first step is user surveys; internal and external. The survey scope was based on the following three points;

* How easily can you find and use information?
* Which information are you accessing regularly, and why?
* If you could change one thing, what would it be and why?

When the feedback is collated and assessed, qualitative and quantitative audits are performed on the content.
A sample of quantitative audit results:

* There are three main help centres in the desktop product.
* Each of the help centres is single sourced from one Framemaker book, consisting of 24 files, the equivalent of 2500+ A4 pages of content.
* There are more than 15 different conditions and more than 6 expressions to generate the help centres from.
* More than 50 variables, most of which are manually updated.
* Google analytics were also analysed for the qualitative data.

A sample of qualitative audit results:

* There are hundreds of external links, which were once automatically redirected urls. I'm guessing over the years technical writers in a hurry have replaced those with embedded urls and as the external links have been changed, the links are now broken. Hundreds and hundreds of broken links.
* At one point, someone copied a 2014 helpcentre, called it 2015 and has not modified or updated any of the links. This is a particular challenge, as the incorrect links are not broken or incorrect, so a link crawler tool cannot identify these issues. They are pointing to legitimate 2013-2014 pages, which is incorrect for the 2015 product.

The content audit is currently taking place, two of the strategies employed for the audit are below.

## Minimalism
The four principles to cut back the content are:

* Choose an action-oriented approach for content
* Focus on the users real goals (what does the user want to do?)
* Support error recognition and recovery (troubleshooting)
* Accessibility: support information access

## User survey defining if content is used
The content that has been identified as "not being used" will be reviewed.
The internal audience will help define the reason for why it is not being used- out of date, lacks relevance, no longer required etc.

After this process is complete the content will be more relevant, streamlined and usable. Estimates of the post-review content anticipate a content reduction of at least one third. Usability will be increased and customer satisfaction should increase.
The project is currently tracking well with no major issues.
