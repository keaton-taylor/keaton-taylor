---
layout: work
title:  "RaiseMore"
date:   2017-01-01 09:13:10 -0500
categories: work
image: assets/images/rm-cover-img.png
---

## Summary
I'm a big fan of movies and comic books, and my number one source to see where those intersect is [ComicBookMovie.com](http://www.comicbookmovie.com). There's great journalism and a strong community there, but the overall experience of the site is lacking both on mobile and on desktop. More often than not I personally find myself trying to access CBM on my mobile device and have the issue of pinching and zooming constantly, making the experience of the whole thing a nightmare. 

## Competitor Analysis & Business Considerations

![ComicBook.com Mobile View](assets/images/rm-cover-img.png)
![SuperHeroHype Mobile View](/assets/images/shh-mobile.png)

These two sites rank lower in search results than comicbookmovie.com but both have considerably more navigable sites on mobile than CBM. Seeing as CBM still apparently has a leg up in the market, there is room for potentially significant growth by branching into the mobile space. My first inclination was a responsive website with ads baked in and support for administering the messaging/bb side of things. The more I researched issues with ads in a responsive setting (~6% of users are using ad blocking software*, Probable need to use a polyfill like PictureFill† or deal with Safari issues with iframes to effectively switch ads at proper sizes) the less hopeful I was about a proper solution. My preliminary solution was simply use the PictureFill polyfill to art direct ads at different sizes and use a single image for it with html text overlayed. With a community driven content stream and a small core team (from what I could find in my research) the upkeep of managing a technical ad display might not be feasible. 

My second inclination was to diversify the monetization strategy. While a responsive redesign is sorely needed to keep up with the mobile device surpassing the desktop computer, there is something to be said about moving away from being solely funded from ads. The problem with ads is that... well, ads suck. 

## Responsible Alternatives to Ads
So from the data we can extrapolate that ads are something users would pay to have removed. On the web there are a few different ways we can tackle this user issue. _Note: I am fully versed in the user ramifications of modals and feel very strongly that they are terrible. That said, I'm trying to think realistically about timeframes and client needs. There would be implementation of whatever the new monetization strategy before there would be any potential redesign. That data would be the driving force behind a responsive redesign._

### I See You Use an Ad Blocker: 
This is an easy way to achieve a win with users. On load we can fire off a modal that gives the user some sense of CBM having some empathy for their choice to use an ad blocker. Essentially CBM would use some friendly copy to let users know that while they understand that ads are obnoxious, CBM.com is looking for alternative methods of sponsorship and it would be awesome if the user would consider turning ad block off. 

![There are better ways](/assets/images/cbm-ad-block-messaging.jpg)

### Paywall with an Allowance: 
A lot of Newspapers use this method. "You have an allotment of 5 articles to click on today." Essentially it's a nice way to let users read some news but hopefully frustrate them into paying a few dollars a month to read what's there uninterrupted and uninhibited.

![You have 4 articles left](/assets/images/cbm-platinum-articles.jpg)

### Ad Free Membership: 
This model would essentially just add a tier to their become a member section that drops all ads from their view. Simple fix when we're talking about a website managed by a CMS. This is essentially the same thing as a paywall but is offered on signup and intermittently through the site and gives no negative consequences to unpaid users. 

![Pay a couple bucks](/assets/images/cbm-sign-in.jpg)

## The Persistent Problem
All of these are valid choices (if you've got the data to back them up) but there still exists a gap in experience that even a responsive redesign can only put a bandaid on. With a responsive site on mobile, the user will still have to load ads from either the CMS or from an ad network like BuySellAds for example and they'll almost certainly have to use some Javascript to get the ad switching done if they'd like to do it well. There are ways to limit pain points there, like loading ads asynchronously and using css to switch ads at break points (If you're managing them yourself). The sad reality is that most publications would need to undergo a multi-month (if not year) redesign of the whole system from the top-down in order to implement some of this new functionality. With a built in readership that has little to nothing to lose continuing to read the site as is, the benefit of a complete overhaul may not be there without a guarantee that there is business benefit from it.

Possible alternative monetization options:
- Low cost mobile app (Iconic maybe? sub $2 price point) 
- Premium Membership ($XX per year nets ad free experience and early access to content?)

### Considerations:
User pain points (hypothesis)
- Poor mobile experience
- Very cluttered web experience

Business considerations
- Ad Revenue
- Registered Users 
- Chat/bb Functionality
- Content Supplied by Community

### User Research
I set out to gather more data from users of the website. Ultimately I could only get 5 users to respond in the first few weeks so I was working preliminarily off of assumptions a lot more than data. The data I DID have told me some interesting things: 

1. None of the users were registered.
2. Their primary goal is to view content (which seems like a no-brainer, but having data that backs that up re enforces the ideas behind presenting clients with a content first and content most approach.) and in 50% of respondents, the comments were of equal or only slightly lesser value.
3. Around 60% of users responded that they would be willing to pay for a mobile app if it was free of advertising. 

The bit about the comments was a surprise for me because I see comments sections as a declining piece of the puzzle. That said, I can see why there might be value in a community based around a very subjective topic. Discussion and sharing ideas in a semi-safe, self policed comment section.

### So where are we left?
Here's what we know: 
- Revenue streams work well enough as they are now. 
- An RWD overhaul will be expensive and will likely result in some user attrition. 
- Attrition will likely hurt revenue from ads, and as such diversifying revenue prior to a redesign might make more sense. 

## My Recommendation
My recommendation, as you may have suspected, is to craft a mobile app using a hybrid mobile app framework (Ionic, Phonegap, Mobile Angular UI, Titanium, etc.). Using a hybrid framework is inherently a less costly route as a talented front end dev could do the heavy lifting, contrasted by the high cost of hiring a mobile engineer and working in native Swift or Objective C. 
