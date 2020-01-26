---
title: "🏗 for ZCash"
path: "/buidling-for-zcash"
date: "2020-01-27"
coverImage: "../images/zcash-ssd-better.png"
author: "Prastut"
excerpt: "Journey so far in building tools to enable an open and trustworthy financial system that doesn’t put our privacy and freedom at risk."
tags: ["zcash", "privacy"]
---

This blog post documents _the_ why and how BUIDL Labs went about building the ZCash Service Status Dashboard with the support of the ZCash Foundation by answering the following questions:

1. How did we come across the ZCash Project?
2. What inspired us to build for the ZCash Project?
3. How did we find the niche space in which we can contribute to the community?
4. How did we go about getting funds for the value we wanted to create for the community?
5. What processes we followed while building to ensure accountability, clarity and alignment towards the outcome?
6. What are our long term plans to contribute to the community?

## How did we come across the ZCash Project?

Since early 2019, BUIDL Labs team has been deep diving into the crypto rabbit hole after being inspired by the audacious vision of the pioneers, teams and projects in this industry. Since our team believes in learning by collaboration, we were itching to start contributing our engineering and growth bandwidth to some of these teams and that itch led our small team to the ZCash project.

## What inspired us to build for the ZCash Project?

We were inspired by ZCash Project's core goal of building an open and trustworthy financial system that doesn’t put our privacy and freedom at risk. In line with the goal, the teams working to steward the mission have built out ZCash - a privacy-protecting, digital currency built on the science of zero knowledge proofs. Like other cryptocurrency networks (e.g. Bitcoin or Ethereum), Zcash allows anyone with a computer and an Internet connection to send and receive scarce tokens that can be used like cash on the Internet.

The magic of ZCash technology lies in it's strong privacy guarantee where shielded transactions in Zcash can be fully encrypted on the blockchain, yet still be verified as valid under the network’s consensus rules by using zk-SNARK proofs.

This example illustrates why financial privacy is important and what led to the transition from an itch to a desire to contribute:

> Bitcoin has been around for almost a decade, and by now many people have realized that it is [not nearly as private or anonymous](https://coincenter.org/entry/how-anonymous-is-bitcoin) as many initially thought. That can be a good thing when it comes to [catching criminals](https://coincenter.org/entry/how-can-law-enforcement-leverage-the-blockchain-in-investigations), but it can also be a bad thing for innocent users. In fact, Bitcoin’s current specifications make it almost impossible for an unsophisticated innocent user to have any privacy. Here’s a simple example. Most people use bitcoin by sharing a payment address that looks something like this: 1CPwNACt62wts2yGbz1vUuqeGD58SzzeAL

> Maybe that address belongs to a bartender. To accept bitcoin for cocktails the bartender puts that address on a poster behind the bar in the form of a QR code so it would look something like this (courtesy of [Room77 in Berlin](http://www.pri.org/stories/2013-10-04/if-you-wanna-buy-beer-berlin-bring-your-bitcoins)):![http://coincenter.org/files/2016-12/room77-small.png](http://coincenter.org/files/2016-12/room77-small.png)

> Patrons at the bar can take a picture of that code with their smartphone and use a bitcoin wallet app to pay that address for their drinks. Trouble is, anyone can look that address up in the Bitcoin blockchain and see every incoming transaction and the total amount of bitcoin sitting in that address. If we look up that information, then we have at least some idea of how rich the bartender is (good information for a would-be robber), and how successful the bar has been (good information for the competing bar next-door). Also, if we sat next to someone while they took a picture of the payment code with their phone, then we might have a good idea of how rich the customer next to us is as well by identifying the most recent incoming transaction for the bartender’s address and looking up the balance of the sending address, the customer’s address.

To put the above example in perspective, just imagine the iota of privacy you have when you use centralised systems of payments. 😰

We were also inspired by the people working on the ZCash project. Recommended playlist to get a sense of the state of mind of the pioneers building this crucial technology:

`youtube: aR-r6q0d6BE`
`youtube: qRypm80AOmM`

Impressed and in awe of the vision and the problem the project is solving, we wanted to start contributing.

In this midst of deep diving, we came across [ZCash Foundation Grants Platform](https://grants.zfnd.org/) - where the Zcash Foundation funds Zcash development, research, and other ecosystem projects to further advance the mission of the ZCash project. Our small team was stoked hearing that there were real incentives at play if we can add value. Now the

## How did we find the niche space in which we can contribute to the community?

First we did a breadth first search of the areas that needed improvement. We came across the

As we were deep diving into the community, we noticed there didn't exist a single source of truth for various external services that exist in the ZCash ecosystem leading to information asymmetry for the ZCash users. For eg: different block explorers reporting different state of the ZCash blockchain.

Donning our hats of problem solvers, we wanted to first confirm whether the need existed by communicating our intent to the ZCash Foundation Team for which we connected with Sonya Mann, who runs communications at ZCash Foundation. After coming to a consensus, that the problem we are thinking about actually exists, we went about doing an exhaustive research to figure out what all different services that existed in the ZCash ecosystem and how to go about creating a standardised source of truth.

The outcome of the above research process yielded ZCash Ongoing Services Exhaustive List - which covered all the different services that we were able to find and organise them into buckets  [https://docs.google.com/spreadsheets/d/1ESq4EA4dQ9UB3sUNiBwLEXm26YhUMheXbzr-ednFI0M/edit#gid=0](https://docs.google.com/spreadsheets/d/1ESq4EA4dQ9UB3sUNiBwLEXm26YhUMheXbzr-ednFI0M/edit#gid=0)

We shared this sheet in ZCash Community Chat

We will do it by:

- Creating a health check monitoring service for different categories of external services that exist in the ZCash ecosystem.
  - That also involves building support for monitoring category specific nuances.
- Creating a user friendly dashboard to view as a single source of truth.

## How did we go about getting funds for the value we wanted to create for the community?

## What processes we followed while building to ensure accountability, clarity and alignment towards the outcome?

## What are our long term plans to contribute to the community?

why we are building the service status dashboard and our long term vision of the project.
