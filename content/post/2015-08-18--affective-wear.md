---
categories:
- posts
date: 2015-08-18T00:00:00Z
summary: Katsutoshi Masai, one of my Master students had the idea to track facial
  expressions using low cost sensors in glasses. Quite nice work!
title: Affective Wear- Recognizing facial expressions
url: /2015/08/18/-affective-wear/
---

Katsutoshi Masai, one of my Master students had the idea to track facial expressions using low cost sensors in glasses. Quite nice work ;)
<!--more-->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9PMzpsDg518" frameborder="0" allowfullscreen></iframe>

Facial expressions are a powerful way for us to exchange information nonverbally. They can give us insights into how people feel and think. There are a lot of works related to facial expression detection in computer vision. However, most work focuses on camera-based systems installed in the environment. It is difficult to track for long hours. Moreover, user’s facial expression can be recognized from only a limited angle.
We present an eyewear type device that can detect facial expression. This eyewear can categorise various facial expression by measuring the distance between eyewear frame and the surface of a person’s face with photo reflective sensors. Recognizable states are as follows: neutral, angry （2 level） smile, laugh, sad,  surprise. With our method, an individual difference can be ignored by user-dependent training. There are several works that show wearable system that can recognize facial expression. Yet, these works focus on detecting only one specific facial expression (smiling). Our contribution is detecting various facial expression states. With our device, computing systems can tap into the rich set of information provided by nonverbal communication...



We have developed the AffectiveWear system to detect facial expressions (neutral, angry (2 level), smile, laugh, sad, surprised). This system includes 8 photo reflective sensors (SG-105), 160 - 270 ohm resistor for the LED and 62k ohm resistor for transistor. These sensors measure the distance between the eyewear and skin surface on face. This distance changes according to the movement of the facial muscles. We show the optimal placement in relation to the expressions of the photo reflective sensors on a glasses frame and the easy integration of the reflectors in the eyewear themselves. Three reflective sensors are used for detecting cheek movement, four for eyebrows/eyelid movement and one for a temple movement. Seven of them are integrated into from frame and one attached to right temple. The placement of the resistors is chosen to pick up facial changes in the action units related to the facial expressions we want to recognize [1]. We choose the following facial expressions: neutral, angry, smile, laugh, sadness and surprise. Photo reflective sensors are used for detecting distance change between the sensor and skin on face. We also implemented HMD type with 7 photo reflective sensors .

**AffectiveWear: Toward Recognizing Facial Expressions** Katsutoshi Masai, Yuta Sugiura, Masa Ogata, Katsuhiro Suzuki, Sho Shimamura, Kai Kunze, Masahiko Inami, Maki Sugimoto. Accepted at Siggraph Emerging Technologies 2015.
