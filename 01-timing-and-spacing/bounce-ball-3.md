---
layout: default
title: Bouncing Ball Chapter III
parent: 01 Timing And Spacing
---


## Bouncing Ball With Trail
<div id="ball_stroke_no" style="max-width:600px;"></div>
<div id="ball_stroke" style="max-width:600px;"></div>
<div id="ball_stroke_squash" style="max-width:600px;"></div>

<script>
  var ball_stroke = bodymovin.loadAnimation({
    container: document.getElementById('ball_stroke'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_ball_stroke.json'
  });
  var ball_stroke_squash = bodymovin.loadAnimation({
    container: document.getElementById('ball_stroke_squash'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_ball_stroke_squash.json'
  });

  var ball_stroke_no = bodymovin.loadAnimation({
    container: document.getElementById('ball_stroke_no'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_ball_stroke_no.json'
  });
</script>
