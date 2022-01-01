---
title: "The Missing Link to the Metaverse"
date: 2021-10-28T07:30:00-07:00
draft: false
---

Last week [Tony Parisi](https://twitter.com/auradeluxe) shared the 
[Seven Rules of the Metaverse](https://medium.com/meta-verses/the-seven-rules-of-the-metaverse-7d4e06fa864c)
which [Kent Bye (host of the Voices of VR Podcast)](https://twitter.com/kentbye/status/1452047797394440194)
endorsed as ["Tony Parisi's Metaverse Manifesto"](https://voicesofvr.com/parisis-metaverse-manifesto-unpacking-his-seven-rules-for-the-metaverse/).

These seven rules and the entire manifesto really resonated with me and bear
repeating here.

* Rule #1. There is only one Metaverse.
* Rule #2: The Metaverse is for everyone.
* Rule #3: Nobody controls the Metaverse.
* Rule #4: The Metaverse is open.
* Rule #5: The Metaverse is hardware-independent.
* Rule #6: The Metaverse is a Network.
* Rule #7: The Metaverse is the Internet.

## The Problem

Inspired, I threw together some [A-Frame](https://aframe.io/)
code, donned my headset, eager to leap from page to page, but alas there was
sadness in my virtual land.  It seems that the state of link traversal in
WebXR is no better today than it was in 2017 when I first picked up my headset.
**When following a link between two web pages in "vr mode" the user is kicked
out of "vr mode" to see the 2D browser window and URL bar.  This is bad, how
do we fix this missing link?**

Immersive link traversal seems like such a foundational issue that I was surprised
to see that it hadn't been resolved in four years.  Links form the foundation of
the Web and the Web, in some form or another, is the foundation of of the
Metaverse.  Quoting Tony here:

> The Metaverse is the Internet, and the Internet the foundation upon which the Metaverse will be built.

If you want to see what I mean and you have a VR headset, put it on, open a
browser and open this link to the A-Frame link traversal demo:

https://aframe.io/aframe/examples/showcase/link-traversal/

Now if you click on one of the circles, you will go to the new link, but pop
out to the 2D view.  This tends to be slightly more graceful on Firefox Reality
than on the Oculus browser on the Quest 2, but still a terrible experience.

## The Current Status

I asked about this on the A-Frame slack channel and someone was kind enough to
point me to a W3C working group and the following resources:

* https://immersive-web.github.io/
* https://github.com/immersive-web/navigation
* [Ada Rose Cannon explaining Navigation (YouTube)](https://www.youtube.com/watch?v=jzIMQfp47zw)

I can appreciate the security issues here and the need to proceed with caution.
Having listened to Kent Bye's Voices of VR pod cast quite a bit, if nothing else,
I have gained an appreciation for the trust that's being placed in the creators
of immersive experiences.  But surely there are options to move forward.

I also appreciate that the big players in XR have been busy building the
hardware and software foundations of XR.  Their successes have become obvious
and their ambitions to scale to broader audiences is becoming clear.  **I would
argue that solving this one thing will result in a boom of user created
content that will drive demand for your platforms.**  Sure, you won't control
that content, but as Tony points out that is an inevitability anyway.

## Solutions

I am no where close to the best person to suggest solutions but I will throw out
a stop gap solution anyway.  This suggestion at least removes some of the
friction and provides a tiny bit of warning to the user.

**Add a setting that allows browser users to enable immersive link traversal
mode.  When in this mode, display a floating red exclamation point in the
bottom right of the users field of view as a warning.**

That's it.  Simple, not a great solution or long term solution.  Hopefully
we don't up browsing the Metaverse with little red exclamation points for the
next two decades, but at least those who choose to do so can.  Tie it into the
headsets parental settings.

## Conclusion

I'll keep exploring options and dig into the w3c committee details.  I wouldn't
be surprised to discover settings on desktop browsers that permit this, I have
not yet tried in this decade.  I am looking forward to see how this evolves and
if we can push this forward in some meaningful way.
