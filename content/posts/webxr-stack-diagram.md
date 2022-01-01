---
title: "Webxr Stack Diagram"
date: 2021-12-03T06:43:44-07:00
draft: false
---

I am working on an [Intro to WebXR presentation for the Phoenix VR Meetup group](https://www.meetup.com/Phoenix-VR-For-Good-Meetup/events/282439401/).
As part of this I've been trying to make a diagram of the WebXR technology
stack.  These sorts of things are always oversimplifications.  With feedback
from several people on the WebXR Discord, I was able to come up with a decent
diagram which is shown below.

![WebXR Technology Stack](/webxr-stack-v1.png "WebXR Technology Stack")

This diagram is split roughly into the blue/green "Application Layer", the
orange "Browser Layer" and the red "Hardware Layer" at the bottom.  The
WebGL and WebXR boxes are the "new" APIs that browsers have implemented
which provide access to the relevant GPU/XR hardware.  Of course Javascript
and WASM are both browser APIs, but I omit them since, despite their importance,
they aren't the new enabling technologies.

The main point of this post is not only to share the diagram but to also share
the [Keynote Source](/WebXR-Presentation.key) (sha256: `50b6d21678b4987e262af2691e27520889d3ac8db508c442c5273f76010c002e`).
My choice of "Application Level" technologies was fairly arbitrary and people
might want to insert or replace their own things in the diagram.

Many thanks to the folks on the WebXR Discord who provided feedback on my
iterations.  The first of which **cough** completely omitted the WebXR parts.
