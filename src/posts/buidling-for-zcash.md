---
title: "🏗 for ZCash"
description: "Journey so far in building tools to enable an open and trustworthy financial system that doesn’t put our privacy and freedom at risk."
path: "/buidling-for-zcash"
date: "2020-01-27"
coverImage: "../images/zcash-cover-image.png"
author: "Prastut"
excerpt: "Journey so far in building tools to enable an open and trustworthy financial system that doesn’t put our privacy and freedom at risk."
tags: ["zcash", "privacy"]
---

This blog post documents behind the scenes of why BUIDL Labs team went about building the [ZCash Service Status Dashboard](https://www.zcashservicestatus.info/) with the support of the [ZCash Foundation](https://www.zfnd.org/) by answering the following questions:

1. How did we come across the ZCash Project?
2. What inspired us to build for the ZCash community?
3. How did we find the niche space in which we can contribute?
4. How did we go about getting funds for the value we wanted to create for the community?
5. What processes did we follow while building to ensure accountability, clarity, and alignment towards the outcome?
6. What were we able to accomplish?
7. What is our long term plan to contribute to the community?

## How did we come across the ZCash Project?

Since early 2019, BUIDL Labs team has been deep-diving into the blockchain industry after being inspired by the audacious vision of the pioneer's and their team's building in this space. [Read more on how we aim to contribute.](/about)

Since our team believes in learning by building, we were itching to start contributing our engineering and growth bandwidth to some of these teams, and that itch led our small team to [the ZCash project.](https://z.cash/)

## What inspired us to build for the ZCash Project?

We were inspired by their mission of building an open and trustworthy financial system that doesn’t put one's privacy and freedom at risk.

The teams working to steward the mission have built out [ZCash](https://z.cash/) - a privacy-protecting, digital currency built on the science of zero knowledge proofs.

Like other cryptocurrency networks (e.g. Bitcoin or Ethereum), Zcash allows anyone with a computer and an Internet connection to send and receive scarce tokens that can be used like cash on the Internet.

The alchemy of ZCash technology lies in it's strong privacy guarantee where shielded transactions in Zcash can be fully encrypted on the blockchain, yet still be verified as valid under the network’s consensus rules by using zk-SNARK proofs. [Read more about Zcash works under the hood here.](https://z.cash/technology/)

### Why the need for ZCash?

ZCash aims to solve the problem of financial privacy. This example illustrates why it is important:

> Bitcoin has been around for almost a decade, and by now many people have realized that it is [not nearly as private or anonymous](https://coincenter.org/entry/how-anonymous-is-bitcoin) as many initially thought. That can be a good thing when it comes to [catching criminals](https://coincenter.org/entry/how-can-law-enforcement-leverage-the-blockchain-in-investigations), but it can also be a bad thing for innocent users. In fact, Bitcoin’s current specifications make it almost impossible for an unsophisticated innocent user to have any privacy.
>
> Here’s a simple example. Most people use bitcoin by sharing a payment address that looks something like this:
> 1CPwNACt62wts2yGbz1vUuqeGD58SzzeAL
>
> Maybe that address belongs to a bartender. To accept bitcoin for cocktails the bartender puts that address on a poster behind the bar in the form of a QR code so it would look something like this (courtesy of [Room77 in Berlin](http://www.pri.org/stories/2013-10-04/if-you-wanna-buy-beer-berlin-bring-your-bitcoins)): ![http://coincenter.org/files/2016-12/room77-small.png](http://coincenter.org/files/2016-12/room77-small.png)
>
> Patrons at the bar can take a picture of that code with their smartphone and use a bitcoin wallet app to pay that address for their drinks.
>
> Trouble is, anyone can look that address up in the Bitcoin blockchain and see every incoming transaction and the total amount of bitcoin sitting in that address.
>
> If we look up that information, then we have at least some idea of how rich the bartender is (good information for a would-be robber), and how successful the bar has been (good information for the competing bar next-door).
>
> Also, if we sat next to someone while they took a picture of the payment code with their phone, then we might have a good idea of how rich the customer next to us is as well by identifying the most recent incoming transaction for the bartender’s address and looking up the balance of the sending address, the customer’s address.
>
> Source: [What is ZCash?](https://coincenter.org/entry/what-is-zcash)

To put the above example in perspective of the current status quo, just imagine the iota of privacy you have when you use centralised systems of payments. 😰

### People behind the project

We were also inspired by the people working on the ZCash project. Recommended playlist to get a sense of the state of mind of the pioneers building this crucial technology:

`youtube: aR-r6q0d6BE`

`youtube: qRypm80AOmM`

Impressed and in awe of the vision and the problem the project is solving, the itch had transitioned to a strong desire to contribute.

In this midst of deep diving, we came across [ZCash Foundation Grants Platform](https://grants.zfnd.org/) - where the Zcash Foundation funds Zcash development, research, and other ecosystem projects to further advance the mission of the ZCash project. Our small team was stoked hearing that there were real incentives at play if we can add value.

The only question left answering was: what can we build?

## How did we find the niche space in which we can contribute to the community?

First, we did a breadth-first search of the areas that community wanted help in, and in this search we came across this [list of grant ideas.](https://www.zfnd.org/grants/#ideas)

We then researched each idea in depth to get vantage on why exactly does this idea need a solution from a community perspective. After spending a week on the Internet in understanding and chewing on the concepts that each idea was talking about, we had a bunch of questions that needed answers before moving ahead.

Here we got in touch with [Sonya Mann](https://www.sonyasupposedly.com/), who runs communications at ZCash foundation with our doubts. She patiently listened to our questions and pointed us in the right direction. We also realized that this research would be valuable for the builders interested to contribute at large and hence assimilated all our research into one document and created an [FAQ around grant ideas on ZCash's community forum.](https://forum.zcashcommunity.com/t/faq-around-grant-ideas/33648)

Another thing which we noticed while interacting with the community is how impressive the community's stance is on public discourse and discussion. One needs to only spend a few days to get a feel of the wide ranging and nuanced discussions that happen on the forum.

### Zeroing in

Afer assessing our strengths and the limited vantage we had acquired so far about ZCash, we decided to brainstorm a solution for the "Ongoing Services section" where the community wanted a service status dashboard that monitors the status of the dozens of ZCash related online services.

## How did we go about getting funds for the value we wanted to create for the community?

#### Step 1: Get vantage on the problem

In our research for a solution, we noticed that there didn't exist a single source of truth for these services leading to information asymmetry for the ZCash users. One example of the problem: different block explorers were reporting a different state of the ZCash blockchain.

Next, we went about doing an exhaustive research to figure out what all different services that existed in the ZCash ecosystem. The outcome of the above research process yielded [ZCash Ongoing Services Exhaustive List](https://docs.google.com/spreadsheets/d/1ESq4EA4dQ9UB3sUNiBwLEXm26YhUMheXbzr-ednFI0M/edit#gid=0) - which covered all the different services that we were able to find and standardize into buckets.

#### Step 2: Get alignment consensus with the community around the proposed solution

We shared the above sheet in [ZCash Community Chat](https://chat.zcashcommunity.com/channel/the-zcash-foundation), where community members helped us in refining the above list. After getting 👍 to proceed ahead, we sketched out the solution in solving the problem which in theory would do the following:

- A health check monitoring service that monitors specific health checks attributes for different categories of external services that exist in the ZCash ecosystem.
- A user friendly dashboard to view as a single source of truth that consumes the data from the above service.

We also decided to split the value proposition into two parts:

1. The first proposal would cover the expenses related to laying the foundation of the dashboard + 1/3rd of the services that we had discovered.
2. The second proposal would build upon the foundation by extending the surface area of monitoring by adding 2/3rd of the remaining services.

The reason behind splitting the value proposition was twofold:

1. Ship out an MVP: since we were operating in a new paradigm in a technology we don't fully understand, we wanted to ship out a functional MVP with a reduced scope. The lessons learned while shipping plus the feedback we would gain from the community will give us insights on how to tune our operations.

2. Establish trust: since we had no history of contributing to the ZCash project, we believed in creating a lower risk - lower reward commitment for both stakeholders involved.

We again took consensus around the above approach and then moved ahead with writing up the first draft of the proposal.

#### Step 3: Submit proposal on ZF Grants Platform for community feedback

1. After various iterations on the draft to ensure clarity and objectivity around outcomes, we submitted our [first proposal on ZF Grants Platform.](https://grants.zfnd.org/proposals/761374418-zcash-service-status-dashboard)
2. We got great feedback in terms of questions. [We took time to answer them in detail](https://hackmd.io/@prastut/rkgi7mHgH) and incorporated the answers to the above questions inside the proposal.
3. We also posted the [link to the proposal on ZCash Community forum](https://forum.zcashcommunity.com/t/zcash-service-status-dashboard/33982) to 🚨 the community at large of what we are aiming to accomplish as well as inviting them for feedback and constructive criticism.

#### Step 4: Get funded!

The ZCash Foundation was kind enough to take a bet on us by funding our first proposal! We used the same process and followed up with the second proposal which was funded by the foundation again. 🙏

## What processes we followed while building to ensure accountability, clarity and alignment towards the outcome?

In all this process, we kept ourself level headed with the perspective in mind that the foundation is betting on random people on the Internet who they haven't met and aren't accessible at all times.

We wanted to ensure that we live up to the trust. We created a system of weekly heartbeat accountability - where we documented weekly progress made on a google doc that was shared with the community. Following are their links:

1. [ZCash Service Status Dashboard - Proposal 00 - Progress Logs](https://docs.google.com/document/d/1Y_quhg9RQxqH3heT5dFd5ZqscPBoLSTt_F6uI6B0Xuc/edit?usp=sharing)
2. [ZCash Service Status Dashboard - Proposal 01 - Progress Logs](https://docs.google.com/document/d/1DocF0E0W9JsnizV99MqNpGdSEjBdFEzM5wSKjSpmnEc/edit?usp=sharing)

## What were we able to accomplish?

We built out [ZCash Service Status Dashboard](https://www.zcashservicestatus.info/) or ZCash SSD, which monitors several health check attributes and analytics across the following group of services:

1. [ZCash Specific Metrics analytics](https://www.zcashservicestatus.info/d/ShOdZ0AWk/zcash-specific-metrics?orgId=1)
2. [Blockchain Explorers Sanity Checks](https://www.zcashservicestatus.info/d/DyDEf8AZk/blockchain-explorers?orgId=1)
3. [ZCash Community and Forums Services Sanity Checks](https://www.zcashservicestatus.info/d/Pic_sbHZz/community-and-forums?orgId=1)
4. [ZCash Token analytics across various exchanges and trading pairs](https://www.zcashservicestatus.info/d/n-3yUXNWk/exchanges?orgId=1)

The dashboard aims to provide a single source of truth for health check + data being reported by all the above services.

## What are our long term plans to contribute to the community?

#### Ideas to further extend ZCash Service Status Dashboard

1. Enabling Community Participation: enable ZCash users to create charts that they think are insightful around the data the dashboard is ingesting and sharing with the community as a whole. In technical terms, we want users to sign up on our Grafana dashboard and spinoff their own dashboards!
2. Monitoring Node for Miners: we are inspired by [Jameson Lopp’s](https://www.lopp.net/) work on [Satoshi](https://statoshi.info/) whose objective is to protect Bitcoin by bringing transparency to the activity occurring on the node network. By making this data available, Bitcoin developers can learn more about node performance, gain operational insight about the network, and the community can be informed about attacks and aberrant behavior in a timely fashion. We want to extend the dashboard with the same vision by borrowing and modifying Jameson Lopp's ideas:
   - Building a pool of ZCash SSD nodes that act together in order to monitor a larger portion of the node network and thus provide a more complete picture.
   - Sending alerts to ZCash developers about aberrant behavior on the network, such as changes of more than one standard deviation.
   - Automated quality assurance tests / sanity checks. For example, adding alerts that would fire if the sum of zcash in existence ever changes by an amount other than the block reward in a single block.
   - Graphing the data collected by ZCash SSD nodes is but one of many possibilities. It could be useful for us to provide batch files of the raw data collected so that other engineers can analyze it, or we could build an API devoted to making it easy to query the data.
   - Automated defensive measures / spooling up honest nodes to combat certain types of attacks.

#### General Plans

Our team is aiming to build more infrastructure projects that help the ZCash community in this year 🚀

## Closing Notes

We believe that financial privacy is a fundamental right for every individual.

We concur with [Vitalik Buterin's views on ZCash Project in late 2019](https://twitter.com/VitalikButerin/status/1204803955131322369?s=20) that [Electric Coin Company](https://electriccoin.co/) & [ZCash Foundation](https://www.zfnd.org/) are doing a stellar job in diligently building out this important technology and it's ecosystem.

We recommend reading [Electric Coin Company's roadmap for 2020](https://electriccoin.co/blog/ecc-flight-plan-for-2020/) to see the impressive work in store for ZCash community this year. We are personally bullish on consumer-facing shielded lite wallets in reducing friction in the adoption of shielded transactions.

A special thanks to the team at ZCash Foundation for supporting our work and a big hug to the following people:

- [Sonya Mann](https://www.sonyasupposedly.com/): for helping out whenever she can and encouraging us to push forward. We also admire her hard work in moderating the discussion for the ZCash community.
- [Eran Tromer](https://www.tau.ac.il/~tromer/): for his precise feedback and his insights on how we can do better.
- [Josh Cincinnati](https://twitter.com/acityinohio): for patiently giving feedback and pointing us in the correct direction once when we had lost our way.
