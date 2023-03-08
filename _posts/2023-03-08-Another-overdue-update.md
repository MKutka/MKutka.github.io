---
layout: post
title: Another Long Overdue Update!
subtitle: More Updates!
cover-img: /assets/img/2023-03-08-another-overdue-update/Cool-Wallpapers.jpg
thumbnail-img: /assets/img/2023-03-08-another-overdue-update/untitled.png
share-img: /assets/img/2023-03-08-another-overdue-update/untitled.png
tags: [Life, Networking]
---

Well i'm back and it's been another hot minute since my last update. Once again that's on me... So let's try this again for a 3rd time... 


## Where I've Been!

 **New Addition to the Family**

 On November 3rd 2022 my wife and I welcomed our beautiful, healthy baby girl into the world! London and Mom are doing very well and it's hard to believe she's already 4 months old! 

<img src="{{ 'assets/img/2023-03-08-another-overdue-update/Family.png' | relative_url }}" 
     width="400"
     alt="London" 
     class="center"/>


**PCNSA: Palo Alto Networks Security Administrator**

While out on Paternity leave I was able to somehow by the grace of god sneak in some studying for the PCNSA and pass the exam. I leveraged the CBTNuggets course by Keith Barker along with the content provider from Palo Alto through their Beacon platform. Definitely a great resource and plan to use it on future products we'll be implementing!

<img src="{{ 'assets/img/2023-03-08-another-overdue-update/PCNSA.png' | relative_url }}" 
     width="400"
     alt="PCNSA" 
     class="center"/>


## Where I'm At!

**Merakify and Automate all the things!**

At my employer we had been struggling with consistency and config drift and troubleshooting has always been a chore due to different platforms. Meraki for WiFi, DNA Center for LAN, SDWAN for... well WAN! All of these solutions have different controllers and from a troubleshooting perspective jumping from one into another is a pain. 

At Cisco Live 2022 Cisco announced the ability to monitor and eventually manage the Catalyst switch line from the Meraki Dashboard and with this an [article](https://newsroom.cisco.com/c/r/newsroom/en/us/a/y2022/m08/cisco-helps-starbucks-brew-up-efficiency-through-network-automation.html?dtid=osolin001080) about how Starbucks had reduced its store network deployment from days to mins and hours "Wow... wouldn't that be nice!"

This is when we decided to make a change, since COVID and the Hybrid work revolution our offices have turned into glorified internet cafe's where people come and go. It made sense to simplify our deployment and automate as much of it as possible. We met with our Cisco Meraki rep and described what we wanted to do and honed in on a full Meraki stack that would be affordable and acceptable for almost all of our offices (places like HQ are special snowflakes).

From there a colleague and I started working on an Full Onboarding and Offboarding automation script which will do the following:

- Create Subnets and DHCP Reservations within Infoblox
- Create Meraki Network and Assign devices to Network
- Create Location and Add Network devices into ISE
- Configure all ports with a consistent topology for all offices
- Configure SSID's for WiFi
- Configure AutoVPN tunnels dependent on Geolocation

We've finalized the scripts and have reduced our traditional deployment from 2-3 days to 10-25 mins from tests on our mock office. We'll be deploying our first production office with this solution in the coming weeks and will hopefully be able to provide a redacted version of our scripts to github to help others!

**Getting SASE!**

Another project that i'll be working on is evaluating and implementing the latest buzz word hotness into our environment, SASE! This is an acronym for Secure Access Service Edge and i'll be working with our InfoSec team to evaluate solutions to secure our workforce. I'm planning for this to be a blog series with an overview of SASE/ZTNA as the first post and then a deep dive into the vendors we're evaluating. 

Keep an eye out for these posts over the next weeks/months!

## Where I'm Going!

**Cisco Live 2023!**

I had such a great time last year at Cisco Live meeting people, learning about solutions, and taking in everything that I don't think it's a surprise I want to continue to go every year. By a stroke of good luck I will be able to! 

Through attending CL I was able to get my org into Early Preview for ThousandEyes WAN Insights and have been engaged with and providing customer feedback on the solution. We saw some pretty awesome success from the solution, so much so that I was asked to speak at Cisco Live 2023 as a Customer Testimonial for the product! From first time attendee to first time speaker in 1 year! Talk about a glow up! Come check out my session if you're going to be attending this year!

<img src="{{ 'assets/img/2023-03-08-another-overdue-update/CiscoLive_Session.png' | relative_url }}" 
     width="700"
     alt="Who's that guy!?!" 
     class="center"/>

**Cert Goals for 2023**

In my last post I was looking at DevNet Associate which was put on the backburner for PCNSA. I'm back on the DevNet train and hoping to take the Exam before May, then onto ENCOR for CCNP!

## Closing: Thank you!

I tried to keep this one shorter than my last post, but thanks for sticking with it! Keep an eye out for my next blog post where I break down SASE and subsequent posts which will explore different vendors and their offerings!

Thanks for stopping by and may your weeks be outage free!




