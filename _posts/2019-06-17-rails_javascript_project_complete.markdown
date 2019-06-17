---
layout: post
title:      "Rails/Javascript Project complete. "
date:       2019-06-17 09:20:47 +0000
permalink:  rails_javascript_project_complete
---


The javascript project felt much more clunky at times compared to the other projects, I think that this was because of being built on top of the previous rails project. The way that my rails project was set up lead me to a few confusing issues within my javascript. The relationships between my challenges and workouts with a join table of challengeworkouts didn't at first make sense to me in javascript. I had to ignore some of the original project and simply concentrate on the requirements of the javascript to get everything working. 
The longest hold up that I ran into working though my javascript was getting $(this).serialize() to return a serialized piece of script when I was calling an event listener for my form. After days of struggling to figure out what was happening I met with Dalia, and she pointed me in the right direction when she mentioned that arrow functions treat "this" differently then the normal sytax for a function. I changes the arrow function to a regular function, and voila, I had a serialized "this". I won't soon forget that lesson!
To fufill the project requirements I have added buttons to my user show page that provide a list of current challenges and expired challenges. On the challenge show page you can click on the challenge to get more information about it, and you can also add a workout to the page. 
Working on this has really helped alot of things in javascript click for me. I wasn't fully grasping the concept of  an internal API until working thorough the requirements of this project.
I'm excited to move onto React!
