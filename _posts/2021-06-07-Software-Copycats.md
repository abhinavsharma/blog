---
layout: post
title: In defense of software copycats, as someone who got scooped
---


To cut to the chase, this is a story about why we should stop trying to fight copycats because they are both inevitable and healthy. Two interesting things happened today that made me think of this deeply.

First, we build [Insight Browser](https://insightbrowser.com), it is in our honest opinion the first powerful truly extensible browser for iOS. We built it because after years of waiting for more powerful iOS web browsers but not seeing it happen, we thought there was a market there and went for it. We've put a lot of blood, sweat and tears into it. Today at WWDC, Safari announced extensions for iOS.

- Does it suck to see the nature of your market change overnight? Yes.
- Did we think it was possible at any time? Yes. 
- Were we prepared? I think so, but it's definitely not Plan A.

To take a short break from this, I went over to Hacker News only to find [How Replit used legal threats to kill my open-source project](https://intuitiveexplanations.com/tech/replit/) on the top spot. In particular,I was surprised to see this quote from the CEO of a modern software company.

> __I think you should take it down and stop working on it. I'll be engaging our lawyers on Monday if it's still up by then. ____[...]____ We were a tiny company when you interned with us ____[...]____ Luckily we're bigger now, and crucially have a lot of money to pay for top lawyers now if we're forced to go that route.__

While our case was startup vs. mega-company (and it's very possible Apple doesn't even acknowledge us), it was interesting to see a similar dynamic play out at bigger startup vs. indie dev right after.
This got me thinking — copycats are inevitable to the nature of innovation, so how do we best embrace it so that 

1. innovation still happens 
2. first movers are not overly disadvantaged 
3. do that while preserving funding for ideas

## Why copycats are inevitable

Software is fundamentally cheap to build (in terms of physical resources, not talent), and **the more beloved the software, it becomes cheaper to build at an exponential rate**. There are 3 important tailwinds behind this in my opinion.


### Law of Open Source Discounting
If 2 software products share any functionality, that component almost inevitably becomes an open source project or its own SaaS company.

### Law of UI Design Discounting
The first mover spends a lot of time perfecting the user experience, the next person can clone it in 1/10th the time.

### Law of Un-monopolizability of Ideas
In software, ideas are extremely difficult to "own". You could try patenting software but there's many ways around it (see the Apple vs Google or Google vs Oracle Android cases). In particular if both parties have legal resources the end result is usually the copying going through anyway and lawyers on both sides pocketing the money.

The point is, if something has an incentive to be copied, it ends up getting copied. If not at first by a small indie project, then by another behemoth.

## Why midsize founders and large-size CEOs don't like copycats

Most of this is just stating the obvious, but the reasons are subtly different as the company getting copied gets bigger, so in order from smaller company to bigger company.

1. You invested a lot of time and effort refining your idea and someone else can just come along and beat you with relative ease, while picking up some of your ideas along the way. That never feels good.
2. Maybe you can't reduce your burn rate to below that of a cheaper, more open competitor while protecting your personal and professional social status.
3. At some level you may have been hoping that if you grew your brand fast enough, you may have pseudo-monopolized the idea.
4. You know your current position is extracting more rent from users than they could if viable competitors existed.

Zero to One popularized the notion that competition is for losers, so the new game in town is that of establishing the first monopoly. Kind of ironic.

## Why copycats are healthy

This is Economics 101. If there's no competition then over time, pricing for successful tools escalates, especially if their primary funding comes from B2B sales.

Here's a few **tools I absolutely love** to use and am a happy paying customer for, but their functionality is fairly commoditized and their prices are relatively high for their complexity.

- Calendly: $10/month
- Roam: $15/month
- Airtable: $20/month
- Typeform: $30/month

1. Do I think these prices justify the value I get from them? Yes.
2. Do my costs add up when you use dozens of SaaS tools? Yes
3. At their current level of success, would these products cost anywhere near what they charge to build and operate? No.
4. As a user, would I prefer to pay the same amount to fund an open-source clone? Yes, because I want to protect myself against price hikes and unwanted functionaliy changes.
5. Would these products and the ideas behind them have had their current level of success without a healthy cash balance early on in their lives? 

**Well, that's the hard one, isn't it**

## But will how will early ideas get enough funding to be iterated on?
First, to put aside any sense of unfairness towards venture funded companies, VCs at every stage already fund adjusting for projected defensibility. "What's your moat?" is (almost) every VC's first question and their estimation adjusts for your defensibility model. They know what they're getting into re. defensibility  and so do the founders who are fundraising.

Newer models like Github funding, Patreon, and the Open Collective are increasingly viable alternatives in solving the collective action problem of raising funds for software that was previously only fundable by venture.

Moreover, projects like Athens are demonstrating that even hybrids are possible — [Athens' $1.9M Seed Round, led by Caffeinated Capital (athens-research.ghost.io)](https://athens-research.ghost.io/athens-1-9m-seed-round-led-by-caffeinated-capital/).

## Some takeaways to chew on


- In the long term, ideas, technology and UI design just aren't very defensible in the way network effects, regulatory capture and control of capital markets is.
- Nevertheless, it's still worth building software that many people want and like because defensibility is often established after-the-fact in a bundling play to become a network or through the establishment of your brand.
- And yes, there are casualties and yes it can feel horrible to be copied, especially by someone with more resources, but you know that's what you're signing up for if you're starting a software company.
- This is one of those questions where there's no easy right answer, but people's positions usually very directly map to their company's current market position.