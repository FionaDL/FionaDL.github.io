---
layout: post
title:      "CLI project complete."
date:       2018-05-16 10:34:01 +0000
permalink:  cli_project_complete
---


I was actually really excited to dive into the first real project. I wanted to see if I had been able to hang on to any of the knowledge that I had been trying to squash into my brain for the past nine months or so. The answer was some of it yes, some of it no. 

The things I really struggled with:

1. I had a really hard time setting up the git repository and the gem. I was a little confused at first by setting it up in the temporary file or sandbox that is currently the base when you open the learn IDE. Eventually I just went with it and cloned my git repository into it. I did have to go back and review all of the git commands, but after using them so often over the last week and half I think I've got them down. At least for now.
 
2. For some reason I had some technical difficulties in the beginning, I was naming things differently in the git repository and the gem bundler. I had to give it about 4 tries of deleting and setting up before it was all running smoothly.

3. Scraping! I actaully really enjoy scraping, it is so fun when it finally all works. I choose a web page from Wikapedia (https://en.wikipedia.org/wiki/List_of_Michelin_3-star_restaurants). I did a lot of googling on how to scrape a wikitable, but I couldn't find much on scraping multiple tables at the same time. I think that most of my time on this project was spent on working out the scraping. The regular class coding, and especially the CLI flow went along much more seemlessly. Except for one method. 

4. I banged my head against the wall trying to figure out why my Country.find_by_name method was not working. My Restaurants.find_by_name class was working just fine, and was very similar to the Country.find_by_name method. Everytime I enter a country name to be found I got back "nil". I was so frustraited and went over this and over it. Finally I set up a technical coach meeting. About 15 minutes after I set up the meeting I realized what the problem was. When I was creating my list of countries it was being scraped from the site, and on the site every country was listed like this " Belgium". It was that space before the name that was breaking my method. It's always those tiny things that really get me. I hope that as I become a more experienced developer I won't have so many of those moments.

5. The other part that I wish there was some more direction with is how to make the demostration video. Maybe I am being daft, but I don't understand how to add a url that would have the video, and I also don't understand how long the video should be and exactly what it should cover. 

All of this being said, I really enjoyed the process and feel like I have learned a ton. I can't wait to do more!

If you want to checkout my gem this is the url: https://github.com/FionaDL/michelin3star.git

