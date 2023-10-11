---
layout: page
title: download 
---
<html lang="en">
    <head>
        <meta charset=utf-8/>
    </head>
    <body>
        <div id='player'>
          <video width="352" height="198" controls>
            <source src="http://10.16.100.206:8080/hls/somoytv.m3u8" type="application/x-mpegURL">
          </video>
          <script src="https://vjs.zencdn.net/7.2.3/video.js"></script>
<script>
var player = videojs('hls-example');
player.play();
</script>

        </div>
    </body>
</html>
