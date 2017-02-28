---
layout: work
title:  "RaiseMore"
date:   2017-01-01 09:13:10 -0500
categories: work
image: assets/images/rm-cover-img.png
---

![Design Sprint Workflow Sketches for Social Sharing](/assets/images/rm-cover-img.png)

Summer of 2015 I joined a friend at his new startup, RaiseMore as a long term contractor to sort out some UI/UX issues. RaiseMore helped non-profits raise more money through better data collection and engaged participants. RaiseMore includes a website, a web based dashboard and mobile apps built on Ionic. I went into it with a great amount of excitement. 

I had the pleasure of taking part in some exciting exercises from user tests to leading remote design Sprints.

## RaiseMore Beta

September 15-16 of 2016, I was part of a 2 day user feedback summit in Oklahoma City with the entire RaiseMore team. We went through 4 sessions of feedback on 3 aspects of the product and our product roadmap. 
<br/>


### Here are a few takeaways*:

~80% of our users would be using Windows computers. Up to 30% of those might be touchscreen Windows laptops and workstations.
Our collective use of Apple hardware caused us to miss some glaring usability issues. We missed hover states, color inconsistencies and responsive issues on smaller screens. We missed these things because we were seeing the product through our tech focused lens. 

Our calls to action inside the dashboard were not very clear, especially on the status page. 
The Status Page is the first page a user lands on in the Dashboard. To confirm they are using the product, the user has to go through a few steps. We did not think those through as calls to action in the first iteration of the product. 

The things we thought were going to be super important are a lot less important. 
One of our assumptions was that users would start in the app from the feed page. This would allow the user to see the status of all their teammates. During testing, our groups let us know they would opt for a view based on the health of their event(s) instead. This was one of the many things we figured out that we were wrong about and that was incredibly exciting.

Mobile Sharing is Hard
A major feature in the mobile app was the ability to share to elicit donations. We got there but it wasn't easy. Sharing could happen in-app or could be shared to a social media platform. Building a seamless and good looking sharing option is not easy. 


## Design Sprints
One of our most interesting sprints was around reworking our social sharing workflow. As a remote team, traditional Design Sprints presented a specific set of challenges. We had to make some changes to the process to fit our needs:
Define requirements
Group Sketch exercise and critique
Regroup and update requirements as needed
Sketch exercise and critique
Prototype feature for testing
Project handoff for final design/engineering
We did this over the course of around a week. Definitely not the ideal system (Sorry Jake and Daniel) 


## Social Share
One of the issues we wanted to tackle was designing around the issues in sharing for the mobile app. We ran our design sprint around this and came up with some guidelines: 

• Users need to be able to share both to social media and in their timeline inside the App. 

• We needed to design around a framework of extensibility. It's the only way to ensure the ability to add social media platforms when necessary. 

• We have to live with the fact that we're not Instagram. We're going to have to send separate messages from separate form fields. 

<div class="PostEntry__img">
  <figure class="three"><img src="/assets/images/rm-wireframe.jpg">
  <figcaption>This was my first sketch, The idea here was essentially that the user would select their social media platforms wrote a main post and had to agree every time it went to a new social outlet. The final screen is the success screen, while the screen below is the "Would you like to send another update?" dialogue.</figcaption></figure>
  
  <figure class="three"><img src="/assets/images/rm-wireframe--2.jpg"><figcaption>My second sketch refined my first thought process by showing that the dialogues would slide up as they were ready to share.</figcaption></figure>

  <figure class="three"><img src="/assets/images/rm-social-sharing.jpg"><figcaption>This final mock was to give another team member a more fleshed out view of what I was thinking. In the end elements of this initial design were worked into the final product, but another team member took point on the design.</figcaption></figure>
</div>

## User OnBoarding
Another of our Sprints aimed to rework login processes and onboarding processes. One of the glaring issues was the technical debt left over from our Bootstrap MVP. During this Sprint we used more time than we expected walking through the signup process in the specific context of data collection and mobile to `www.` changes. 

Our goals were obvious:
• Make signup as easy as possible.
• Capture the smallest possible amount of information:
    - Organization - We need this to organize Teams inside the mobile app based on the Administrator's and Team Leader's org affiliation.
    - Name 
    - Email
    - Password
• Immediately push users into an action after signup.

To keep us on track to sort out some of these ideas we put together three simple personas based on users from our beta.

<div class="PostEntry__img">
  <figure class="three"><img src="/assets/images/admin-persona.png"><figcaption></figcaption></figure>
  <figure class="three"><img src="/assets/images/noob-persona.png"><figcaption></figcaption></figure>
  <figure class="three"><img src="/assets/images/exec-persona.jpg"><figcaption></figcaption></figure>
</div>

One piece of useful information we gleaned from these meetings was that in total there were up to 4 places in our product where a user could potentially sign up and define a password. 

<div class="PostEntry__img">
  <figure class="one">
    <img src="/assets/images/entry-points.png">
    <figcaption>Mapping out our entry points. Trying to make sure our entry points are cohesive but also tuned to the specific needs of that user, at that entry point. </figcaption>
  </figure>
</div>

This meant we had to create a cohesive and strategic plan for the three key user entry points as well as planning for one edge case. We also had to to think through changing the "Request a Demo" call to action on our home page to a more generic login/signup Call to Action. 

## Signing Up from Various Places
<div class="PostEntry__img">
  <figure class="two"><img src="/assets/images/header-cta__modal.png"><figcaption>Used in the process as guidance on how much data to collect and where.</figcaption></figure>
  <figure class="two"><img src="/assets/images/header-cta__modal-success.jpg"><figcaption>An early mock of how we might confirm success for a signup submission.</figcaption></figure>
</div>

## Requesting Access to View 
This is born of a slightly different use-case. This involves a user being sent a preview of the mobile app or data within the product and being denied access because of a lack of an account. The suggested and adopted solution became giving organization admins the ability to create user accounts and login credentials.

<div class="PostEntry__img">
  <figure class="two"><img src="/assets/images/request-access-modal.jpg"><figcaption>A quick dialogue modal letting the user know that they are locked out until they request access.</figcaption></figure>
  <figure class="two"><img src="/assets/images/request-access-modal---success.jpg"><figcaption>Aaaaaand the success message.</figcaption></figure>
</div>



_______________________________________________

 *Numbers extrapolated to identify total user base from user base who was able to attend the beta retreat.
