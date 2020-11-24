---
layout: default
title: 01 Timing And Spacing
nav_order: 2
has_children: true
---

## It's All In The Timing And Spacing
> **_First plot out the timing... and see what looks right or wrong. Try it with different timing and spacing. You're already animating._**

> **-- Richard Williams**

Richard describe a very simple way to making animation: put your subject on stage, try with different timing and spacing, and test it.

**Look, it's moving!** But boring.
<div id="coin_a" style="max-width:600px;"></div>

Same timing but difference spacing. Better with slow in and out.
<div id="coin_b" style="max-width:600px;"></div>

Even better with some adjustment.
<div id="coin_c" style="max-width:600px;"></div>
<script>
  var coin_a = bodymovin.loadAnimation({
    container: document.getElementById('coin_a'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/04_coin_a.json'
  });
  var coin_b = bodymovin.loadAnimation({
    container: document.getElementById('coin_b'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/04_coin_b.json'
  });
  var coin_c = bodymovin.loadAnimation({
    container: document.getElementById('coin_c'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/04_coin_c.json'
  });
</script>

When you walking into outside form dark room, your eyes need times to get the change. Few seconds later, your eyes can seeing with no problem. Otherwise if the light change between dark with light all the time, you will see noting but get mad.

Same way, your eyes catch up by the moving things with slow in. So you find the moving thing on stage first, then you can track it even fast later. Otherwise, if the position change all the times, you can only see flash afterimages.
