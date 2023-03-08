---
layout: post
title: We're getting SASE!!
subtitle: What is SASE/ZTNA??
cover-img: /assets/img/2023-03-10-getting-sase/cyber.jpg
thumbnail-img: /assets/img/2023-03-10-getting-sase/sase.jpg
share-img: /assets/img/2023-03-10-getting-sase/sase.jpg
tags: [Cloud, Networking, Security, SASE, ZTNA]
---

As cloud adoption accelerates, traditional network and security architectures are becoming increasingly outdated. The pandemic accelerated the trend toward remote work and the use of cloud applications, which has further exposed the weaknesses of legacy networking and security architectures. This has led to the emergence of two new network and security concepts, SASE and ZTNA. On an upcoming project I will be working directly with our InfoSec team at my employer to evaluate and select a SASE/ZTNA solution to help connect and secure our remote workforce.

In this blog post i'll be describing these two concepts and how they are being applied to organizations new architecture across the globe! In subsequent posts i'll be looking at specific vendors who are in the SASE/ZTNA space and discussing what I think they do well or could work on. 

Let's dive in!

## What is SASE?

SASE, or Secure Access Service Edge, is a network architecture that combines network and security functions into a single, cloud-native service. SASE consolidates multiple network and security services, such as SD-WAN, VPN, firewall, and secure web gateway, into a single cloud-based platform. By doing so, SASE simplifies network and security management, reduces the need for hardware, and provides consistent security policies across all locations and devices.

One of the key benefits of SASE is its ability to provide secure access to applications regardless of the user's location or device! That's the golden ticket in my opinion! With SASE, users can access cloud applications and data securely, without needing to connect to a corporate network. This is particularly important for remote workers who need to access applications and data from different locations and devices, but without the need to expose the application to the public internet.

## You mentioned ZTNA? What's that?

ZTNA, or Zero Trust Network Access, is a security model that assumes that all network traffic, whether from inside or outside the network, could be malicious. Never trust, always verify is the name of the game and ZTNA does just that! ZTNA uses a least-privilege access approach, which means users only have access to the resources they need to perform their job. This reduces the attack surface and limits the potential of a security breach.

ZTNA uses a software-defined approach to secure access to applications and data. Unlike traditional network security models that rely on a perimeter-edge defensesm ZTNA establishes secure connections between users and resources regardless of their location or device.

Like SASE, ZTNA has one key benefit, its ability to provide granular access control. Administrators can control access to applications and data based on user identity, device posture, and other factors. This means that users only have access to the resources they need to perform their job, which reduces the risk of a security breach. This adds a layer of complexity however as adminsitrators needs to understand the internal applications of their organization and the roles and responsibilities that each group in the organization performs. In order to have an successful deployment I suspect planning and requirement gathering is key and could save you a lot of headaches.

## So do I need both of these to be successful?

Depending on your organization size you might have Network Engineers and Security Engineers. These two groups likely have different roles and responsibilities, but complement and likely work very close to each other. Similiarly SASE and ZTNA are different concepts, but are complementary and often used together. SASE provides a network architecture that can support ZTNA, and ZTNA provides a security model that can be implemented within a SASE architecture. 

Together, they provide a solution to the challenges of cloud adoption and remote work.

## Who are the top players in this space?

SASE and ZTNA are relatively new concepts and technologies around these are constantly evolving. Many vendors are looking at their existing solutions and trying to determine what features can be added to be considered a SASE/ZTNA technologies. This can cause a lot of confusion when looking at solutions and create variablity in the market.

The current leaders may not be the ones leading the pack in 6 months time, but at time of this post the below who are considered to be the "Leaders".

* Akamai
* Cisco
* Cloudflare
* Netskope
* Palo Alto Networks
* Zscaler

Through my evaluation i'll be looking at a few of these vendors and reviewing their solutions objectively.

Thanks for stopping by and May your weeks be outage free!