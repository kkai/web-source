---
title: "HCI Deep Dive"
subtitle: "Using Generative AI for Audio Creation"
date: 2024-10-20T14:08:46+09:00
draft: false
---

{{< gallery caption-effect="fade" >}}
  {{< figure thumb="-thumb" link="/images/logo2.jpg" alt="" >}}
  {{< figure thumb="-thumb" link="/images/episode1.jpg" alt="" >}}
  {{< figure thumb="-thumb" link="/images/episode11.jpg" alt="" >}}
{{< /gallery >}}

I’ve been experimenting with the [Audio Overview](https://blog.google/technology/ai/notebooklm-audio-overviews/) of Google’s NotebookLM to create a podcast about Human-Computer Interaction (HCI), and I have to say, it’s surprisingly useful! Using their Audio Overview feature, I’ve uploaded several HCI publications, and NotebookLM has turned them into conversations.  

Additionally, I also summarized most of my [publications](https://kaikunze.de/publications/). Have a listen.

Google just announced that they allow to [customize the Audio Overviews](https://blog.google/technology/ai/notebooklm-update-october-2024/). I'm pretty excited about this feature, as the standard summarization is a bit too casual for me. Here is an example from the podcast without customization:

<iframe title="Linking Audience Physiology to Choreography" allowtransparency="true" height="150" width="100%" style="border: none; min-width: min(100%, 430px);height:150px;" scrolling="no" data-name="pb-iframe-player" src="https://www.podbean.com/player-v2/?from=embed&i=t6igx-16f1fba-pb&share=1&download=1&fonts=Arial&skin=1&font-color=auto&rtl=0&logo_link=episode_page&btn-skin=7&size=150" loading="lazy"></iframe>

Notice that the speakers use "like" and other rather informal language a lot. Also they like to finish each others sentences. It would be nice if one of the speakers could be the interviewer and the other the expert.

For the later podcast episodes I tried several customization prompts. Some were longer introducing the roles of the two speakers in more details. Yet, I found shorter ones to work better.
Listen to the difference, when prompting for "Use formal language. Don't use the word "like."
 
<iframe title="Linking Audience Physiology to Choreography" allowtransparency="true" height="150" width="100%" style="border: none; min-width: min(100%, 430px);height:150px;" scrolling="no" data-name="pb-iframe-player" src="https://www.podbean.com/player-v2/?i=e9byw-17119a0-pb&from=pb6admin&share=1&download=1&rtl=0&fonts=Arial&skin=1&font-color=auto&logo_link=episode_page&btn-skin=7" loading="lazy"></iframe>



I also started to look into some open-source tools to perform similar tasks and found [Podcastfy](https://github.com/souzatharsis/podcastfy). Brave new world for podcasters.

I'll continue experimenting. In the meantime you may want to listen to some [HCI Deep Dive Conversations](https://www.deep-hci.org).









