---
layout: default
title: Bouncing Ball Chapter II
parent: 01 Timing And Spacing
---

## With Squash and Stretch
<div id="bouncing_ball_squash_stretch" style="max-width:600px;"></div>
<img src="../img/03_ball_squash_stretch.jpg" style="width:100%;max-width:600px;"/>

## Put Contact With Squash and Stretch
<div id="bouncing_ball_squash_stretch_b" style="max-width:600px;"></div>
<img src="../img/03_ball_squash_stretch_b.jpg" style="width:100%;max-width:600px;"/>

## Soft Ball, Less Squash
<div id="ball_soft_less_squash" style="max-width:600px;"></div>
<img src="../img/03_ball_soft_less_squash.jpg" style="width:100%;max-width:600px;"/>


## Heavy Bowling Ball
<div id="ball_heavy_bowling" style="max-width:600px;"></div>
<img src="../img/03_ball_heavy_bowling.jpg" style="width:100%;max-width:600px;"/>

## Bouncing Bubble
<div id="bubble" style="max-width:600px;"></div>
<img src="../img/03_bubble.jpg" style="width:100%;max-width:600px;"/>


## Bouncing Ball Rotate
<div id="bouncing_ball_rotate" style="max-width:600px;"></div>
<img src="../img/03_ball_rotate.jpg" style="width:100%;max-width:600px;"/>

## Bouncing Rod
<div id="bouncing_rod" style="max-width:600px;"></div>
<img src="../img/03_bouncing_rod.jpg" style="width:100%;max-width:600px;"/>


<script>
  var bouncing_ball_rotate = bodymovin.loadAnimation({
    container: document.getElementById('bouncing_ball_rotate'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_ball_rotate.json'
  });
  var bouncing_rod = bodymovin.loadAnimation({
    container: document.getElementById('bouncing_rod'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_bouncing_rod.json'
  });
  var bouncing_ball_squash_stretch = bodymovin.loadAnimation({
    container: document.getElementById('bouncing_ball_squash_stretch'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_ball_squash_stretch.json'
  });
  var bouncing_ball_squash_stretch_b = bodymovin.loadAnimation({
    container: document.getElementById('bouncing_ball_squash_stretch_b'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_ball_squash_stretch_b.json'
  });
  var ball_soft_less_squash = bodymovin.loadAnimation({
    container: document.getElementById('ball_soft_less_squash'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_ball_soft_less_squash.json'
  });
  var ball_heavy_bowling = bodymovin.loadAnimation({
    container: document.getElementById('ball_heavy_bowling'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_ball_heavy_bowling.json'
  });
  var bubble = bodymovin.loadAnimation({
    container: document.getElementById('bubble'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_bubble.json'
  });
</script>
