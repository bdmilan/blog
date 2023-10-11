---
layout: page
title: download 
---
<!-- CSS  -->
 <link href="https://vjs.zencdn.net/7.2.3/video-js.css" rel="stylesheet">


<!-- HTML -->
<video id='hls-example'  class="video-js vjs-default-skin" width="400" height="300" controls>
<source type="application/x-mpegURL" src="http://10.16.100.206:8080/hls/somoytv.m3u8">
</video>

<script src="https://vjs.zencdn.net/7.2.3/video.js"></script>
<script>
var player = videojs('hls-example');
player.play();
</script>
