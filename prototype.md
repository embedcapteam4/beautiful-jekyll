---
layout: page
title: Rapid Prototype
subtitle: Team 4
---

The Smart Mirror is coming along nicely and we already have a working prototype for the basic functionality. The mirror is currently recognizing faces and logging in the appropriate user. The setup is customizable per user by editing the config files manually, and we even have a basic web app for customizing the mirror.

Here is what the current prototype looks like:

<figure>
	<img style="width: 50%; height: 50%" src="{{ '/img/Rapid_Proto_TV_Camera.jpg' | prepend: site.baseurl }}" alt=""> 
	<!-- <figcaption>Hover Gesture Controller</figcaption> -->
</figure>

The TV Monitor will be covered with 2-way film and have a frame mounted on top to more resemble a mirror. The ELP Mini HD USB Camera is temporarily mounted on top, but will eventually be hidden behind the frame with an opening for the lens. The Raspberry Pi is currently resting on the counter for easy access while prototyping, but will also be mounted behind the frame. 

User being recognized and logged in:  

<figure>
	<img style="width: 50%; height: 50%" src="{{ '/img/Rapid_Proto_User_Camera.jpg' | prepend: site.baseurl }}" alt=""> 
	<!-- <figcaption>Hover Gesture Controller</figcaption> -->
	<img style="width: 50%; height: 50%" src="{{ '/img/Facial_Recognition_Greeting.jpg' | prepend: site.baseurl }}" alt=""> 
	<!-- <figcaption>Hover Gesture Controller</figcaption> -->
</figure>

Web application used for mirror customization:  

<figure>
	<img style="width: 50%; height: 30%" src="{{ '/img/Magic_Mirror_WebApp_Login_Form.jpg' | prepend: site.baseurl }}" alt=""> 
	<!-- <figcaption>Hover Gesture Controller</figcaption> -->
</figure>

Face recognition is currently working, but must be set up by manually running scripts through the terminal on the Raspberry Pi 3. Soon we will have a more friendly user interface that can be operated through the Hover gesture sensor and a web application.

Here is a preview of that functionality and how it will enable a new user to set up their profile:

<figure>
	<img style="width: 100%; height: 100%" src="{{ '/img/proto1.jpg' | prepend: site.baseurl }}" alt=""> 
	<!-- <figcaption>Hover Gesture Controller</figcaption> -->
</figure>
<figure>
	<img style="width: 100%; height: 100%" src="{{ '/img/proto2.jpg' | prepend: site.baseurl }}" alt=""> 
	<!-- <figcaption>Hover Gesture Controller</figcaption> -->
</figure>

We are happy with our progress thus far, but still have lots to do! The phone and gesture integration will really pull the Smart Mirror together, and will vastly improve the user experience. We can't wait to show off the mirror once the next stages are complete.

