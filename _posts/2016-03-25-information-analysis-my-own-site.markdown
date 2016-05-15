---
layout: post
title:  "Information analysis: my own site"
date:   2016-04-05 20:36:58
tags:
  - tools
  - information architecture
  - user experience
  - content strategy
  - navigation
---

One of the best ways to learn is to review your own work publicly, then others can learn from them too! In this post, I'm going to critique some of the design fails I've noticed while setting up this site.

## Plan to fail

![avatar picture]({{ site.url }}/images/twine.png)

Full disclosure? I scrapped my original portfolio design two weeks in. I had originally intended to create an interactive portfolio, using the non-linear story tool Twine. Seriously if you haven't already, [check Twine out](https://twinery.org/), it's really cool.

I was seduced by how 'unique' it would be, I could create an interactive, clickable trip through my career! There could be pictures and music, or links, video... except I couldn't. Not really. Or rather, not without some serious hours put in. 
Sometimes you can scope out a project you really want to do only to have to admit to yourself the time and effort required aren't going to translate into the professional looking outcome you expected. 
And so it was with Twine.

![avatar picture]({{ site.url }}/images/twineoutput.png)

See? ^^ That's the final output in its most basic form. Yes, you can make it more pretty, but sometimes it's more cost effective to admit that you need a better solution and scrap it, rather than 
continue out of mistaken pride or because you're really stubborn.  *Cough*.  After a bit of analysis, I concluded that nobody coming to check out a portfolio is going to be impressed by something that 
looks 'kind of okay', even if I do show them how bad the original was. 

I decided to scrap Twine and set up a simple Jekyll website, using BitBucket and Aerobatic to manage hosting, and wrote the content in Atom. This is a far superior outcome, even if Twine still IS
really fun.

## Layout and architecture plan
This is not a huge site. I deliberately kept it clean and simple: easy to navigate. If I'm creating large amounts of content such as help text, I prefer to have a side bar with a nested tree for 
navigation, or depending on how good the engine is, a search bar at the top. People can see the main headings for navigation and can seek further information as they require or desire.

I didn't want users to be 'seeking' hidden or nested information. The 'seeking' has already taken place, in a person wanting to see the portfolio. I don't want to make it harder for me to look good.
This simplicity translates well to smaller devices too. I found the site layout easy to use and read on a tablet, an iphone and an android phone.  

## Critique
It's almost *too* basic. The original layout was a single-page bootstrap theme, to get me off the ground (credits are on  the [copyright]({{site.url}}/copyright) page). I've added a blog and created 
content to sit behind images in the portfolio section. I do think this is an improvement as I felt it was too much information for a single page, without scroll-scroll-scroll but it's also no marvel 
of design innovation. In saying that, I really don't think there is a need for further complexity, so I probably would leave it as it is. Simplicity is okay after all. 

The blog posts layout... well. The posts can be sorted by date, or by tag. Sorting by date is okay, when you click into it, you can see they are sorted by year. You can't see the actual date without 
clicking into a specific post. When you sort posts by tag? YUK. GROSS. EWW. I really hate that and I'll definitely make stylistic updates going forward. The posts sorted by tag have generated a mysterious 
numeral next to each one. I eventually worked out this was the number of posts related to each tag but I'm not ashamed to admit that took me a second to work out. I don't think the blog section is great, 
so I'll put some thought into intuitive improvements.

When you click an anchor (e.g. the full tag list under the Tag Archive heading) it drops you to the location, however the heading you clicked is NOT the middle of the page, it's crammed up the top. 
This is not intuitive and leaves you searching. When you compare that to the nice slide animation on the front page (when clicking from one heading to another in the sidebar), it get irritating.

Annoyingly, at the top of the side bar my name appears. This should be a link- I keep clicking it myself, trying to get back to home and it doesn't go anywhere. It's **really** annoying. 
I've also discovered that clicking a link to an external site does not open a new tab, it opens in your current tab. I'll definitely be fixing that, it's no help to me if the reader clicks a link 
and gets pulled away from my site. 

That's probably plenty of criticism to work on! I'm off to go cry myself to sleep, then come up with a plan to fix it.
