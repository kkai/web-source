---
categories:
- posts
date: 2013-12-22T00:00:00Z
summary: So I got my hands on another Glass device and can now play with it a bit
  longer.
tagline: how to root, update the firmware and enhance privacy
tags:
- glass
title: Hacking Glass
url: /2013/12/22/hacking-glass/
---

<p class="lead">
So I got my hands on another Glass device and can now
play with it a bit longer.
</p>

Disclaimer: Rooting and flashing your device voids your warranty and can brick your Glass. Also you won't receive OTA updates afterwards.
This is not an instruction manual. I just use it as 
a scratch pad to give a record what I did and
what worked for me. The commands below will erase all data on your device. Proceed at your own risk.


##Rooting and Flashing Images##
To get root follow the instructions from Google.
Unfortunately, the fastboot under Mac OS does not work.
I could use a virtual machine on my Mac with ubuntu
to get root and flash images.

    adb devices
    adb reboot-bootloader
    fastboot devices

    fastboot oem unlock

I needed to execute the last command twice. The first time
it just asked me if I was sure if I want to void my 
warranty etc.

Next I flashed the boot image from the [Glass developer page]().

    fastboot flash boot boot.img
    fastboot reboot
    adb root
    adb shell


If you want to update to a new OTA (in my case XE12) and
rooted your device,
you can download the zip with all necessary images from
Google. It's cool that they support rooting and
flashing (even if it voids your warranty).

    fastboot flash boot boot.img
    fastboot flash system system.img
    fastboot flash recovery recovery.img
    fastboot flash userdata userdata.img
    fastboot erase cache

##Reading out the Proximity Sensor##
I'm most interested in accessing the proximity
sensor facing the eye. So thanks to Philip Scholl's and
Shoya's help, I was able to do it.
The device is under 

    adb root
    adb shell
    > cat /sys/bus/i2c/devices/4-0035/proxraw

Gives back one raw proximity value from 
the sensor. Unfortunately without timestamp.
If you want to read out the proximity
data from Android Apps etc. you need to change
the access rights.

    >chmod 664 /sys/bus/i2c/devices/4-0035/proxraw


##Privacy Enhancement##

As I will be visiting the [Chaos Communication Congress]()
next weekend, I wanted to "privacy enhance" GLASS
for the event. I want to wear Glass but don't
really need the camera functionality.

So I used my [3Doodler](http://www.the3doodler.com) to make a simple attachment to block the camera of.

![Doodler](/imgs/doodler.jpg)

The tricky part is that the light sensor for adjusting
screen brightness is directly under the camera.
If it's blocked the screen will be very dark.
Here's the "privacy enhanced" Google Glass version.

![Glass Enhanced](/imgs/glass_p.jpg)

and a picture taken by it. It's not completely black
due to the issue with the light sensor, yet I 
think it's a start ;)

![Glass Enhanced](/imgs/glass_p2.jpg)

Here is the very [basic stencil](/files/glass.stencil.pdf) I used to build the attachment.


