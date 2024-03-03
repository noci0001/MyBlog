---
title: BCX SURVIVAL GUIDE | 5 tips
author: Samuel Nocita
date: 2024-03-01
tags: ["post", "featured"]
image: /assets/blog/article-1.jpg
imageAlt:  meme
description: 5 tips to keep in mind when you are about to face your first hackathon
---

BCX - Bosch Connected Experience Hackathon - ended a few days ago. In these 2 days I compiled a list of considerations and anecdotes coming from me and my peers that we thought you, the reader and future hacker, could find insightful.<br>
GOAL: help you run your next marathon like a bosch!


<div class="chapter">
<p>1) CHOOSE HOW FAR YOU WANT BE OUTSIDE OF YOUR COMFORT ZONE</p>
</div>
During the hackathlon you will have to design and present an innovative solution while working inside a team of around 4 other people. Coming with friends is a super valid option, but we all felt like being open to collaborate with people we didn’t know. Ultimately groups created naturally. I would encourage you to try to push youself outside of your comfort zone because that’s where there is opportunity for growth. However, what makes one person uncomfortable can vary a lot. For instance, I tend to be ambivert so the factor of meeting new people was not a challenge, which is why I chose to work with people I mostly knew focusing on building and improving that rapport. My friend Adam knew that being in the team with me would have been a comfortable safe option so he went for a team of totally new people that I had the chance to meet only at the end of the hackathon.
Amazing people, we had a drink in the last day of the BCX, cheers to them!

Being out of your comfort zone means that the amount of stress you will be subjected to will increase as the hours go by. Stress that is alimented by the clock ticking, the code not running, the constant chattering of the people around you. Also, let’s not forget that the tech we are using can be as faulty as we are.

<div style="padding: 2.5rem; display:grid; grid-template-columns: 1fr 1fr;
">
<img width={{"800px"}} src={{"/assets/blog/meme1.jpg"}}></img>
<p>*RIP to my work laptop that passed away a few hours into the hackathon. For some reason, the entire GNOME desktop environment was removed after I took a break from working with the kuksa-client to establish a connection with the VR headset.</p>
</div>


<div class="chapter">
2) DO NOT UNDERESTIMATE THE MARATHON ASPECT OF THE HACKATHON
</div>

The 48hours window that you have from start until the end of the hackathon is time that must be carefully utilized to work, take breaks, eat and hydrate. Nevertheless, it’s supposed to be a marathon and like any marathon you can’t just start sprinting. This is a personal takeaway from this experience. I wanted to write code as soon as possible no matter what and so I focused so intensely without taking an actual break to rest my mind which slowed me down at the end of the first day. 
Also, I had a problem in the expectations of what I thought our code had to be like, which slides perfectly into the next point:
<div class="chapter">
3) REMEMBER THAT PROGRAMMING MEANS ALSO DEBUGGING AND AN HACKATHON IS NOT ONLY AN OPPORTUNITY FOR YOU TO PRACTICE PROBLEM-SOLVING BUT ALSO FOR THE TECHNOLOGIES PROVIDED BY THE HACK COACHES TO BE TESTED AND REVIEWED</div>

When you come up with an amazing idea to code, code is all you want to get to do. However, the reality is way different: the sooner you can adjust your expectations the easier it’s going to be to not end up disappointed in something you don’t have the control over. 
For instance, my team and I eventually settled for the creation of what we called an 
Autonomous Driving Parking System
where you can abandon your vehicle and from a mobile app you can order it to go park itself. If the car does not succeed it sends a message back to the owner which can either call a remote valet to park the car through vr goggles or they themselves can park the car using vr goggles all while they are in the queue for their coffee. In order to achieve our vision we divided the project in three components: Mobile Application in Swift, Autonomous Driving module provided by the Bosch Mobility Challenge team and SDV-LINK VR sandbox that utilizes Kuksa.val and a scene created Unity to simulate a city map where you can drive your car in vr using the Meta Quest 2. 
90% of our hackathon focused entirely on getting those tools ready.

Some of my peers were happy to contribute to this article, this was Andor’s take about this aspect of the hackathon experience:

“I think overall I wrote less than 100 lines of code and in the end we didn’t use any code of mine. [\…] In the end we just focused on the presentation.”

By the way, Andor’s team was one of the 5 finalists, so congrats!   
<div class="chapter">
4) EMBRACE COLLABORATION AND FLEXIBILITY</div>

Collaboration is key to success and each team member brings a unique perspective and set of skills to the table, making it essential to at least listen to and consider their thoughts. 
For example, I thought the Autonomous Driving Parking System idea me and my teammate came up with was very exciting, but when I heard my other teammate proposal it was clear to me that hers was much more simple and grounded in reality so I knew it had way more chances to win. I chose to support it but ultimately the team divided in half because both ideas were so enticing to us. Me and my peers knew that a VR driving school where you could practice parking is a way safe and cool concept to pitch, but decided to go for our initial idea because we cared more about having fun than choosing something (also fun) just because it has more chances to win. Embrace collaboration and flexibility, but ultimately there is no shame in parting ways if you truly care about something. After splitting we still kept checking on each other and we all got to work creating what we wanted.

<div class="chapter">
5) FIND BUGS, CREATE ISSUES AND PULL REQUESTS
</div>
Finding bugs, creating issues, and submitting pull requests are integral parts of the hackathon experience, representing opportunities for learning, growth, and collaboration. I was personally quite excited when I realized what the bug was about and fixing it was of course such a tasty moment after so many trials gone wrong. For instance, I had been trying to compile a tool to maneuver the vehicle in vr using Kuksa Client and COVESA VSS (Vehicle Signal Specification) and I kept getting a dependency installation error which was caused by the listing of unnecessary dependencies with pip. So I worked with the software engineer of the team that wrote the program to fix it. 

And just like that… we are close to run the pr..

NOPE, “You can run this program only on windows” he said while I was holding my linux laptop.

Here we go with another problem.. how do we get a windows machine out of thin air?
(We eventually were lucky and Alex had a windows laptop that we could use to continue working.)

I hope this article was somewhat useful and I wish you good luck for your next hackathon, make sure to have fun, meet people and think BIG!

A big thank you to Thomas Spreckley for reviewing, to the 42 Wolfsburg students that helped me by contributing to this article and last but not least thank you to Daniel Pisanu for giving me the encouragement and opportunity to talk about my experience at BCX  
