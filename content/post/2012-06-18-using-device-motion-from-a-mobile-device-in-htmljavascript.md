---
title: Device Motion in Html/Javascript
subtitle: A simple demo
tags: ["hacking", "demo"]
date: 2012-06-18
---

This project demonstrates real-time accelerometer data streaming from mobile devices using WebSocket technology. The system combines a Node.js web server with a Processing.org visualization interface. When a mobile device connects to the server through its browser, the visualization displays a distinctive red cube among randomly positioned background cubes. The cube features a dynamic transparent aura that responds to the intensity of the device's movement - the more vigorously you shake your phone, the more pronounced the visual effect becomes.

The implementation relies purely on HTML and JavaScript, making it both lightweight and accessible. This creates an intuitive bridge between physical movement and digital visualization, effectively demonstrating the potential of mobile sensors in interactive web applications.


{{< vimeo id="45626605" title="Using Device Motion" >}}

[Visualization based on mobile phone data](http://vimeo.com/45626605) from [Kai Kunze](http://vimeo.com/user8093378).

The complete source code is available on my GitHub repository: [devicemotion-demo](https://github.com/kkai/devicemotion-demo)
This project builds upon several excellent resources:

- A Node.js WebSocket tutorial demonstrating chat server implementation by Martin Sikora: [a simple chat server node.js tutorial](http://martinsikora.com/nodejs-and-websocket-simple-chat-tutorial)
- Paul Hayes' guide on creating animated 3D cubes using CSS3 transforms: [3d css cube](http://www.paulrhayes.com/2009-07/animated-css3-cube-interface-using-3d-transforms/)
- The "3D Cube World" Processing sketch that inspired the visualization: [3d cube world](http://openprocessing.org/sketch/19216)

These resources provided the foundational techniques that were combined and adapted to create this interactive demonstration.









