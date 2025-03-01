---
title: Fixing the XR buying experience
author: Rayan Saleh
category:
layout: post
---

The XR (AR, VR, MR) buying experience is broken. The process feels a little like buying a car without taking it for a test-drive first. For first-time-XR-buyers, it’s like buying a car having never even been in one. Whilst I knew the key specs before buying my first headset, I had no way of knowing whether the 90° field-of-view was enough, what the actual image looked like, or how it would compare to other devices. I suspect this is going to be a major blocker to mass user adoption (after XR’s largely gimmicky use-cases) and I’m surprised there hasn’t been much discussion on solving it.

The problem compounds every year as spec lists grow. Even in the best case, when a user understands, has prioritised and compared specs across devices, they still miss key nuances that you can only spot having compared the headsets first-hand. The XR comparison site [vr-compare.com](https://vr-compare.com/compare?h1=GeZ01ojF8&h2=ZhHpFl6JF) displays the problem well. Though it does an amazing job of showcasing the specs in a clear and ordered way, it isn’t obvious how the actual visual experience of the headsets differ.

By far the most misleading part of the buying experience, however, is the blatant false advertising used by headset companies in their promotional content.


<figure>
  <img src="/assets/images/ezgif-5-bf6ec19f63.gif" style="width:100%">
  <figcaption>Promo video from the Hololens <a href="https://www.microsoft.com/en-us/hololens">homepage</a>. No ‘real’ demo shown.</figcaption>
</figure>

<figure>
  <img src="/assets/images/kguttag.png" style="width:100%">
  <figcaption>Shot-through <a href="https://kguttag.com/2019/12/18/hololens-2-not-a-pretty-picture/">images</a> showing what HL2 users actually see.</figcaption>
</figure>

<figure>
  <img src="/assets/images/ezgif-5-939f735720.gif" style="width:100%">
  <figcaption>Tilt-five <a href="https://www.reddit.com/r/augmentedreality/comments/uhiply/tilt_five_adding_new_experiences_to_system_they/">video</a> showcasing high-contrast 3D images in a well-lit room.</figcaption>
</figure>

<figure>
  <img src="/assets/images/clipboardtilt.png" style="width:100%">
  <figcaption>Shot-through <a href="https://www.youtube.com/watch?v=lRGHBtshVEo">video</a> in dark room.</figcaption>
</figure>

<figure>
  <img src="/assets/images/ezgif-5-0d4b5a2fe3.gif" style="width:100%">
  <figcaption>Quest promo <a href="https://www.youtube.com/watch?v=60yP8f5E-B4">video</a> showing full FoV and near-eye-level resolution.</figcaption>
</figure>


<figure>
  <img src="/assets/images/THROUGH_THE_LENSES__Quest_2_vs_Quest_1.gif" style="width:100%">
  <figcaption>Shot-through <a href="https://www.youtube.com/watch?v=2FH4iIrY5LU">video</a> on the quest.</figcaption>
</figure>



Now I know what you’re thinking: no one *actually* believes this is how it’ll look irl. Companies will also argue that the content isn’t meant to represent what the actual user experience is like - that it’s just a way of showcasing the high-level potential of the tech. But, if no footage of the real user experience exists (as is true in most cases), users use the promotional content as the de facto representation of the true experience. 

Whats more, once a few XR companies start doing this, it becomes the game-theory-optimal strategy for the rest to follow suit (or risk getting left behind). This is how it became default marketing practice. I think the failure for the industry to ‘live up to its hype’ can be mostly accredited to this. 

Other consumer electronics, like laptops and smartphones, don’t seem to have as much of a problem with this and I think its because they have more obvious and clearly-visible features that are harder to embellish. They’re also relatively mature industries with clear user expectations and a stagnation of novel features.

XR headsets, by their nature, also have more ergonomic considerations than other consumer electronics like inter-pupillary distances, head size and shape, hair and whether you wear makeup, which makes it even more difficult to compare designs based purely off spec sheets. 

### The Solution

Whilst there is no silver bullet to solving all of the problems at once, I think there are things you can do when buying a headset to make your life easier and, crucially, things the industry can implement to improve the experience as a whole.

The first rule goes without saying: never trust the promotional videos or images released by companies to depict the real user experience. Even seemingly realistic footage is usually shot in very particular (and unrealistic) circumstances to greatly improve the end result.

Second, whilst [vr-compare.com](https://vr-compare.com/) and [others](https://kguttag.com/) are doing the industry a big favour by democratising knowledge, I think it’s about time we had a fair-standardised-visual-online-comparison tool to be able to quickly and accurately compare the real visual experience across devices. People have already started to hack something like this together and I think the accuracy and usefulness of these tools can be 10X’d [^1]. You’d needs to be able to compare key parameters like: resolution, refresh rate, FOV, contrast, brightness, colour uniformity, transmissibility as well as visual artefacts like god rays. In an ideal world, we’d be able to accurately represent the experience programmatically (probably using something like WebGL to compare FoV and ergonomics), but I think the only way you can get a true representation is by using a camera setup as a proxy for the eye. Though logistically cumbersome, it’s completely doable.

For the features that cannot be weighed up purely through online research (like comfort, individual physical differences, long-term use and ergonomic preference), the industry needs to introduce more pro-consumer try-before-you-buy options. This is especially important for newcomers to XR that perceive a much higher risk to the first-time purchase. Implementations can range from easy online trials to physical stores, which we’re [already seeing](https://www.theguardian.com/technology/2022/apr/26/meta-store-shop-california-metaverse-vr) pop-up. 

Ultimately, fixing the XR buying experience is in the interests of everyone in the industry and I’m hopeful that, as user adoption grows, the ease and reduction in perceived risk to buying a device will grow in tandem.



![](https://sherlock-holm.es/stories/html/pictures/prio-1.png)


[^1]: Tyriel Wood’s Through The Lens series and Karl Guttag’s test patterns.