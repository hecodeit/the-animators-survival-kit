---
layout: default
title: Home
nav_order: 1
description: "A study log of The Animator's Survival Kit, a book by Richard Williams."
permalink: /
---

# The Animator's Survival Kit
A study log of The Animator's Survival Kit, a book by Richard Williams.

## Motivation
The first animations I have made which use SoftWear Adobe Flash, many many years ago. I'm draw on stage, play with timeline, write script control the spirit which interact with mouse and keyboard. It's the very first step I'm beginning work with graphic design, animation and programming. Later I become graphic designer and programmer, working on graphic design, creative coding, web/app design and development area.

Few month ago, I working with LottieFile animation for one client. Later, I am very interested in how make perfect illustration and animation for Website or Mobile Apps.

By googling resources of on internet, I read the book and watch the video course of "The Animator's Survival Kit" by Richard Williams. It is change everything I think about animation. Before the book, I think animation is some kinds of production by SoftWear. Now I find it is really no concern with software. But a way to planning, design and produce moving pictures, it's an art that emotionally move your audience.

There, I will write everything I learned.

## The Animation Principles
<div id="animation" style="max-width:600px;"></div>
<script>
  var animation = bodymovin.loadAnimation({
    container: document.getElementById('animation'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: 'lottie/03_timing_and_spacing_bounce.json'
  });
</script>
If you googling how make animation, you will find people talk about Animation Principles. On internet, books, youtube... The most famous one is [Twelve basic principles of animation](https://en.wikipedia.org/wiki/Twelve_basic_principles_of_animation) by the Disney animators Ollie Johnston and Frank Thomas in their book.

Why Animation Principles? How understanding all these kinds of principles? I'm asking myself. What these principles working for? What's the most important principles?

As well knows that even not trained person, can easily find the huge different between vivid animation with lifeless puppet animation. So what happen when people watch an animation? I will pass away from all kinds of principles first, to find why things work out.

> **_There are lots of principles, formula, cliches and devices here to help, but the main thing I want to pass on is way of thinking about animation in order to free the mind to do the best work possible._**

> **-- Richard Williams**

## It's All In The Timing And Spacing
> **_First plot out the timing... and see what looks right or wrong. Try it with different timing and spacing. You're already animating._**

> **-- Richard Williams**

Richard invent a very simple way to making animation. Put your subject on stage, try with different timing and spacing, and test it.

**See, it's moving!** It's working, but look strange. No such of things moving like that in the real world.
<div id="coin_a" style="max-width:600px;"></div>

Better with slow in and out.
<div id="coin_b" style="max-width:600px;"></div>

Even better with some adjustment.
<div id="coin_c" style="max-width:600px;"></div>
<script>
  var coin_a = bodymovin.loadAnimation({
    container: document.getElementById('coin_a'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: 'lottie/04_coin_a.json'
  });
  var coin_b = bodymovin.loadAnimation({
    container: document.getElementById('coin_b'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: 'lottie/04_coin_b.json'
  });
  var coin_c = bodymovin.loadAnimation({
    container: document.getElementById('coin_c'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: 'lottie/04_coin_c.json'
  });
</script>

When you walking into outside form dark room, your eyes need times to get the change. Few seconds later, your eyes can seeing with no problem. Otherwise if the light change between dark with light all the time, you will see noting but get mad.

Same way, your eyes catch up by the moving things with slow in. So you find the moving thing on stage first, then you can track it even fast later. Otherwise, if the position change all the times, you can only see flash afterimages.
