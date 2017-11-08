---
layout: work
title: Keaton Taylor | Product Designer | RaiseMore
category: "work"
---
{% include head.html %}
  {% include header.html %}
  
RaiseMore

![](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086095_rm-cover-img.png)


In the Summer of 2015 I joined a friend at a startup he had been working at as lead front end engineer. He asked me to join RaiseMore as a long term contractor to sort out some Product and Experience issues. RaiseMore was a platform that worked to help non-profits raise more money through better data collection and more engaged participants. RaiseMore included a marketing website, a dashboard and mobile apps built on the Ionic framework. I had the pleasure of taking part in some genuinely exciting experiences during my time with RaiseMore, from in-person user testing sessions  to leading remote Design Sprints.

RaiseMore Beta

In September of 2016, I was part of a two day user feedback summit in Oklahoma City with the entire RaiseMore team. We went through 4 sessions that included one-on-one interactions, speaking to users as they used our products and group discussions afterward collecting feedback on the products and our roadmap.

Here are a Few Takeaways*:

- ~80% of our users would be using Windows computers. Up to 30% of those might use touchscreen technology in some capacity.
  Our collective use of Apple hardware caused us to miss some glaring usability issues. We missed hover states, color inconsistencies and responsive issues on smaller screens. We missed these things because we were seeing the product through our tech focused lens.


- Visual design inside the dashboard caused a lot of confusion. The design team had defaulted to using a very modern, flat, knockout-button UI pattern and this was often and easily missed by our testers.
  Our internal bias toward design instead of toward the user was flayed open and on display for all to see. This was particularly powerful because it exposed some internal frustration inside our team with visual design’s tension vs. experience design.


- The things we thought were going to be super important were a lot less important. One of our assumptions was that the user would start in the app from the feed page. This would allow the user to see the status and relevant data points of all their teammates. During testing, our groups let us know they would opt for a view based on the health of their event(s) instead.
  An interesting pattern emerged here, our testing partners were very event focused and used a very leader-leader style of event participant management. The money raised is important but not on such a granular level. The overall event health was a more desirable metric. From there our partners could dig deeper and address individual coaching needs among fundraising teams and team members.

Design Sprints

One of our most interesting sprints was around reworking our social sharing workflow. As a remote team, traditional Design Sprints presented a specific set of challenges. We had to make some changes to the process to fit our needs:

- Define requirements
- Group Sketch exercise and critique
- Regroup and update requirements as needed
- Sketch exercise and critique
- Prototype feature for testing
- Project handoff for final design/engineering

We did this over the course of around a week. Definitely not the ideal system (Sorry Jake and Daniel). What this exposed inside our team though was that we really didn’t have a good process for iteration. We were burning through tasks as a pretty high rate but the side effect was that issues were being exposed and backlogged, ne’er to be seen again, even upon seeming feature completion in other areas.

Social Sharing

One of the problems we wanted to tackle was designing around the issues in sharing for native iOS apps. We ran our design sprint around mobile sharing and came up with some guidelines:

- Users need to be able to share both to social media and in their timeline inside the App.
- We needed to design around a framework of extensibility. It's the only way to ensure the ability to add social media platforms when necessary.
- We have to live with the fact that we're not Instagram. We're going to have to send separate messages from separate form fields.


![Mobile Sharing Preliminary Sketch](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086066_rm-wireframe.jpg)
![Mobile Sharing Second Sketch](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086059_rm-wireframe--2.jpg)


This was my first sketch, The idea here was essentially that the user would select their social media platforms wrote a main post and had to agree every time it went to a new social outlet. The final screen is the success screen, while the screen below is the "Would you like to send another update?" dialogue.

The second sketch refined my first thought process by showing that the dialogues would slide up as they were ready to share.

This final mock was to give another team member a more fleshed out view of what I was thinking. In the end elements of this initial design were worked into the final product, but another team member took point on the design.

![](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086052_rm-social-sharing.jpg)

User OnBoarding

Another of our Sprints aimed to rework login processes and onboarding processes. One of the glaring issues was the technical debt left over from our Bootstrap MVP. During this Sprint we used more time than we expected walking through the signup process in the specific context of data collection and mobile to `www.` changes.

Our goals were:

- Make signup as easy as possible.
- Capture the smallest possible amount of information:
  - Organization - We need this to organize Teams inside the mobile app based on the Administrator's and Team Leader's org affiliation.
  - Name - Email - Password •
-  Immediately push users into an action after signup.

One piece of useful information we gleaned from these meetings was that in total there were up to 4 places in our product where a user could sign up and define a password.

![There are at least 4 portals that will drop you into a Sign-Up situation. ](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086179_rm-entry-points.png)


Mapping out our entry points and trying to make sure our entry points are cohesive but also tuned to the specific needs of that entry point was incredibly important. To limit the disparity between potential login cases we used our goal to “Capture the smallest possible amount of information” as a true north. At this time we didn’t have a service like Auth0 to log in with so we went with manual fields and allowed a user to get into the mini-store to build apps straight away.

![](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086030_rm-header-cta__modal.png)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086022_rm-header-cta__modal-success.jpg)

Requesting Access to View

One final thing was is born of a slightly different use-case. This involves a user being sent a preview of the mobile app or data within the product and being denied access because of a lack of an account. The suggested and adopted solution became giving organization admins the ability to create user accounts and login credentials.


![](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086047_rm-request-access-modal.jpg)
![](https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086038_rm-request-access-modal---success.jpg)


A quick dialogue modal letting the user know that they are locked out until they request access puts up road blocks for non-users but protects the data from unwanted viewers through email-based permissions.


What I Learned

Working on the team at RaiseMore was a delight. The entire team was dedicated to making really good software and always wanted to hear critical feedback as soon as possible. My biggest takeaway - one that still shapes my work a couple years on - is the focus on the real live people who use the product. Software lives and dies by adoption and embedding with the people who have adopted or could adopt your technology is incredibly important. We’re really just making assumptions until we find the pain points of real people who interact with what you’ve built.


----------

*Numbers extrapolated to identify total user base from user base who was able to attend the beta retreat.
