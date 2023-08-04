
---
title: "Eyewear Computing"
subtitle: "Mainstream with the Apple Vision Pro?"
image: images/eyewear-header.jpg
date: 2023-04-28T19:42:36+01:00
draft: false
---

{{< gallery caption-effect="fade" >}}
  {{< figure thumb="-thumb" link="/images/oma.jpg" alt="There are also applications of smart eyewear for older adults." >}}
  {{< figure thumb="-thumb" link="/images/seminar.jpg"  alt="Participants of the 2016 Dagstuhl Seminar on Eyewear Computing">}}
  {{< figure thumb="-thumb" link="/images/miraikan.jpg" alt="Public dissemination about Eyewear Computing at The National Museum of Emerging Science and Innovation, Miraikan, Tokyo 2017." >}}
{{< /gallery >}}

A research concept from 2016 might be in the spotlight in the next years,
as described and discussed in the [Dagstuhl Seminar 
"Eyewear Computing – Augmenting the Human with Head-mounted Wearable Assistants"](https://www.dagstuhl.de/16042).


With the advent of Apple Vision Pro, it seems timely to reflect on 
some of our earlier research directions. 
Eyewear Computing could go from an academic niche (e.g. [Eyewear Computing Workshops at UbiComp](https://dl.acm.org/doi/abs/10.1145/3460418.3479267)) to becoming mainstream in the next years, if Apple 
succeeds in establishing their platform. 
Yet, there are also a tremendous amount of challenges. In the long term smart eyewear needs 
to become more like regular glasses. 



Regular, analog glasses are already a great cognitive augment to us. 
If we put them on, we can see more clearly and, after a while, forget
that we even wear them. Yet, even after the invention of what is considered the first digital, programmable computer (the ENIAC) 78 years ago, our
digital tools are still lacking behind. PCs, smart phones and watches
are distracting us, they are not the "Invisible Computing" that was promised to us.

To enable digital augments, tools that seamlessly help us in everyday tasks,
the most critical limitations are no longer CPU speed, RAM, hard-drive space.
The most critical are our cognitive limitations: our attention span, memory, and 
other cognitive properties. To understand these better, activity recognition
for our mind is essential, towards [A Cognitive "Quantified Self"](https://www.imlab.jp/publication_data/1362/mco2013100105.pdf) or in other words Cognitive Activity Recognition.

As we are in an Artificial Intelligence (AI) revolution right now, it removes one
of the largest barriers for cognitive activity recognition: the reliable and correct
classification of cognitive states. Given just large enough datasets, the first
cognitive foundation models will emerge, similar to what we see today in foundation models for language prediction (OpenAI's ChatGPT, Meta's LLaMA) and for 
image generation (Dallee 2, Midjourney, Stable Diffusion).

{{< figure src="/images/eyewear-overview.jpg" title="Cognitive Activity Recognition based on Eyewear Computing" >}}

Yet, the question remains what would be a decent concept and platform to first gather all this data and second provide meaningful interactions taking cognitive states into
account. In terms of concept, [Eyewear Computing](https://www.dagstuhl.de/16042) seems to fit perfectly. As most of our senses are on the head, smart glasses could be
the perfect cognitive assistants, simultaneously sensing cognitive states and
providing cognitive aware interactions.

In terms of platforms, Google Glass was a first very interesting exploration
of the Eyewear Computing space. Implementing a simple [Blink detection](https://dl.acm.org/doi/pdf/10.1145/2582051.2582066), we can already receive some relevant
information regarding cognitive states. Blinking not only keeps the eye lubricated,
yet it's also related to cognitive tasks, might help to [disengage our attention](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3545766/). 

The next platform, we explored in the Eyewear Computing space is [J!NS MEME](https://jinsmeme.com). MEME is fascinating, as it's not a full-fledged computer compared to Google Glass. MEME is a lightweight glass (ca. 35 grams) and simple sensing device connected to a smartphone. It contains inertial motion sensors (accelerometer and gyroscope).
Additionally, 3 electrodes are embedded in the nose bridge. With these three electrodes one can recognize eye movements [Electrooculography](https://en.wikipedia.org/wiki/Electrooculography). These lightweight glasses enable a completely new 
[sensing and interaction space](https://dl.acm.org/doi/pdf/10.1145/2702613.2725449).
They can be used to track [alertness over the day](https://dl.acm.org/doi/pdf/10.1145/3290605.3300694). We can even use the electrodes to 
detect [subtle nose touching gestures](https://juyounglee.net/projects/itchynose).


Yet, each of these platforms had their limitations. For google glass, 
it didn't provide any sophisticated sensors for cognitive activity recognition and 
feedback was limited to rather small screen and bone-conducting audio on
one side only. J!NS MEME has no means to output information, interactions need to go over a secondary device (smartphone).

With the Advent Apple Vision Pro, we still know very little about the specifications.
Yet, from early feedback, the see-through optical display seems to be amazing with very little lag. In terms of sensing, it provides definitely camera based eye-tracking. The cameras are probably also used to enable facial expression tracking. I'm curious about the hardware setup of the, maybe the Vision Pro also contains some infra-red distance sensors. It's possible to detect the 8 universal facial expressions with relative simple [smart eyewear](https://dl.acm.org/doi/pdf/10.1145/3012941). 


 If Apple Vision Pro succeeds, it could usher in a renaissance for Eyewear Computing and a revolution in understanding our cognitive tasks and perfromance.



  

 

