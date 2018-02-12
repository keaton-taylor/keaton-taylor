---
layout: work
date:   2017-09-03 16:16:01 -0600
category: case_study
image: /assets/images/rm-post-image.png
title: "RaiseMore: Making Fundraising Social for Fun and (limited) Profit"
excerpt: "RaiseMore was a social fundraising platform that used teamwork and social interactions to maximize fundraising efforts. I was a product designer working on their web and mobile apps."
role: Product Designer
year: 2015-2016
platform: Web, Mobile
series: Case Studies
---

### In the Summer of 2015 I joined a social fundraising platform that used teamwork and social interactions to maximize fundraising efforts. In turn we used the aggregate data to help predict fundraising trends and success patterns.

The problem of making fundraising and nonprofit volunteering more fun and social is an extremely hard one. Fundraising is usually a solitary experience. You donate and you go about your business. At RaiseMore we wanted to make fundraising a team sport. How could we offer a competitive platform? How could we give leaders the power to coach team members based on performance & quantifiable metrics? We aimed to answer these questions and unfortunately the answer was sometimes, “We can’t.”

At RaiseMore we built a digital product suite that would give a lot of power to event-focused non-profit teams. Our system built semi-custom native apps through a customization UI and the Ionic framework. Once the mobile app was finished, people would be given access to a dashboard area to maintain their app and events. Because of the app store approval process we would show a UI in the dashboard giving tips and information about the process of the app going live over the course of a few days.

I came to RaiseMore hoping to make a difference. I cut my teeth working for NPO's like Art Feeds and the Hippo Valley Christian Mission, so the idea that I could help similar nonprofits be successful was incredibly exciting. Up to this point my experience was primarily with strictly web-based work, mostly on marketing sites. While at Blue Fish I worked on a few digital products for companies like Intel and Athlon Media Group and that added experience made me a good fit. I worked directly with engineers and our product manager to try and grok challenging problems like social sharing and in-app coaching.

### The MVP
Before our limited Beta release and test period we were on a time crunch to complete a couple of major features - finalizing our on-boarding flow and social sharing. Both of these were challenging because of the nature of our app. The on-boarding flow consisted of signing up and filling in information and then customizing a mobile app. It was not for the faint of heart and for the MVP our goal was to just try and make that process slightly more elegant. For social sharing -  we had to make some trade-offs because of the sandboxed nature of sharing externally vs. internally at the time. One of the tools we tried to use at the time was a kind-of Design Sprint to get ideas from every part of the organization and try to meld everything into a cohesive feature.


#### Design Sprints
As a distributed team, traditional Design Sprints presented a specific set of challenges. We had to make some changes to the process to fit our needs. None of us had much, if any, experience with Design Sprints. We had read a few blogs on the GV site and were essentially diving in and hoping for the best. The process we identified for ourselves was this:

- Define requirements
- Group Sketch exercise and critique
- Regroup and update requirements as needed
- Sketch exercise and critique
- Prototype feature for testing
- Project handoff for final design/engineering

We did this over the course of around a week. Definitely not the ideal system (Sorry Jake and Daniel). What this exposed inside our team though was that we didn’t have a good process for iteration. We were burning through tasks as a pretty high rate. The side effect of that speed was that issues were being exposed and backlogged, never to be seen again.

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

In the course of discussing the new onboarding flow we exposed a glaring experience flaw. There were no less than 4 places for a person to sign up and define credentials.

<figure class="container__image mb-2">
  <img src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086179_rm-entry-points.png" alt="image There are at least 4 portals that will drop you into a Sign-Up situation" />
  <figcaption class="mt-half center">
    <small>There are at least 4 portals that will drop you into a Sign-Up situation</small>
  </figcaption>
</figure>

Mapping out entry points and making them cohesive and contextually relevant was a task. To limit the disparity between potential entry points was the imperative here. We made our goal to “Capture the smallest amount of information possible” our true North.

<div class="container__images">
  <figure class="container__image">
    <img src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086030_rm-header-cta__modal.png" alt="image Header Call to action" />
    <figcaption class="mt-half center">
      <small>Header Call to action</small>
    </figcaption>
  </figure>

  <figure class="container__image">
    <img src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086022_rm-header-cta__modal-success.jpg" alt="image Header call to action success modal" />
    <figcaption class="mt-half center">
      <small>Header call to action success modal</small>
    </figcaption>
  </figure>
</div>

Once a person works through the actual signup we prompt them to go through our "mini-store" experience to start customizing their app experience.

<figure class="container__image">
  <img src="https://d2mxuefqeaa7sj.cloudfront.net/s_F311AE08451D62116DFFACCBDC7E009E2FF890EF15810A623D30F66D11798920_1517346138952_Screenshot+2018-01-30+15.02.02.png" alt="image After signing up, you’re invited to customize your app - which is released to the  app store after your subscription is confirmed through our signup UI." />
  <figcaption class="mt-half center">
    <small>After signing up, you’re invited to customize your app - which is released to the  app store after your subscription is confirmed through our signup UI.</small>
  </figcaption>
</figure>

Ultimately the mini-store experience shipped as an MVP. After our Beta, it was clear it needed some updating. We needed a clear affordance to make the process more transparent. we tried a few different iterations of this and the one we landed on was a 3 part status indicator at the top of the page that's purpose was to give people a sense of place and a feeling of completion as they signed up.

<figure class="container__image">
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

<div class="container__images">
  <figure class="container__image">
    <img src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086066_rm-wireframe.jpg" alt="Mobile Sharing sketch 1" />
    <figcaption class="mt-half center">
      <small>Mobile Sharing sketch 1</small>
    </figcaption>
  </figure>

  <figure class="container__image">
    <img src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086059_rm-wireframe--2.jpg" alt="Mobile Sharing sketch 2" />
    <figcaption class="mt-half center">
      <small>Mobile Sharing sketch 2</small>
    </figcaption>
  </figure>
</div>

The person would need to select their social media platforms, write a main post and agree every time the post went to a new social outlet. The final screen is the success screen, the screen below is the “Would you like to send another update?” dialogue. This was a really complex workflow, but was the reality of sharing as we understood it at the time.
From there we thought a lot about the interaction. The next social media post sliding up from the bottom for example. we started fleshing this out a little more to hand off to engineering for some prototyping.

![Social sharing comp](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086052_rm-social-sharing.jpg)

### The RaiseMore Beta

In September of 2015, We ran a two day feedback summit in Oklahoma City with the entire RaiseMore team. We went through 4 feedback sessions. The rounds of one-on-one interaction with real people was incredibly helpful. The Group discussions On Day 3 discussing the product roadmap was very insightful. The weekend would inform a lot of the next several months of product features and iteration.
Here are a Few Takeaways*:

- Up to 80% of our users would be using Windows computers. Up to 30% of those might use touchscreen technology in some capacity.
- Our collective use of Apple hardware caused us to miss some glaring usability issues. We missed hover states, color inconsistencies and responsive issues on smaller screens. We missed these things because we were seeing the product through our tech focused lens.
- Visual design inside the dashboard caused a lot of confusion. Defaulting to ghost buttons and a flat UI pattern was often and easily missed by our testers.
- Our internal bias toward aesthetics vs. experience was exposed. This surfaced some internal frustration on our team between UX and Visual design imperatives. The dialogue we had here was tense but positive. If people can't accomplish the product tasks, we will have a hard time making them customers.
- The things we thought were going to be super important were a lot less important. One of our assumptions was that the person using the app would start at the feed page. This would allow people to see the status and relevant data points of all their teammates. During testing, our groups let us know they would opt for a view based on the health of their event(s) instead.
- An interesting pattern emerged here. The money raised is important but not on such a granular level. The overall event health was a more desirable metric. From there our partners could dig deeper and address individual coaching needs. There was a very "leader-leader" structure to the way our partners managed events.

If it seems like some of this was inordinately surprising - it's because it genuinely was. For most of this team there was a feeling that we really had our finger on the pulse of the industry. As it turned out many on our team were shocked.


#### In-App Coaching

During the course of my time at RaiseMore there was one feature I coveted more than any other. Based on feedback during the beta, it was the white whale for events-based fundraising. I loved the possibilities around in-app coaching and messaging. I loved the idea of our team leaders being able to insert content into someone's feed to encourage them or coach them. Our original idea was just that this would come in the form of a push notification. Push notifications turned out to be a technical limitation. As an alternative we looked into adding both automated messages and what it might look like to allow an admin to send messages from the admin dashboard.

Our first step was to define some types of messages that might be sent. Warning Alerts, Coaching, Reminders, Data Points. The possibilities of message types are nearly endless. We went through a few different types of message and thought about how it might look and feel. starting with the icons it might use.

<figure class="container__image">
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

![initial concept for the alert](/assets/images/rm-messaging-examples.png)


This feature ended up being mostly aspirational because of some engineering limitations with the Ionic Framework at the time but was a fun excercise in thinking about our products' evolutions over time.


<hr>
*Numbers extrapolated to identify total user-base from user-base who was able to attend the beta retreat.
