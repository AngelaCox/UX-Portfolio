---
layout: post
title:  "Acceptance testing outside software"
date:   2016-03-05 20:36:58
tags:
  - non-software
---

I've decided to write a series of posts on technical writing topics outside of software. I think there are many valuable skills from other industries that software technical writers can apply to their careers. How many of us have bothered to really think about how our procedures fit into the wider business? What information security means to us as technical writers?

For my first post in this series, I'm going to talk a little about acceptance testing outside software, because it is *really* different to what we do in a software environment.

I won't dwell on this but an acceptance test in its most basic form is a yes or no answer regarding a question- usually user driven. That is, a pass or fail on a *specific* user story created by a customer, given to the developers. It may be called different things, but that's how it works.

Acceptance testing in engineering or operational environments, is a lot more complex. I worked on a multi-billion dollar hospital project where test plans were monitored by independent auditors and used a cross-functional process team that may require upwards of 50 people per live test. Additionally, these acceptance tests were contractually agreed across multiple parties and were a binding legal requirement to fulfill the contract. You can't turn around just before release and go **shrug** "this can't happen in this iteration". You lose your multi-billion contract when that happens.

Creating test plans in these circumstances was incredibly interesting. As a technical writer, it doesn't often fall to us to perform such functions, they're normally completed by teams of business analysts or other specialists. The test maps themselves were huge and required months to workshop, as they are an interlocking series of processes, across multiple teams and departments.

A good example is 'admitting a patient'. You would assume that starts at the admissions desk, yes? No. When you think carefully about how you are admitted to hospital, it happens for a reason (Duh) and the reasons are called "triggers". A trigger starts a process, and an acceptance test will begin with a series of potential triggers: admission following a scheduled doctor appointment, admission following an emergency doctor appointment, admission from an ambulance following a call to emergency, admission from another hospital etc. Each of these scenarios begins a different way: there might be a doctor involved, an ambulance crew, a medical chopper etc.

 When a scenario is tested, one trigger and one series of options is tested all the way through the entire admission process, from the trigger through to how they get to their bed. This includes getting all the patient's details (Is the patient conscious? What is our process if not?), which department takes the patient to their bed, who gets the patient **into** their bed (Orderly? Nurse? Porter?), and so forth.

 Learning how to map processes is a valuable skill for anyone working for a business and particularly for technical writers, because the procedures we write every day, are drawn from business processes whether we realise it or not. In this particular role, I learned things like managing a cross-functional workshop across a business, how to think a process through and map it, looking for variations, pitfalls and other issues. But a lot of my learning was around communication and how to ask the *right* questions. And learning how to map an end-to-end process, taught me a lot about writing procedures, who the audiences are and how important this information is, to people trying to do a good job. If you only take one thing away from this article, I would recommend it be that you try to understand how hard you can make people's lives if you don't care about making their jobs easier.
