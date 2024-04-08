# Blue Team Level 2 Writeup
## Intro

Blue Team Level 2 (BTL2) by Security Blue Team is an excellent course and certification for those interested in furthering their career and knowledge in security operations and incident response beyond the junior and intermediate levels. I had the privilege to take and (thankfully) pass the exam early 2024, and can say with confidence - this exam is no joke. They provide 5 months access to the course and lab environment (w/ 120 hours of lab runtime), and you better believe I utilized all of the time available (extentions are available to purchase for those that need some extra time).

I will not go into detail on what each of the domains/sections specifically cover in detail (there are other writeups I'll link below for that), but I will provide context to how I felt about and approached each domain. I'll also share some exam tips I think helped me pass.


## A bit of background and context

I have worked in IT and Information/Cybersecurity since 2012 when I was an IT admin intern during my last few years of university. My career progress is as follows:
- IT Admin Intern
- Helpdesk Technician
- Security Analyst
- Systems Administrator
- Security Operations (SOC) Engineer
    - 2022 - Passed BTL1, CySA+
- Detection and Response Engineer
    - 2024 - Passed BTL2

I was fortunate enough to have a good deal of experience in IT/Cybersecurity before taking the Security Blue Team certifications, but I do believe the coursework provided, for the most part, does a good enough job on setting students up for success to pass the exams.


## Overview

Dubbed "the world's hardest practical blue team exam" by its creators, BTL2 expands on its sibling exam Blue Team Level 1 (BTL1) by digging into cybersecurity domains:
- Malware Analysis
- Threat Hunting
- Advanced SIEM
- Vulnerability Management

If you're looking for details on each section within these domains, you can check out these writeups from other BTL2 certified legends:
- [Krzysztof](https://medium.com/@krzysztof.kuzin/blue-team-level-2-btl2-531a9ebc2cbc)
- [Domedion pt1](https://www.domedion.com/2022/03/21/blue-team-level-2-review/)
- [Domedion pt2](https://www.domedion.com/2023/01/16/blue-team-level-2-btl2-review-part-2/)

SBT also provides detail in [the downloadable PDF syllabus on SBT webpage](https://www.securityblue.team/btl2) itself

If you already have a few (2-3) years experience in cybersecurity, you will find BTL2 a thorough but challenging bit of training. This is by no means entry-level, as there are some sections that take on an assumed measure of expertise, but for those willing to grind through the gauntlet, BTL2 is well worth the skills gained. 

As for value - personally I believe if you are able to have your employer or other party assist financially with this course, it is certainly worth it. 


## Malware Analysis
### My least favorite...

And by least favorite I mean personally, I am not great with code, and therefore analyzing malware is very daunting to me. Despite my "decade +" of experience, programming/coding has not been a focus, nor has it needed to be for my professional career (surprise, not all IT or cyber jobs need coding, even though its a *really* great skill to have). Malware Analysis as a whole fascinates me, but in practice, makes my brain hurt because of how technical it gets. This domain is *extremely* technical, as you dive into the skills to understand the behavior and intention behind different pieces of software.

This domain has an optional section that teaches you how to build your own malware analysis lab at home. This is not required for the exam (you are provided everything you need to take/pass the exam in the exam environment), but if you want extra practice, it is a great setup. 

As someone who has spent most of their professional career avoiding clicking random links in emails, it is really neat to actually feel confident detonating the malware and actually being able to analyze *and understand* what happens when this occurs. The malware analysis tools they cover really do a lot of heavy lifting in helping you understand what's happening, which came as a big relief to someone whose eyes sometimes glaze over when they see a full screen of code. 

Music to study to: Instrumental Progressive Rock/Metal
- [Intervals](https://open.spotify.com/artist/0xpJGyjbEzkWSNfcf2tcMl?si=HhzzM2n1RRWWhiXhspHzyw)
- [Plini](https://open.spotify.com/artist/3Gs10XJ4S4OEFrMRqZJcic?si=uUsyr-7SQPOQ8wHJwg5feA)


## Threat Hunting
### My most favorite...

I'll be honest, this was the main reason I wanted to take BTL2. When I discovered "Threat Hunting" was a thing back in 2018, I became obsessed with one day being able to answer the question "What do you do for work?" with "Oh, I'm a Threat Hunter" - I mean, how cool does that sound? Easily top 3 job titles in Cybersecurity in my opinion. 

Anyways, this is the longest domain of the bunch - but really in-depth and worthwhile. It is also *extremely* technical like Malware Analysis, as it teaches you to navigate through systems and logs to retrieve artifacts you want to look for. But that's the key - sometimes you don't know where to start - that's where this domain excells. It teaches you the who, what, when, where, why, and how of extracting artifacts to aid in your investigations for threats plaguing the environment. The training not only teaches you the technical skill to do this, but also helps you build a mindset and baseline to approach a threat hunt, and this is key for the exam and real-world application. You will not always be provided with a perfect scope, environment, or tooling, so when you're asked to "find out where evil lives" or "what did the threat do" in an environment, you will already have the mindset needed to take the challenge head on, and more importantly, produce tangible results (i.e. a report) for any higher ups that need answers. 

Music to study to: Synthwave/Retrowave/Outrun
- [Kung Fury OST](https://open.spotify.com/album/1LvYQkoLEtTOqpuoc4X3IX?si=hZ3POzJjSbqfVD0mxKCDVg)
- [Mitch Murder](https://open.spotify.com/album/1ln0cipwqohGR62gIBgpBM?si=UfLqpjwjT_euD_6q55NbvQ)
- [Synthwave for Driving](https://open.spotify.com/playlist/5xQxOMOVkWNXQAtwWP8XfC?si=51e5b5b663114bec)


## Advanced SIEM
### It's not just for analysis...

You're in the IT/Cybersecurity space - you might only view a SIEM as simply the tool a SOC uses to respond to security alerts. 
- But how do those alerts fire?
- Who creates the alerts?
- HOW are the alerts created, or even managed?
- Who else can use the data collected by a SIEM?
- How is a SIEM deployed in an environment that makes the most sense?

That's what this domain covers. BTL1 introduces you to the idea of a SIEM and teaches you the basics, BTL2 covers higher level uses of the SIEM including its architecture and how it can be used for threat hunting, as well as threat emulation, detection, and advanced log analysis. This goes beyond the simple SIEM alert triage, and teaches you to leverage other aspects of the SIEM to help you and other analysts on your team get to the data they need faster (dashboards anyone?).

This is the section where the more reps, the better. SBT's SIEM of choice here is Splunk (BTL1 covers it, BTL2 expands on it), so the more comfortable you are with it, the easier it will be for you to extract the data you want (and need) for the exam. 

Music to study to: Classical piano
- [Rousseau](https://open.spotify.com/playlist/31mVl7TDRsto0qwvUcXD8s?si=0506f74b47b1453f)
- [Kassia](https://open.spotify.com/artist/3m8qh3adp23dCoZBHZt5IH?si=vb05vpq8TpGPmX3l4ajSfA)


## Vulnerability Management
### Oh, you're secure? Prove it... 

This section is arguably the most applicable to most organizations. A lot of companies need to adhere to some type of compliance regulation. Almost all of these compliance regulations require an organization to perform vulnerability scanning to some degree to prove their systems are "secure" (enough). Understanding how and why these are necessary is an essential fundamental skill for anyone in cybersecurity. 

Being able to run, report on, and explain vulnerabilities to both technical and non-technical people within an organization is an extremely undervalued skill these days. Knowing your audience and the relevant facts they need to know regarding certain threats or incidents is crucial to an efficient cybersecurity program. BTL2 helps demystify this part, and teaches you how to communicate effectively. 

I have worked for Managed Security Service Providers (MSSP - a type of cybersecurity consulting company) for a large portion of my career and Vulnerability Management and Scanning is always at the top of the conversation between us (the MSSP) and the client (customer). This is a great proactive way for organizations to better understand and secure their environment. It's also usually one of the first things a threat actor completes during [Reconnaissance](https://attack.mitre.org/tactics/TA0043/). 

Music to study to: Funk/Jazz
- [Vulfpeck](https://open.spotify.com/artist/7pXu47GoqSYRajmBCjxdD6?si=fKDwXdGlTK2IiSCrmwr26w)
- [Cory Wong](https://open.spotify.com/artist/6xt9sJmmyYwWkJv8A6ssiU?si=xuDZqqfCSAmPVPz6KHOFJw)
- [Sylva](https://open.spotify.com/album/4CMBJalQcdxkisQvx8iJxJ?si=lHxPqIPOSzyYe2zsEVo12Q)
- [Anika Niles](https://open.spotify.com/artist/0IF3ewdvS7h9Wu3gDgV3fi?si=sQkKQdm2SlybUi_pWmtPAA)


## Exam 

It's 72 hours long. That's a long time, but you are provided a report template that guides you through the rough outline you can use to approach investigating and gathering evidence. I personally started in the afternoon to acclimate to the exam environment and scenario to do some initial investigating and note taking so I could sleep on it as a first pass. This also allowed my timing to have the final hours in the morning before lunch, which is when I'm usually able to focus best. 

My biggest tip for the exam - Recreate the labs you've already completed through the course within the exam environment. 
- What did that malware analysis tool help you understand? 
- How did you approach that threat hunt?
- What about how to retrieve that one type of log?
- Or use that vulnerability scanner?
Pretend your exam environment is the lab environments you've already been through and answer the same exact questions with your new data. The exam won't necessarily  need the answers it produces, but going through the motions again within the exam environment can help you think of things you might not have otherwise. You'll be surprised how much of what you've learned from the labs that will help you here. (I mean, that's the point of the labs right?)

Also, breathe. You have time to do everything you need to. Whenever you're about to step away from the exam to take a break to eat, sleep, etc - write down notes of what questions you still need to find answers for. 
- "I need this, how do I find that?"
- "I already have this, is this relevant?"
- "Can I use this info somewhere else?" 
When you come back, you'll be refreshed and have stepping stones to your next tasks ready to go. 

Lastly, take a walk when you're stuck. Still write down the note of what you need before you walk away, but getting out of the house and moving in the outside air works *tremendously* for unsticking your brain. 

Since the exam is a written report, results are not instant like BTL1 as it is hand graded by their lead trainer. This can cause some extended delays in receiving your  grade. Personally, my wait time was 39 business days from submitting the exam to receiving the results, but on the SBT Discord there have been others claiming longer. SBT is aware of this sore spot and are dedicated to improving turnaround time some time in the future. The feedback they provide for your exam results are incredibly detailed, even for a passing grade. I knew I missed some details when I submitted my report, and the feedback reflected where I could have improved, so it was very refreshing to see the committment to detail. 


## Final Thoughts

To me, BTL2 was 100% worth it. I continue to lean on what I learned and experienced throughout the course in my day-to-day as a Detection and Response Engineer. Some of the topics I've even brought in as project for my team to explore and the results have been well received. For others, I say if your employer or other party can provide some financial support for it, then it is a no brainer to pursue, especially those wanting to push deeper into Security Operations or Incident Response. 