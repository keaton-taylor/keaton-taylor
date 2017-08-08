---
title: "Content Personalization - Apartment Therapy Media"
categories: work
layout: post
date:   2015-11-17 16:16:01 -0600
---

We had some questions from editorial and Audience development about contextual content delivery. "Can we deliver specific content to specific people depending on device context?" The short answer is yes, but we weren't sure what that looked like. Our editorial goal was to deliver more focused content to our "Below-Post" area on article or "Post" pages.

With editorial and product goals, there are usually business goals to lean on as well. For this feature, our business goals sat on the shoulders of our Engagement Objectives and Key Results (OKR) for this quarter. We have been trying to boost Pages Per Session (which turned out to be loftier a goal than we anticipated). The hypothesis was that we could deliver more opportunities for readers to read better content. From there, readers finding more content should raise our visibility for ad impressions.

We had a cross-functional meeting to get out some ideas and hone in on one or two that made sense. What came out of that were 2 guiding thoughts and myriad ideas on how we could make this happen.:
- We have three categories of content we want to deliver.
- It would be cool if it felt kind of magical.
- A choose your own adventure game, a sort of survey, a simple tabbed solution and lots of other fun and kind of silly possibilities were discussed.


![](https://www.dropbox.com/s/kl0ch2d95d0fn4f/cyoa.pdf?dl=0)
![](https://www.dropbox.com/s/dnghs2befcmu0rh/survey.pdf?dl=0)

We had an internal follow-up to talk with a PM and an Engineering partner about what the viable parts of this might look like. I took notes and started playing around in SketchApp trying to sketch (see what I did there?) out what some of those ideas might look like.

![](https://d2mxuefqeaa7sj.cloudfront.net/s_60E0029229ACD5198C41AE939A4759F18BB066A44C8415D7541EBA520BAE72D5_1499887124774_Screenshot+2017-07-12+14.18.29.png)
![](https://www.dropbox.com/s/cj2lzazog5lbxsw/Screenshot%202017-07-12%2014.12.44.png?dl=1)
![](https://www.dropbox.com/s/d5abimbauk4p0xe/Screenshot%202017-07-12%2014.15.47.png?dl=1)


After doing some internal reviewing, we moved some sketch mockups to Adobe XD to test them out. We realized that the fun ideas we had were kind of terrible for a reader who is trying to skim headlines and read articles. This was super valuable to hear from people testing the XD mocks. It drove home how much we were trying to be too clever for our own good.

During our regroup with my engineering buddy and PM, it became more and more clear that we were starting too big. We needed to scale back and start again. What does that look like? How does that feel? We knew a few things:

- We have three content types we need to deliver to readers.
- We want all three to be available on both mobile and desktop.
- We need an easy-to-use interface that doesn't feel clunky.
- Building it into a game out of the box doesn't feel on-brand and doesn't meet the business goals of this feature.

So we stripped everything back to it's lowest common denominator so we could test. Let's design 3 tabs and track analytics (20 million users per month so getting to statistical significance doesn't take a super long time).


![](https://www.dropbox.com/s/ji1dxz7j9w8ijn4/Screenshot%202017-07-12%2014.15.11.png?dl=1)


What we found after several days is that very few people (<2%) were switching through the tabbed views and clicking on content. More people were using the feature on small screens to begin with but that dropped off pretty quickly. We saw this data accumulate over the course of a few days. This led us to decide as a group that we were over-thinking the delivery of three types of content, especially on larger screens. Tabs hide content and hiding content is almost never a good thing. After talking through the ramifications, we decided to split the three content types out into three columns on larger screens. We also decided at that time to keep the tabbed interface on smaller screens. Our hope was that adoption of use was taking more time than expected.


![](https://d2mxuefqeaa7sj.cloudfront.net/s_60E0029229ACD5198C41AE939A4759F18BB066A44C8415D7541EBA520BAE72D5_1499887846262_Screenshot+2017-07-12+14.30.05.png)


It wasn't. We got click through rate numbers back and "desktop" has gone up from 3.6 to 5.8 and "mobile" has gone down to 3.3 with 99% of clicks coming from the default active tab. Up to this point, we've been using the Parse.ly API to drive recommendations in the "Related" and "popular" tabs. The next iteration on the books will be to remove tabs from small screens. To work on content delivery optimization, we're going to A/B test the Parse.ly API against a similar API from a company called LiftIgniter. I'll be helping with the design and front end of that process - writing CSS and editing React and Rails code.
