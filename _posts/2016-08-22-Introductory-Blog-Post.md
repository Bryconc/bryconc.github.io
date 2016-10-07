---
layout: post
title: Introductory Blog Post
thumbnail: MoparScape_Login.jpg
---

### {{ page.title }}

<p class="meta"> {{ page.date | date: '%d %B %Y' }}</p>

<i>Topic: an introductory blog post describing your best "in class" computing experience as a computer science student and your best "outside the class" computing experience during your time thus far as a computer science student.
</i>

<hr>

In order to introduce myself as a computer science student, I must go back when I was eleven years old, to what was probably my best "outside the class" computing experience.
As with many children, I was an avid gamer, and my game of choice happened to be <i>[Runescape](http://www.runescape.com)</i>, an MMORPG which many of my best friends got me into 
playing. After many years of playing the game and watching player generated content on sites like YouTube, I came across Runescape Private Servers (RSPS), a replication
of the game's source code that was engineered an released to the public by fellow players. While the server source code (not necessarily the client source code) was
completely legal, the game's creator Jagex highly discouraged development of such servers, and the domain became somewhat taboo. 

Naturally, as a young child, all I saw was the potential to spawn myself high level gear and max out my character's skills with little effort in this sandbox environment, 
so I began investigating RSPS through the website Moparscape. With this community I found a variety of tutorials detailing how I could create changes within the
game (e.g. new commands, summon monsters, spawn items, etc.), with this little knowledge and a lot of copy and paste I slowly began to teach myself the programming
language Java. Of course initially, via just copy and paste, I had no way of learning the abstract concepts behind programming like what a method or data encapsulation
was, but through simple manipulation of existing code I began to learn the basic structure of a Java program. Now that I had developed some of my own custom content
(e.g. quests, new items, new monsters, etc.) I wanted to share my server with the world, luckily <i>MoparScape</i> was an expansive networking opportunity that
allowed advertisement of servers for other players to join. Via this networking of my server, I came into contact with and codeveloped projects with people from
all over the world (e.g. Texas, Florida, Canada, Britain). This first adventure in programming, still remains my most treasured non-academic experience as a computer scientist,
and it stems from a time long before professional training.

<figure>
    <img alt="MoparScape login screen" src="{{site.baseurl}}/img/blog_pics/MoparScape_Login.jpg">
    <figcaption><i>MoparScape</i> login screen. <i>MoparScape</i> was the host/tutorial site for begining RSPS players.</figcaption>
</figure>

My most favorite "in class" computing experience, seems meager by comparison (but then again it's hard to compete with my first experience), but I would have
to say it came from my CS3535 Music Informatics class. This was an experimental class more-or-less, falling under the category of "Selected Topics," taught by
Dr. Mitch Parry. In a very broad sense, the goal of the class was to analyze music at a computational level and perform calculations such as fingerprinting, 
similarity analysis, and database construction. Moreover, the class was a research experience: each student was allowed to choose a related area of interest and spend
the semester researching and developing a product. The primary building block of the course was the EchoNest data platform, that would analyze bits of sound and
return relevant information based on what song the sound identified as. 

In conjunction with this platform, the web calls served as sort of a wrapper for access to the Spotify API; this is where I found my area of interest. As a dedicated user 
and subscriber of Spotify, I wanted to develop an application that could be used as a sort of utility program. With my personal use of Spotify, I constantly ran into the
problem of having massive public playlists that I found from friends without any idea of their full contents. Short of manually clicking through every song, I wanted some
sort of application that would allow me to "sample" the contents of playlists automatically. And thus, through my experience of learning Python, Spotipy, and TkInter I developed
a program I appropriately dubbed the "[Spotify Playlist Sampler] (https://github.com/Bryconc/Spotify-Playlist-Sampler)", which would automatically queue 30 second samples of each
track in a playlist and allow recording of your favorite tracks to be exported to a new or existing Spotify playlist. This project allowed me to tackle problems such as retrieval
of external network resources, multi-threaded programming, the MVC design pattern, and much more. This was my first large scale project that I followed to completion completely
independently, and that is why I've dubbed it my best non-academic programming experience.

<figure>
    <img alt="Spotify Playlist Sampler screenshot" src="{{site.baseurl}}/img/blog_pics/Playlist_Sampler.jpg">
    <figcaption>Spotify Playlist Sampler screenshot. The picture shows an active traversal of a playlist, while accumulating a list of favorite tracks.</figcaption>
</figure>