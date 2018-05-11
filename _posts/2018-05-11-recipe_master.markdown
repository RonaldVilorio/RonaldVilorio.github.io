---
layout: post
title:      "Recipe Master"
date:       2018-05-11 15:28:04 -0400
permalink:  recipe_master
---


For my Rails Portfolio project I ended up doing a recipe manager web application. An app where a user can make an account, sign in and keep track of all their recipes. A user would be able to check other users recipes and make comments, leave rating on their recipe.

I spent the first 2 days planning out the project. I wrote down all the tables and models I was going to use and their associations. I wanted to make sure I had this right before I went ahead in my project. After finishing the planning, I decided to work on the signing in and creating a user part of the project which wasn’t too bad until I had to deal with omniauth and facebook. I was having a hard time logging in through facebook even after following documentation and looking through labs. After a bit of googling I managed to pinpoint my problem and get a solution. Facebook was expecting my url to have ssl with https but I only had http on my side so when facebook sent the token, it was not finding my url.

The facebook login took a large amount of time to finish. It really was a great a feeling after I saw the login went through in the browser. Solving problems is great because you earn your reward, and the harder the problem the more reward there is. I took it step by step, and while I would not progress much some days I knew I was still progressing because I would work on it every day. 

There was always a game of catch going on between the view and controller. user id and recipe id are always being sent, or sent back and found between create, show, edit actions. So I started to get more comfortable with the flow of things. I also realized during the project building that I didn’t understand how some things were happening, and had to go back to prior lessons to reconsolidate concepts. Reading is great, and watching videos is helpful in learning, but building out a project is truly where you get the most benefit in consolidating concepts.

Iv said it before but I’ll say it again, breaks are very important for working efficiently and you would be surprised on how quickly you can solve something coming in with a clear mind. I made sure to take frequent breaks on this project. It’s important to take it step by step and this way you make sure not to overwhelm yourself. It was a great learning experience, but now I’m off to relearn some Javascript!

	

	

	

	
