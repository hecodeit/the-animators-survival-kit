---
layout: default
title: Bouncing Ball
parent: 01 Timing And Spacing
---

## Bouncing Ball
<div id="bouncing_ball" style="max-width:600px;"></div>
<img src="../img/03_ball.jpg" style="width:100%;max-width:600px;"/>


<script>
  var bouncing_ball = bodymovin.loadAnimation({
    container: document.getElementById('bouncing_ball'),
    renderer: 'svg',
    loop: true,
    autoplay: true,
    path: '../lottie/03_ball.json'
  });
</script>
