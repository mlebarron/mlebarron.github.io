---
layout: post
title: "Responsive is dead, long live responsive"
description: "Thoughts and a bit of a rant on responsive design"
tags: [responsive]
comments: true
published: true
---

### Responsive is dead

> "Just make it responsive"

The most common definition of responsive design is that you can serve one codebase for the front end and it "just works" across all devices, from a desktop to a phone. The idea is great, but flawed. It completely ignores devices in the real world, where use cases change, interaction methods are different, bandwidth changes, and devices have wildly different capabilities.

Have you ever watched someone develop for "responsive"? 9 times out of 10 it involves building the site in a standard desktop browser, then resizing the window to see how it changes. I'm guilty of this myself, but when you do it, what are you building? You're building a site that someone can go to, and resize the window to a bunch of sizes and it will still kind of work.

Building like this is just an excuse to be lazy, just ship all the code to every and just let the browser sort it out. Are we really that afraid of writing server side code to have some smarts? To do at least a little checking and send only the code required by the device?

> "But those guys are doing it, and it works for them"

Well, by all means, go ahead and do it then. I assume that by now you have learned that what works for other people doesn't always work for everyone. It also doesn't mean it's the right way, it's just what works best for them.

> "But Bootstrap/Foundation give me responsive for free"

No, no they don't. They're frameworks to help you build sites, not a magic bullet that makes responsive "just work".

> "What about all the research of the past few years?"

Let's face it, a bunch of the solutions we've come up with are just hacks. We lean on Bootstrap and Foundation and expect them to be the answer for making sites work on multiple screens. Show for mobile, hide for mobile, show on desktop... they're hacks, made for prototyping, but we stick them into production because we get lazy. It's the best we could come up with at the time, and it has worked so far, but let's not get lazy.

### Long live responsive.
