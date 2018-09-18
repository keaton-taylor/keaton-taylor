---
layout: work
date:   2017-09-13 16:17:01 -0600
category: case_study
title: "Apartment Therapy: Delivering Better Content"
excerpt: "In 2016 I transitioned from 4 years of working as a web and graphic designer to working on digital products full-time. After interviewing with a few companies I landed at Apartment Therapy. The team culture, engineering focus and commitment to quality have afforded me incredible learning opportunities. One of the most memorable projects we approached involved trying to deliver personalized content to our readers."
role: Product Designer
year: 2016 - 2018
platform: Web
series: CASE STUDY
URL: www.apartmenttherapy.com
class: at
---

### The Challenge, Hypothesis and Goals

**Challenge:** _How can we deliver more personalized content options to our readers?_

**Hypothesis:** By implementing and testing data driven recommendation APIs, we can deliver better content to our readers, more consistently.

**Background:** We already used Parse.ly for editorial analytics, so pulling recommendations from their API was a relatively low hurdle. In addition to Parse.ly we planned to test LiftIgniter, a machine learning API for making recommendations. We had already been using Parse.ly for a limited number of users and saw an upward trend in related metrics.

**Editorial Goal:** Deliver better content recommendations on article pages.
**Metrics:** Time on Site and Pageviews.

**Business Goal:** Raise viewability numbers for advertising impressions.
**Metrics:** Viewability, Impressions and CTR for ads in DFP.

**User Goals:** Make it easier and more fun to read AT Media properties by making relevant content easier to find.
**Metrics:** Social sharing and Unique sessions.

### The Process
Out of the gate our cross-functional team came together to define a common-sense scope for our project. What came out of that were a few ideas on how we could make this engaging and fun for readers to navigate the three categories of content we want to deliver. Some questions started to crop up:
- Could we make it feel magical?
- A choose your own adventure game?
- A survey of some sort?
- A simple tabbed solution?

<div class="container__images">
  <figure class="container__image">
    <img src="https://ktportfolio-cdn.sirv.com/Images/at-idea1.png?progressive=true&png.optimize=true" alt="A sketch for a custom content experience with yes no questions" />
    <figcaption class="mt-half center">
      <small>Idea 1: Choose Your Own Adventure!</small>
    </figcaption>
  </figure>

  <figure class="container__image">
    <img src="https://ktportfolio-cdn.sirv.com/Images/at-idea2.png?progressive=true&png.optimize=true" alt="A sketch for a custom content experience with personal preference options" />
    <figcaption class="mt-half center">
      <small>Idea 2: Choose Another Adventure!</small>
    </figcaption>
  </figure>

  <figure class="container__image">
    <img src="https://ktportfolio-cdn.sirv.com/Images/at-idea3.png?progressive=true&png.optimize=true" alt="A sketch for a custom content experience with user selectable options" />
    <figcaption class="mt-half center">
      <small>A Stand Alone Component That Changes State From Questions to Content Presentation</small>
    </figcaption>
  </figure>

  <figure class="container__image">
    <img src="https://ktportfolio-cdn.sirv.com/Images/at-idea4.png?progressive=true&png.optimize=true" alt="A sketch for a custom content experience with tabbed selections" />
    <figcaption class="mt-half center">
      <small>Idea 4: Components That Could Be Tab-Based</small>
    </figcaption>
  </figure>
</div>

Lots of other fun and kind of silly possibilities were discussed. We compiled research both on what had worked for us in the past and what other media outlets were doing to make related content more visible. The options kind of ran the gamut or what was possible: text links, teaser rolls, simplified teasers, images, stylized images. It was kind of all over the place. Based on our research and some of the notes we took, I started playing around in Sketch trying to see what some of those ideas might look like.

<figure class="container__image container__break">
  <img src="https://ktportfolio-cdn.sirv.com/Images/at-iam-statements.png?progressive=true&png.optimize=true" alt="concepts for choose your own content adventure." />

  <figcaption class="mt-half center mb-1">
    <small>Quick Mockups for a Choose Your Own Content Component.</small>
  </figcaption>
</figure>

After reviewing what we had in Sketch, we moved the mockups to InVision to test them out. Through some simple user testing (both in-person and through UserTesting.com's PEEK feature) we realized that the fun ideas we had were kind of terrible for a reader. We tested the concepts with readers inside our ideal demographics range: Two female and one male, between 24-34, 2 with children, one without. The overwhelming response by these readers was that we had made the interface more complex than it needed to be. Some specific comments were, "I might use this once, but it's pretty cumbersome," and "My only problem... is that this makes me have to think a lot more than I feel like I should about what I'm going to be seeing." It was clear that these early concepts created roadblocks for readers and were not conducive to skimming headlines and clicking into articles. This qualitative data early on was a guiding light for the concepts that came after.

During our regroup with one of our Product Managers, it became more and more clear that we were starting too big. We needed to scale back and start again. What does that look like? How does that feel? We refocused and simplified our original scope:
- We have three content types we need to deliver to all readers
- We want all three to be optimized across devices
- We need an easy-to-use interface that doesn't feel clunky

Based on these learnings it was clear that building this into some sort of game didn’t feel on-brand and didn’t meet the goals of the feature. So we stripped everything back to a significantly lower common denominator for testing. We still wanted an interactive experience. We wanted readers to feel like they were in control of the experience. As such we doubled back to try the concept with 3 clickable tabs correlated to our three content categories.

<figure class="container__image container__break">
  <img src="https://ktportfolio-cdn.sirv.com/Images/at-bg-img2.png?progressive=true&png.optimize=true" alt="Simpler content delivery." />
  <figcaption class="mt-half center mb-1">
    <small>A simplified interface that feels a little more on-brand.</small>
  </figcaption>
</figure>

In implementation we ran an initial test comparing Parse.ly to LiftIgniter apples-to-apples and saw a marked difference in engagement. LiftIgniter was clearly making more actionable recommendations. Over time we would come to traffic most of our reader recommendations through LiftIgniter because of the staggering increase in engagement.

### Results and Iteration
What we found after a few days of monitoring analytics numbers was that very few people (<2%) were switching through the tabbed content on larger screens. Smaller screens were doing only slightly better. After talking through the results and ramifications, we decided to split the three content types out into three columns on larger screens. We kept the tabbed interface on smaller screens in hope that adoption was taking more time than expected.

It wasn't. We got analytics numbers back and "desktop" click through rate had gone up from 3.6% to 5.8% and "mobile" had gone down to 3.3% with 99% of clicks coming from the default active tab. Up to this point, we had been using the Parse.ly API to drive recommendations in the "Related" and "Popular" tabs. We decided to follow some suggestions from Parse.ly and LiftIgniter to test a “back to the drawing board” option. Their data suggests that a simple 4x3 grid of article teasers might increase overall interactions.

<figure class="container__image container__break">
  <img class="no-shadow"  src="https://ktportfolio-cdn.sirv.com/Images/at-fourthree.png?progressive=true&png.optimize=true" alt="The four post by three column."  />
  <figcaption class="mt-half center mb-1">
    <small>The 4x3 grid of teasers on a large screen.</small>
  </figcaption>
</figure>

Based on Parse.ly and LiftIgniter suggestions we did, in fact, remove all tabs on smaller screens and went to a 3 row, 4 column view on larger screens. Switching to this layout yielded growth in teasers clicked across screen sizes. As time has gone on we’ve tested and implemented more changes. Moving to LiftIgniter to power most of our machine learning-driven content recommendations. Splitting recirculation into a mix of plain text links after post content and a highly scrollable new horizontal teaser design has been an unexpected win for us. Our design has again evolved so that most of our content on the home page as well as the below-post section follow a more traditional layout.

<figure class="container__image container__break ">
  <img class=" no-shadow"  src="https://ktportfolio-cdn.sirv.com/Images/at-new-upnext.png?progressive=true&png.optimize=true" alt="The four by three column." />
  <figcaption class="mt-half center mb-1">
    <small>Highly Scrollable new teasers</small>
  </figcaption>
</figure>

Click through rates on this new design seem to hover around 8-10% - which is incredibly high.

### Site Wide Teaser Iteration
At the end of 2017 our team continued to be more experimental and take more risks with how we were showing content. With the results from below-post updates in hand, we set out to test content delivery in other places. A piece of low-hanging fruit related directly to the personalization tests was our home page teasers. We saw a 35%+ increase in clicks on teasers on the home page by updating our layout to closely resemble our below-post tests. I worked with our Lead PM and my Design Manager on a couple of iterations. Using our A/B testing framework and Google Optimize, we tested multiple variants. What we landed on was simple and scrollable and was a big win for engagement metrics.

<figure class="container__image container__break">
  <img src="https://ktportfolio-cdn.sirv.com/Images/teaser-update.png?progressive=true&png.optimize=true" alt="2 screens showing two different teaser styles, one vertical and one horizontal. Indicators show the horizontal version was better." />
  <figcaption class="mt-half center mb-1">
    <small>Moving from vertically arranged teasers to horizontal ones increased clicks on the home page by just under 36%</small>
  </figcaption>
</figure>

The Apartment Therapy team continue to test, monitor and iterate to deliver the best possible context-optimized content recommendations.
