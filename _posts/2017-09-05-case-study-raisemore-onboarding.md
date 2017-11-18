---
layout: raisemore
date:   2017-09-05 16:16:01 -0600
category: rm_secondary
title: "User Onboarding"
---

## User Onboarding
Onboarding is hard. Reworking the general login process was an imperative. One of the glaring issues was the technical debt left over from our Bootstrap MVP. During this Sprint we used more time than we  expected walking through the signup process. The conundrum we spent the most time on was the amount of data we needed to collect. Where is the line between too much and not enough? We weren't sure. In hindsight what we were asking for became a barrier to entry.

Our goals for the update were:

- Make signup as easy as possible.
- Capture the smallest possible amount of information:
  - Organization - We need this to organize Teams inside the mobile app based on the Administrator's and Team Leader's org affiliation.
  - Name
  - Email
  - Password
-  Immediately push users into an action after signup.

In the course of discussing the new onboarding flow we exposed a glaring experience flaw. There were no less than 4 places for a person to sign up and define credentials.

<div class="RaiseMore__image mb-1">  
<img src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086179_rm-entry-points.png" alt="There are at least 4 portals that will drop you into a Sign-Up situation. " />
</div>

Mapping out entry points and making them cohesive and contextually relevant was a task. To limit the disparity between potential entry points was the imperative here. We made our goal to “Capture the smallest amount of  information possible” our true North.

<div class="RaiseMore__image">
  <img class="RaiseMore__image p-1"  src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086030_rm-header-cta__modal.png" alt="Header Call to action" />

  <img class="RaiseMore__image p-1"  src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086022_rm-header-cta__modal-success.jpg" alt="Header call to action success modal" />
</div>
