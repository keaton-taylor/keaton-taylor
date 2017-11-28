---
layout: raisemore
date:   2017-09-04 16:16:01 -0600
category: rm_secondary
title: "Social Sharing"
---

## Social Sharing

One of the problems we wanted to tackle was reworking our social sharing workflow. Designing around the complications in sharing for native iOS apps (at the time) was an interesting problem. We ran a couple of modified design sprints around mobile sharing. Before we got into the sprint we set out some loose req's to make sure we were working toward a unified end. We set out one major user need and a couple of gotchas to plan for:

- As a user I need to be able to share both to social media and in their timeline inside the App.
- We needed to design around a framework of extensibility. It's the only way to ensure the ability to add social media platforms when necessary.
- We have to live with the fact that we're not Instagram. We're going to have to send separate messages from separate form fields.

<div class="RaiseMore__image">
  <img class="RaiseMore__image p-1"  src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086066_rm-wireframe.jpg" alt="Mobile Sharing sketch 1" />

  <img class="RaiseMore__image p-1"  src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086059_rm-wireframe--2.jpg" alt="Mobile Sharing Sketch number 2" />
</div>

The user would need to select their social media platforms, write a main post and agree every time the post went to a new social outlet. The final screen is the success screen, the screen below is the “Would you like to send another update?” dialogue. This was a really complex workflow, but was the reality of sharing as we understood it at the time.

From there we thought a lot about the interaction. The next social media post sliding up from the bottom for example. we started fleshing this out a little more to hand off to engineering for some prototyping.
<div class="RaiseMore__image">
<img src="https://d2mxuefqeaa7sj.cloudfront.net/s_E6C2E1981A9640327110390FCA8823B3EFD888DDBE1E984574D91BEEACCC87E1_1506112086052_rm-social-sharing.jpg" alt="Social sharing comp" />
</div>
