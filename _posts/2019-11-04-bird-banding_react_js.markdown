---
layout: post
title:      "Bird-banding React.js"
date:       2019-11-04 16:52:49 +0000
permalink:  bird-banding_react_js
---


The final project is just about over. This has been a much, much longer journey than I ever could have imagined. Learning to code has been a slow and arduous process, but it has also been amazing. 

For the final project, I had dreams of creating an app in just a few days. I would include data pulled from the api of a government website, I would also deploy my app using AWS. Everything was going to be smooth, it would be easy! 

My grandmother was a bird-bander when she was living. I decided for my final project to make an app that would have made her gathering of bird data easier. I wanted users to easily be able to input data, delete data, and see data from other banding stations. 

Small mistakes and frustrating small problems have made my dreams more difficult then I imagined. I have not had time to add everything that I had hoped for in the beginning, but even so, I am feeling amazing. Why? Because I  think that I finally understand React and Redux, and isn't that the whole point? 

An example of the small frustrations that I faced in this project came at the very beginning. I could not get create-react-app to work! After hours of stack overflow and google searching. I finally found a solution that worked for me: 

-trouble updating Node.js so that I could use create-react-app. Finally figured it out by running

First update npm:

npm install -g npm stable

Then update node:

npm install -g node or npm install -g n

This may sound extremely simple, but I tried so many different commands to get node updated. It was making my head spin!

Finally, after using create-react-app I was on my way. But wait, how do I build a rails api, and what exactly does that mean anyway? Back to the googling, video watching, and searching. 

Then with both my rails api, and react front-end set-up it would be smooth sailing from then on out. Ha! Almost immediately I was stuck for two days trying to figure out why my Redux store was working one minute was not working the next. Grrrrrr. It turned out all I had to do was push the extension button again to get it to reload. I had manipulated my code a whole bunch to figure out what was going on. I had to put it all back the way it had been. 

Finally, after several weeks of working away at my code, learning more about bootstrap, users between frontend and backend, and redux, I could finish up everything. One last tiny problem arose when I decided I needed to include relationships in my serializer so that I could access the location of the banding stations. Changing the data structure I was receiving from the backend seemed like it would be easy to add to the front end, and it was. But I forgot to change it in one place, and suddenly I felt completely confused. Luckily, after several hours of panic, I asked Annabel what she thought, and after a few questions from her through slack, I was able to calm down and remember to change the data structure in one more place. Problem solved. Project over. Flatiron curriculum finished!


