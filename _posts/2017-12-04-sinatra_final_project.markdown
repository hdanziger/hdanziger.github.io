---
layout: post
title:      "Sinatra Final Project"
date:       2017-12-04 19:00:09 +0000
permalink:  sinatra_final_project
---


Sinatra MVC projects are really cool because you can really see what you are creating, and watch as the changes you make effect what is on your screen. This section really helped me understand how all the components work together and work off of each other. I think also separating each section really helps as well. the controllers, versus the models, versus the views helps to separate not only the work, but also the thought flow. 

This project was very manageable because there had been so many practice labs that helped prepare for this final project. i like i had a good grasp of the concepts before actually jumping in, and knew what to expect with my program. In addition, since the previous labs had been so diverse, i felt like i could pick any type of platform to build because my knowledge was not specific to one type of domain. 

I started by building my tables, and then models, and then controllers, before moving onto my views. i liked the views section the most because enjoy the flexibility i had with the design of the forms when it came to font size and placement. 

the most challenging part for me was setting up the program itself, making sure i had all the proper gems and that my environment was set up correctly.

The strangest issue I ran into with this program was that when i was creating a user, it for some reason was not being saved in the session hash, but i was not getting an error, just stuck in the loop of signing in and signing up. I soon found out (with the help of Cernan!) that my issue was that i had set :sessions_secret instead of :session_secret, so there was the tiniest typo giving me the biggest headache! the toughest part about it was that i was not getting any error, so i couldnt even try to debug, i was just frozen. but once that problem was fixed, the program worked normally! 
