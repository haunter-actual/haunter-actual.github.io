---
title: "OffSec Offensive Security Certified Professional (OSCP+) - My Journey to Certification"
date: 2026-01-19 12:00:00 -0000
categories: [Certification, OSCP]
tags: [OffSec, OSCP, OSCP+]
---

<img alt='Offsec OSCP Logo' src='/assets/img/oscp.svg' style='width:25%;display:block;margin: 0 auto;'/>


How can does one properly bookend a journey that has taken several hundreds (perhaps even over a thousand) hours of your life? The study sessions starting at 3am, the late nights ending often when your spouse is about to wake up for work, and turning down social calls with friends and family over and over. I took and passed the OSCP+ exam on my third attempt earlier this month. I'm writing this in case there is someone out there that is about to start their own path to the OSCP and may benefit from my experience.

<iframe
  src="https://credentials.offsec.com/embed/fea2ee2f-058e-4192-97a7-6130e7cd78ef"
  width="800"
  height="600"
  frameborder="0"
  allowfullscreen>
</iframe>

# tl;dr

* join and participate in the OffSec community Discord from the start of your journey. You'll likely see me there. Be respectful, make friends, and ask questions: https://discord.com/invite/offsec
*  Read a few posts from others that have passed the exam. Note their study tips to help develop your own plan of attack. Here's a link to Reddit posts from the last year, restricting results to the current exam format, for potential reference: https://www.reddit.com/r/oscp/search/?q=passed&sort=relevance&restrict_sr=on&t=year
* The OSCP is not a beginner IT certification, it is a beginner *pentesting* certification, make sure you have some general experience before attempting it. Check my suggested path below if you are new to offensive security 
* Start making writeups for every CTF machine you complete. This will reinforce your methodology as you develop it as well as well as ensure you master what you've learned. Writing about new concepts has been proven to be a very effective method to learn and retain new information. 
* The course material (PEN-200) is great, but can only be useful to you with proper notes and practice. Use the challenge labs wisely and take them after completing the material to hone your methodology and revise it as-needed.
* AVOID BURNOUT / SPEND TIME RELAXING AND BEING WITH THOSE YOU LOVE
	* at the end of the day, it's just a cert. Remember to make time to enjoy life and spend time with those you care about.

# When is the Right Time to enroll in the OSCP course (PEN-200)?

## Join the Community & Get a Feel for the Experience

Join the official OffSec discord to be apart of the community: https://discord.com/invite/offsec

You can lurk and ask questions as you navigate your studies. The people here are incredibly smart, experienced, and helpful. Just remember to be respectful and at least be will to show what efforts you've taken when asking for help.

Another helpful tactic is to read posts from those that have passed the exam. You'll seem some students that have taken the exam 6 times over years of study, and others that are in their mid-teenage years that passed on their first attempt. Reading their stories can provide insight that may be close to your situation. 

**Note: the below reddit search is limited to the last year as the current exam format went live just a bit over a year ago. If you search for older posts you'll get them from folks that passed taking the older exam format**

https://www.reddit.com/r/oscp/search/?q=passed&sort=relevance&restrict_sr=on&t=year

## What is your I.T. / Cybersecurity Experience?

A somewhat common misconception is that the OSCP is an entry-level certification; that pursuing and achieving it is feasible for anyone wanting to break into I.T. and immediately get a sexy hacking job. *This is generally incorrect.*

The OSCP is an **entry-level pentesting certification**. It is NOT an **entry-level I.T. certification**, let alone an **entry-level cybersecurity certification**. The typical* suggested pipeline to get into pentesting/red teaming is:

General I.T. -> Specialized I.T. (System/Network Administration) -> General Cybersecurity -> Specialized Cybersecurity (penetration testing in this case)

Combinations of experience, education, certifications, and human networking can impact this.

*There are always exceptions. There are some people that have or will be able to jump straight into a security job but the current job market meta makes it even less likely.

## My Background

When I decided to study for the OSCP I had been in I.T. for years. I started with web design learning HTML/CSS, then QA and basic python programming, followed by PHP programming and Linux administration, and finally tier 3 support work involving network and Windows admin work. While working that last job I attended Western Governor's University (WGU) and got my B.S. in Cybersecurity & Information Insurance (CSIA). I then was able to pivot into security, and also get my M.S. CSIA as well.

My original career goal was to specialize in **blue team**, DFIR specifically. Life happened and that blue team dream died (BIG SAD), and I focused on **red team** instead. While I had broad knowledge and skills, my baseline technical skills were lacking, especially in respect to Linux exposure and web applications. 

Here's the path I went on after a ton of research to prep for the OSCP.
## A Suggested Path

You can reference my route below. I'd skip #1 through #4 if you have pentesting/CTF experience. Otherwise, I'd suggest the relevant portions, though completing them to 100% isn't necessary (I didn't, I moved on from each once I felt comfortable enough with the concepts being taught). 

### No Prior Pentesting or CTF Experience, Start Here:

1. OverTheWire
	1. https://overthewire.org/wargames/bandit/
	2.  An excellent gamified CTF to learning Linux terminal and bash commands. Skip this if you've been using Linux and are confident in your abilities with the OS.
2. UnderTheWire
	1. https://underthewire.tech/wargames
	2. A Windows/Powershell version of the above CTF. I skipped this as my Windows skills were strong, but include this if you are short on exposure to Powershell.
3. TryHackMe - https://tryhackme.com/
	1. https://tryhackme.com/path/outline/jrpenetrationtester
	2. THM is a great resource that holds your hand in exploring basic pentesting concepts. Skip this if you've done some CTFs already, otherwise include THM if you are lacking in technical experience and would benefit from a structured lesson system.
4. eJPT 
	1. https://ine.com/security/certifications/ejpt-certification
	2. Baby's first pentesting cert. The course I took was prior to eLearnSecurity migrating to their new learning platform. I really liked the course and the exam. If the current version is similar, this would be a great cost-effective way to gauge if you are ready for the OSCP course.

### Prior Pentesting or CTF Experience or Completed the Above Prerequisites, Start Here:

1. PEN-200
	1. https://www.offsec.com/products/learn-one/
	2.  I purchased a Learn One (L1) subscription **twice** (*RIP my fucking checking account*)*. The L1 includes 1 full year access to the course material, proving grounds labs, and the challenge labs. It also includes 2(!) exam attempts. L1 is ideal if you can afford it and aren't starting off technically savvy, such as myself when I started. 
	3. *I purchased L1 twice due to burnout + imposter syndrome. More on that later.*
	4. The course is great, and if you meet the prerequisites, it's straightforward to get through. Make sure to compile your notes concisely and practice your knowledge in the module labs.
2. PEN-200 Challenge Labs
	1. You may get impatient but leave the challenge labs for after you've completed the course in its entirety. The challenge labs, A/B/C in particular, are great practice for the exam so you'll want to use these to measure your knowledge and notes at the culmination of your studies with the official material.
	2. IMPORTANT: start making writeups for each machine you complete from here on forwards. The writeups should include each enumeration, foothold, privesc, lateral, root, and post-exploitation steps (along with screenshots). This is important as it will directly help formulate your methodology and create a workflow for reporting and documentation that will be needed. *Remember, if you don't submit a passing report, you can't get the certification!*
3. LainKusunagi / TJNull Practice Systems Lists
	1. https://docs.google.com/spreadsheets/d/18weuz_Eeynr6sXFQ87Cd5F0slOj9Z6rt/edit?rtpof=true&sd=true&gid=487240997#gid=487240997
	2. https://docs.google.com/spreadsheets/u/1/d/1dwSMIAPIam0PuRBkCiDI88pU3yzrqqHkDtBngUHNCw8/htmlview
	3. If you complete the PEN-200 course and have time before your exam, or you need extra practice after an attempt, these curated lists are great resources of machines to practice on that are 'OSCP-like'. 
	4. I compiled both lists into a singular study plan for myself, ensuring that I made writeups for each box and notated lessons learned for each system that had something unique I hadn't seen before: https://haunter-actual.github.io/posts/OffSec-OSCP-Study-Progress/
4. HackTheBox Penetration Tester Job Path
	1. https://academy.hackthebox.com/path/preview/penetration-tester
	2. In my experience, the quality of content from HTB academy is comparable to the PEN-200 course material. Much of the path is redundant but if you feel like you need additional material and practice, I'd suggest doing the AD modules, privEsc modules, and attacking common services.

# The Exam

As mentioned earlier, scheduling the exam early on can force you to make a plan and stick with it to study. My exam experiences are detailed below:

### Attempt 1
Exam Format: Old Format
Datetime: 10/31/2024 - 10 PM PST 
Total Exam Time: 24 hours
Score: 20 PTS (+10 Bonus PTS)
Status: Fail

I might have been the actual last person taking the old exam format (no assumed breach AD, no partial points AD, +10 bonus points for completing 80% of all learning modules + 30 lab proofs from the challenge labs). The current exam format switchover was set to 11/1/2024 and actually occurred 2 hours into my exam lol 

Initially, I had purchased a Learn One subscription and then a lab extension to have enough time to qualify for the bonus points. Additionally, my exam was originally scheduled the attempt for mid-August, but then pushed it back to October to the last available date and time slot due to nerves. 

That didn't help :O  I did abysmally. Starting the exam so late in the day was a bad idea as I felt compelled to stay away through my normal sleeping ours. I didn't take any breaks and slammed my head against the wall for 24 hours, only having achieved a foothold on two standalone systems. This really upset me as I was sure I would nail the AD set at the very least, but I didn't even dent it.

### Attempt 2
Exam Format: Current Format
Datetime: 4/19/2025 - 11 AM PST 
Total Exam Time: 24 hours
Score: 50 PTS
Status: Fail

I learned my lesson and started this exam earlier in the day. Things started off smoother and I was able to get SYSTEM on two of the AD machines and fully rooted a standalone box in the first 12 hours. Unfortunately, upon reflection I realize I should have been taking more breaks but I kept persisting after making progress. It wasn't until hour 23 that I finally took a break and found a foothold on that 2nd standalone that was super obvious. If I had rested earlier I would have likely had enough time to pwn the box and move on to either the last standalone or wrap up the AD set.

### Attempt 3
Exam Format: Current Format
Datetime: 1/10/26 - 9 AM PST
Total Exam Time: 13 hours
Score: 90 PTS
Status: Pass

The time between this final attempt and the previous was filled with gaps (sometime months long) where I took breaks from studying. However, I had structured my study time much more efficiently. I made my own study tracker based on a compilation of both TJNull's and LainKusunag's OSCP-like practice machines:

https://haunter-actual.github.io/posts/OffSec-OSCP-Study-Progress/

I grouped the systems by Linux, Windows, or AD and by difficulty. For each system I made a writeup, noted the foothold, privesc vectors, and any other lesson learned in a summary statement. Getting this routine in place was the most influential factor in upping my skill level to pass the exam.

After doing a couple dozens of practice machines, I scheduled the exam on a whim after not having studied for about two months due to the holidays. This attempt was to be just to gauge my progress to see how far I'd come. As it turned out, it was quite far!

I started with the AD set and had pwned the first box in an hour. I took a break and tried to get the 2nd machine, but switched targets after about an hour to a standalone machine. I found a vulnerability and got a foothold, took a break, and got root shortly after.

I took another break and revisited AD. I found something I had overlooked earlier and was able to get a foothold on host #2. Fumbled around a bit longer than I should have before taking another break and switching back to standalone #2. I rooted this one pretty quickly and set myself to hammer back at the AD set after another break.

Redoing my enum from square one helped me focus on what I overlooked again. I found what I needed and got SYSTEM on AD #2. At this point I was invigorated to finish AD, but I forced myself to step away and have dinner. I came back and got DC in another hour. I had enough points to pass and that was a HUGE relief. 

I gave the last standalone the old college try and got a foothold after awhile, but with 90 pts I was content and wanted to ensure I had everything I needed for the report. I went back and triple checked I had all the needed screenshots, copies of my commands, links to scripts/payloads, and had the correct proof details. 

Just barely above 13 hours had passed when I submitted to complete my exam. I celebrated briefly with my wife before going to bed. I spent the majority of the next day organizing and proofing my report before submitting. I received my 'Passed' status on the Portal the next day :)

Sysreptor is great for reporting, by the way: https://docs.sysreptor.com/


## Lessons Learned from Studying & the Exams

* Pick a date for your exam and get it scheduled. Don't put it off indefinitely. Having a target and some pressure can be a great way to force yourself to make a study plan and stick to it
* Practice making writeups and exporting them in the format you'll be using for the exam report. Many people don't actually practice report writing until they are in the exam, and you may run into technical troubles or lack the muscle memory to capture your steps properly and document via screenshots
* Don't cram before an exam and get plenty of rest the night before. Also, schedule the exam so it aligns with your normal day/night schedule. Fighting exam fatigue while also drinking gallons of caffeine will just make you fail energetically 
* Take many breaks during the exam, even if you aren't actively stuck. Pomodoro timers are great for this. Just stepping away even just 5 minutes can reset your mind to attack again. Hell, stepping away to pet your cat/dog or hug your family can be a great booster!
# A Word on Study / Life Balance

Burnout is a thing. I spent a long, long time going through my Bachelor's program, Master's program, and getting here. That was years of studying that took me away from my family and close friends, and also neglecting my personal health. In I.T. and security there is *always going to be another cert*. ALWAYS. It's the nature of the industry and many of us have that need to constantly learn more and *be more*.

One thing I wish I had done much better was prioritizing my time in a much more balanced manner. My loved and friends certainly paid a price I thought I was paying on my own by focusing so hard. Please be better and remember to take weekends off to relax and make memories while you pursue your goal :)

# What's Next

Now that I'm ready for the next step, I'll be specializing further into red team certifications.

First though, I'll target the CISSP. WGU's cybersecurity programs seemed tailor made to culminate in the CISSP, with the Bachelor's program resulting in the SSCP and CCSP certs when I attended. It would have made so much sense for the Master's program to include the CISSP (and I think that was the plan) but they ended up included EC-Council's CEH and CHFI (meh...).

Once that's done I'll target Zero-Point Security's Certified Red Team Operator (CRTO) and Certified Red Team Lead (CRTL)
* https://www.zeropointsecurity.co.uk/course/red-team-ops
* https://www.zeropointsecurity.co.uk/course/red-team-ops-ii

After that, I'll try OffSec's Experienced Penetration Tester (OSEP) or HackTheBox's Certified Active Directory Pentesting Expert (CAPE) if I have the energy and/or funds.

# Good Luck on Your Journey!

That's my OSCP story. Thank you for reading, and I look forward to reading yours soon. Please reach out if you have questions or want to share with me.

* Discord: @teknoir-haunter
* Reddit: OPFOR-HAUNTER
* Email: haunter-actual@outlook.com

