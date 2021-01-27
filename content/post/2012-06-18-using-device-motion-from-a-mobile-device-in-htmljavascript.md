---
date: 2012-06-18
title: Device Motion in Html/Javascript
subtitle: A simple demo
tags: ["hacking", "demo"]
---

A while ago, I built a simple demonstration on how to stream accelerometer data from a mobile device over websockets to a server just using html and javascript. It consists of a nodejs web server and a processing.org visualization. As soon as a mobile browser connects to the server a new red
cube is shown on the screen (placed between randomly generated cubes). 
The transparent area around the cube changes depending on how strong
one shakes the phone.


{{< vimeo id="45626605" title="Using Device Motion" >}}

[Visualization based on mobile phone data](http://vimeo.com/45626605) from [Kai Kunze](http://vimeo.com/user8093378).


You can get the code from my [github page](https://github.com/kkai/devicemotion-demo)

It's based on these tutorials and sample code:

[a simple chat server node.js tutorial](http://martinsikora.com/nodejs-and-websocket-simple-chat-tutorial)

[3d css cube](http://www.paulrhayes.com/2009-07/animated-css3-cube-interface-using-3d-transforms/)

[3d cube world](http://openprocessing.org/sketch/19216)




