---
layout: work
date:   2017-09-03 16:16:01 -0600
category: case_study
image: assets/images/messaging-img.png
title: "RaiseMore: Making Fundraising Social for Fun and (limited) Profit"
excerpt: "RaiseMore was a social fundraising platform that used teamwork and social interactions to maximize fundraising efforts."
role: Product Designer
year: 2015-2016
platform: Web, Mobile
series: Case Study
---

### In the Summer of 2015 I joined a social fundraising platform. RaiseMore used teamwork and social interactions to maximize fundraising efforts. In turn we used the aggregate data to help predict fundraising trends and success patterns.

Making fundraising and nonprofit volunteering more fun and social is hard. Fundraising is often a solitary experience. You donate and you go about your business. At RaiseMore we wanted to make fundraising a team sport. How can we offer a competitive platform? How can we give leaders the power to coach based on performance & quantifiable metrics? We aimed to answer these questions and unfortunately the answer was sometimes, “We can’t.”

Our system built semi-custom native apps with the Ionic framework. Using a front end "store" workflow, users would choose colors, upload logos and adjust a template to their specs. Once finished, the mobile app compiled and was sent to the App Store. Users were then given access to a dashboard with tools to maintain their subscription and events.

I came to RaiseMore hoping to make a difference. I cut my teeth working for non-profit's like Art Feeds and the Hippo Valley Christian Mission. The idea that I could help similar nonprofits be successful was exciting.  I worked with the design team, engineers and our product manager to grok challenging day-to-day problems. In addition to being an IC and contributing day-to-day I also brought advocacy for a more user-centered process. At the time, my focus was moving from visual design to being more experience focused. That renewed focus was obvious in my work and interactions with coworkers. I set out to help other team members consider things like color accessibility and common interaction patterns.

#### On-Boarding
On-boarding is hard. Reworking the general login process was an imperative. One of the glaring issues was the technical debt left over from our Bootstrap MVP. During this Sprint we used more time than we expected walking through the signup process. The conundrum we spent the most time on was the amount of data we needed to collect. Where is the line between too much and not enough? We weren't sure. In hindsight what we were asking for became a barrier to entry.
Our goals for the update were:

- Make signup as easy as possible.
- Capture the smallest possible amount of information:
  - Organization - We need this to organize Teams inside the mobile app based on the Administrator's and Team Leader's org affiliation.
  - Name
  - Email
  - Password
- Immediately push people into an action after signup.

In the course of discussing the new on-boarding flow we exposed a glaring experience flaw. There were no less than 4 places for a person to sign up and define credentials.

<figure class="container__image container__break">
  <img src="/assets/images/rm-entry-points.png" alt="image There are at least 4 portals that will drop you into a Sign-Up situation" />
  <figcaption class="mt-half center mb-1">
    <small>There are at least 4 portals that will drop you into a Sign-Up situation</small>
  </figcaption>
</figure>

Mapping out entry points and making them cohesive and contextually relevant was a task. To limit the disparity between potential entry points was the imperative here. We made our goal to “Capture the smallest amount of information possible” our true North.

<div class="container__images">
  <figure class="container__image">
    <img src="/assets/images/rm-header-cta__modal.png" alt="image Header Call to action" />
    <figcaption class="mt-half center">
      <small>Header Call to action</small>
    </figcaption>
  </figure>

  <figure class="container__image">
    <img src="/assets/images/rm-header-cta__modal-success.jpg" alt="image Header call to action success modal" />
    <figcaption class="mt-half center">
      <small>Header call to action success modal</small>
    </figcaption>
  </figure>
</div>

Once a person works through the actual signup we prompt them to go through our "mini-store" experience to start customizing their app.

<figure class="container__image container__break ">
  <img src="https://d2mxuefqeaa7sj.cloudfront.net/s_F311AE08451D62116DFFACCBDC7E009E2FF890EF15810A623D30F66D11798920_1517346138952_Screenshot+2018-01-30+15.02.02.png" alt="image After signing up, you’re invited to customize your app - which is released to the  app store after your subscription is confirmed through our signup UI." />
  <figcaption class="mt-half center mb-1">
    <small>After signing up, you’re invited to customize your app - which is released to the  app store after your subscription is confirmed through our signup UI.</small>
  </figcaption>
</figure>

Ultimately the mini-store shipped as an MVP. After our Beta, it was clear it needed some updating. We needed a clear affordance to make the process more transparent. we tried a few different iterations of this and the one we landed on was a 3 part status indicator at the top of the page that's purpose was to give people a sense of place and a feeling of completion as they signed up.

<figure class="container__image container__break mb-1">
  <img src="/assets/images/review_c1.png" alt="An image of a header with three green arrows" />
  <figcaption class="mt-half center">
    <small>A UI in the mini-store to show people where they are in the process of creation and to launch a demo.</small>
  </figcaption>
</figure>

#### Social Sharing

One of the problems we wanted to tackle was reworking our social sharing workflow. Designing around the complications in sharing for native iOS apps (at the time) was an interesting problem. We ran a couple of modified design sprints around mobile sharing. Before we got into the sprint we set out some loose req's to make sure we were working toward a unified end. We set out one major people need and a couple of gotchas to plan for:

- As a person using this software I need to be able to share both to social media and in their timeline inside the App.
- We needed to design around a framework of extensibility. It's the only way to ensure the ability to add social media platforms when necessary.
- We have to live with the fact that we're not Instagram. We're going to have to send separate messages from separate fields.

<div class="container__images mb-1">
  <figure class="container__image">
    <img src="/assets/images/rm-wireframe.jpg" alt="Mobile Sharing sketch 1" />
    <figcaption class="mt-half center">
      <small>Mobile Sharing sketch 1</small>
    </figcaption>
  </figure>

  <figure class="container__image">
    <img src="/assets/images/rm-wireframe--2.jpg" alt="Mobile Sharing sketch 2" />
    <figcaption class="mt-half center">
      <small>Mobile Sharing sketch 2</small>
    </figcaption>
  </figure>
</div>

The person would need to select their social media platforms, write a main post and agree every time the post went to a new social outlet. The final screen is the success screen, the screen below is the “Would you like to send another update?” dialogue. This was a really complex workflow, but was the reality of sharing as we understood it at the time.
From there we thought a lot about the interaction. The next social media post sliding up from the bottom for example. we started fleshing this out a little more to hand off to engineering for some prototyping.

<figure class="container__image container__break mb-1">
  <img src="/assets/images/rm-social-sharing.jpg" alt="Social sharing comp" />
  <figcaption class="mt-half center">
    <small>A UI comp for Social sharing</small>
  </figcaption>
</figure>

#### In-App Coaching

During the course of my time at RaiseMore there was one feature I coveted more than any other. Based on feedback during the beta, it was the white whale for events-based fundraising. I loved the possibilities around in-app coaching and messaging. I loved the idea of our team leaders being able to insert content into someone's feed to encourage them or coach them. Our original idea was just that this would come in the form of a push notification. Push notifications turned out to be a technical limitation. As an alternative we looked into adding both automated messages and what it might look like to allow an admin to send messages from the admin dashboard.

Our first step was to define some types of messages that might be sent. Warning Alerts, Coaching, Reminders, Data Points. The possibilities of message types are nearly endless. We went through a few different types of message and thought about how it might look and feel. starting with the icons it might use.

<figure class="container__image mb-1">
  <img src="/assets/images/rm-messaging-assets.png" alt="Mobile Sharing sketch 2" alt="a picture of raisemore messaging icons" />
  <figcaption class="mt-half center">
    <small>raisemore messaging icons</small>
  </figcaption>
</figure>

There was an initial idea that floated around of using photos uploaded to the app as posts to help give a personalized feel to the notifications.

<div class="mb-1">
  <figure class="container__image container__image--small">
    <img src="/assets/images/rm-ask-comp.png" alt="Mobile Sharing sketch 2" alt="a picture of an early alert comp" />
    <figcaption class="mt-half center">
      <small>initial concept for the alert</small>
    </figcaption>
  </figure>
</div>

The implementation was more challenging than we were ready to take on at such an early stage. We opted to work with the icons and an integrated color-field that might be slightly different depending on the colors chosen in the app building process.

<figure class="container__image container__break ">
  <img src="/assets/images/rm-messaging-examples.png" alt="initial concept for the alert" />
  <figcaption class="mt-half center mb-1">
    <small>initial concept for the alert</small>
  </figcaption>
</figure>

This feature ended up being mostly aspirational because of some engineering limitations with the Ionic Framework at the time but was a fun excercise in thinking about our products' evolutions over time.

[![RaiseMore Product Walkthrough with CEO, CTO and Lead Engineer and some shots from our beta testing summit. ](/assets/images/rm-cover-img.png)](https://vimeo.com/200031428)
#### Click above to watch a RaiseMore Product Walkthrough with CEO, CTO and Lead Engineer and some shots from our beta testing summit.
