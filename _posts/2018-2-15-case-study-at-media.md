---
layout: work
date:   2017-09-03 16:16:01 -0600
category: case_study
image: assets/images/AT_Media.png
title: "Apartment Therapy: Designing a Healthier Happier Home"
excerpt: "Designing lifestyle-focused digital products at scale with an engineering-forward team."
role: Product Designer
year: 2016-Present
platform: Web
series: TL;DR
---

### In 2016 I transitioned from 4 years of working as a web and graphic designer to working on digital products full-time and on purpose. After interviewing with a few companies I landed at Apartment Therapy. The team, the culture, and the focus on quality have kept me going for just over 2 years.

### Content Personalization
#### The Problem
_Can we deliver specific content to specific people depending on device context?_

The short answer is yes, but we weren't sure what that looked like. Our editorial goal was to deliver more focused content to our "Below-Post" area on article pages. Our product goal was to test using The Parse.ly Recommendation API against The LiftIgniter Machine Learning API to deliver personalized content based on context and engagement.

With editorial and product goals, there are obviously business goals to lean on as well. For this feature, our business goals sat on the shoulders of our Engagement OKR for the quarter. The hypothesis was that we could deliver more opportunities for readers to read better content. Readers finding more content should raise our content shareability and in turn visibility for ad impressions.

#### The Process
Our cross-functional team came together to put together a common-sense scope for our project. What came out of that were a few ideas on how we could make this engaging and fun for users to navigate the three categories of content we want to deliver:
- Could we make it feel magical?
- A choose your own adventure game?
- A survey of some sort?
- A simple tabbed solution?

Lots of other fun and kind of silly possibilities were discussed. Based on some of the ideas and notes we took, I started playing around in Sketch trying to see what some of those ideas might look like.

After reviewing what we had in Sketch, we moved the mockups to InVision to test them out. We realized that the fun ideas we had were kind of terrible for a reader. They were not at all conducive to skimming headlines and reading articles. This was super valuable feedback from people testing the prototypes. It drove home that we were trying to be too clever.

During our regroup with my Product Manager, it became more and more clear that we were starting too big. We needed to scale back and start again. What does that look like? How does that feel? We refocused and simplified our original scope:
- We have three content types we need to deliver to all readers
- We want all three to be optimized across devices
- We need an easy-to-use interface that doesn't feel clunky

Based on these learnings t was clear that building this into some sort of game didn’t feel on-brand and didn’t meet the goals of this feature. So we stripped everything back to a significantly lower common denominator for testing. We still wanted an interactive experience so we started with 3 clickable tabs correlated to our three content categories.

In implementation we ran an initial test comparing Parse.ly to LiftIgniter apples-to-apples and saw a marked difference in engagement.

#### Results and Iteration
What we found after a few days of monitoring analytics numbers was that very few people (<2%) were switching through the tabbed content on larger screens and smaller screens were doing only slightly better. After talking through the results and ramifications, we decided to split the three content types out into three columns on larger screens. We kept the tabbed interface on smaller screens in hope that adoption was taking more time than expected. While tabs hide content and hiding content is almost never a good thing.

It wasn't. We got analytics numbers back and "desktop" click through rate had gone up from 3.6% to 5.8% and "mobile" had gone down to 3.3% with 99% of clicks coming from the default active tab. Up to this point, we had been using the Parse.ly API to drive recommendations in the "Related" and "Popular" tabs. We decided to follow some suggestions from Parse.ly and LiftIgniter to test a “back to the drawing board” option. Their data suggests that a simple 4x3 grid of article teasers might increase overall interactions.

Based on Parse.ly and LiftIgniter suggestions we did, in fact, remove all tabs on smaller screens and went to a 3 row, 4 column view on larger screens. Switching to this layout yielded growth in teasers clicked across screen sizes. As time has gone on we’ve tested and  implemented more changes. Moving to LiftIgniter to power most of our machine learning-driven content recommendations. Splitting recirculation into a mix of plain text links after post content and switching most of our teasers to a highly scrollable new horizontal teaser design. Click through rates seem to hover around 8%. The Apartment Therapy team continue to test, monitor and iterate to deliver the best context-optimized content recommendations.

<hr>

### Color Search by Sherwin-Williams
My first project at AT Media was a complete overhaul of our Sherwin-Williams sponsored Color Search tool, which was a collaboration with McKinney. I came into the process as wireframes were being handed off and was able to jump in and contribute to the team in the first 2 weeks after I started. Our work did not go unnoticed - along with our partners at McKinney and our direct sales and creative services teams, our work on Color Search won an IAB Mixx award in 2016.

<figure class="container__image container__break">
  <img src="/assets/images/color-search-screens.png" alt="4 iPhones with various screens from the color search interface" />
  <figcaption class="mt-half center mb-1">
    <small>The Home, results, location search and image detail screens from color-search.</small>
  </figcaption>
</figure>

### Helping Build an A/B Testing Framework and Using it
Because of my love for data-informed design I was tapped to work with our Lead Front End Engineer to build a new system into our - largely monolithic - codebase. Using a fancy Varnish setup, courtesy of our Back End team, we created an internal methodology to use feature flippers and traffic splitting via our CDN. We were able to test this out of the box on social sharing designs for images. Our tests Eventually produced a 20% increase m/m in social sharing to Pinterest.

<figure class="container__image container__break">
  <img src="/assets/images/ab-testing.png" alt="8 photos with icons for Pinterest with a green checkmark on the 'winning' option" />
  <figcaption class="mt-half center mb-1">
    <small>A/B test options across 2 different tests over the course of several weeks. (photos are via Unsplash for presentation only)</small>
  </figcaption>
</figure>

### Home Page Teaser Redesign
At the end of 2017 our team wanted to be more experimental and take more risks with how we were showing content. A piece of low-hanging but effective piece of fruit related directly to this was our home page teasers. Those little image and text sandwiches that give our readers hints about what they're looking at and for. We say a 35%+ increase in clicks on teasers on the home page by updating our layout to be more scroll-friendly. I worked with our Lead PM and my Design Manager to work through a couple of iterations of a horizontal teaser. Using our A/B testing framework and Google Optimize, we tested a couple of treatments. What we landed on was simple and scrollable and was a great win in user engagement metrics.

<figure class="container__image container__break">
  <img src="/assets/images/teaser-update.png" alt="2 screens showing two different teaser styles, one vertical and one horizontal. Indicators show the horizontal version was better." />
  <figcaption class="mt-half center mb-1">
    <small>Moving from vertically arranged teasers to horizontal ones increased clicks on the home page by just under 36%</small>
  </figcaption>
</figure>

### Community Focused initiatives
My all-time favorite projects for AT Media have been the online community driven initiatives. Launching our new Save feature, refreshing our profile pages and ongoing projects to integrate more connective community features have been a joy to work on. We have a dedicated user0base that loves to connect through comments and social media. It's been a real treat developing features to satisfy some long-standing requests and work with users to develop a roadmap of new and upcoming features.

<figure class="container__image container__break">
  <img src="/assets/images/at-community.png" alt="The mobile and desktop views of our community pages" />
  <figcaption class="mt-half center mb-1">
    <small>The project focused on giving users a more mobile-feeling experience at small sizes and integrating the ability to save stories to community profiles.</small>
  </figcaption>
</figure>
