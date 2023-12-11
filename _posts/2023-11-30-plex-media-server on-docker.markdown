---
layout: post
title:  "Plex server on docker"
date:   2023-11-30 20:54:23 -0700
categories: portfolio update projects

<p>Recently restarted my plex server project. In the past I had tried to host one on a raspberry pi 4b with varying levels of success due to sd card corrution. That pi is currently a retro gaming station running off usb instead. 
After configuring a wireless bridge with an old router I finally had internet for my old computer server project (8th gen i7). I was determined to run this plex server through a docker-compose.yml file instead of 
the command line CLI scripts I had used in the past. After a few hours and some difficulties the plex server is up and integrated with Overseerr, Radarr, Sonarr, Jackett and Transmission.  It was a fun project and
the result is a fully automated media server and a good way to finally learn docker-compose. I've included some pics of my docker-compose setup for anyone curious:</p>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
div.scroll-container {
  background-color: #333;
  overflow: auto;
  white-space: nowrap;
  padding: 10px;
}

div.scroll-container img {
  padding: 10px;
}
</style>
</head>
<body>

<h3>Use the horizontal scrollbar to see the other images.</h3>

<div class="scroll-container">
  <img src="../../../Images/docker1.png" alt="docker-compose pt.1" >
  <img src="../../../Images/docker1.png" alt="docker-compose pt.2" >
  <img src="../../../Images/docker1.png" alt="docker-compose pt.3" >
  <img src="../../../Images/dockerps.png" alt="docker containers running" >
</div>
