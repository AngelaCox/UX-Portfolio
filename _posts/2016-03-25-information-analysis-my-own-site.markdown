---
layout: post
title:  "Information analysis: my own site"
date:   2016-03-05 20:36:58
tags:
  - tools
  - information architecture
  - user experience
  - content strategy
  - navigation
---

I think the best way to learn from your mistakes is to really critique your own work. I mean sure, if you know nasty people they can do it for you. Doing it yourself first is a great way to expose yourself to constructive criticism; if you can trust anyone, you can trust that YOU are being constructive! With this in mind, I'm going to work through my design process and critique some of the design decisions I made when setting up this portfolio.

## Plan to fail
![avatar picture]({{ site.url }}/images/twine.png)

Full disclosure? I scrapped my original portfolio design two weeks in. I had originally intended to create an interactive portfolio, using the non-linear story tool Twine. Seriously if you haven't already, [check this out](https://twinery.org/).

I was seduced by how "unique" it would be, an interactive trip through my career! You can add pictures and music, or links, video... except you can't. Not really. Or rather, not without an absolutely herculean effort. And it pains me to admit, but sometimes you scope a project you really want to do, only to realise the time and effort you will dedicate to this project, does not translate into a suitable outcome. And so it was with Twine.

![avatar picture]({{ site.url }}/images/twineoutput.png)

See? That's the final output in its most basic form. Yes, you can fix it up and make it pretty, but sometimes it's better to admit that you need a better solution rather than continue flogging that dead horse.
I decided to scrap this idea, and set up a simple Jekyll website, using BitBucket to manage and writing content in Atom. Ta da!

## Layout and architecture plan
This is not a huge site. I deliberately kept it clean and simple: easy to navigate. For example, if I'm creating high volume content such as help text, I prefer to have a side bar with a nested tree for navigation, or depending on how good the engine is, a search bar at the top. People can see the main headings for navigation and can seek further information as they require or desire.

I did not want the user experience for my portfolio to involve 'seeking' hidden or nested information. The 'seeking' has already taken place, in wanting to see the portfolio in the first place!

## Layout critique
The layout was a single-page bootstrap theme, to get me off the ground (The url is credited in the copyright). I've added a blog (voila!) and created content to sit behind images in the portfolio section. I do think this is an improvement as I felt it was too much information for a single page, without scroll-scroll-scroll. The blog... well. In the LH menu; the posts can be sorted by date, or sorted by tag. Sorting by date is okay, when you click into it, you can see they are sorted by year. You can't see the actual date without clicking into a specific post. A minor thing.

When you sort posts by tag, ugh. I think I'll make more stylistic updates going forward. The posts sorted by tag have generated a mysterious numeral next to each one. I eventually worked out this was the number of posts for each tag but I'm not ashamed to admit that took me a second. I think the blog section isn't very intuitive, so I'll put some thought into improvements.

And lastly when you click an anchor (e.g. the full tag list under the Tag Archive heading) it drops you to the location, however the heading you clicked is NOT the middle of the page, it's crammed up the top. This is not intuitive and leaves you searching. When you compare that to the nice slide animation on the front page (when clicking from one heading to another in the sidebar), it becomes very irritating.

That's probably plenty of criticism to work on! I'm off to go cry myself to sleep, then come up with a plan to fix it. And one of these days, I'm going to start a new Twine project!
