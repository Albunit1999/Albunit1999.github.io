---
layout: post
title:  "Car Park Occupancy Detection Using Neural Networks"
date:   2023-08-01
excerpt: "This project is a system that can identify empty car parking spots in a car park scenario"
image: "/images/carpark.jpg"
---

## What is Soundwrite?
SoundWrite is a web application which was made to assist the user to take notes on audiobooks. This project is being developed to address the issue of quality education which is part of the United Nations Sustainablity Development Goals. Audiobooks are a vital educational tool for people with learning disabilities such as dyslexia. Although there are various audiobook providers out there, Soundwrites main focus was on the educational side of things which created a strong emphasis around the note taking element.
<br/>
Key features :
<ul>
  <li>Take notes as you are going through an audiobook.</li>
  <li>Able to skip to the part of an audio when you click on the note taken.</li>
  <li>Organise notes according to the audiobook you read!</li>

</ul>

## The technical stuff
### Back-end
<p><span class="image left"><img src="{{ "/images/spring.png" | absolute_url }}" alt="" /></span>For the back-end we utilise Java Spring boot couple with Azure cloud services. We also use Spring security for the log in flow using JWT authentication tokens. Each time a user logs in, a new token is generated and stored in the users cache. Once this token is stored, it is sent to the back-end using a post request via axios. This returned the users data. How difficult was this? .... Very, considering it was my first big project (like most of my team) and having to create a complicated full stack application from scratch was extremely challenging.
</p>



### Front-end
<p><span class="image right"><img src="{{ "/images/react.png" | absolute_url }}" alt="" /></span>For the front-end we used React. As we found out, using React and Spring Boot together isn't the most popular combination which made things extremely difficult as there wasn't much content out there to aid us. However, React as a front end framework proved extremely versatile and through the use of axios we were able to perform POST and GET requests to connect with the back-end all while having a sleek user friendly interface.
</p>

## The end product

<div class="box">
<video width="840" height="680" controls>
  <source src="{{ "/images/soundwritevideo.mp4" | absolute_url }}" alt="" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
Your browser does not support the video tag.
</video>
</div>
