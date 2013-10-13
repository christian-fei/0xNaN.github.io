---
layout: post
title: "Two words about security"
date: 2013-10-12 20:06
comments: true
categories:
 - security
---

Few days ago I bought an item from a *famous* online shop.  
This site provides a simple game that allows to win points, which afterwards the users can transform to coupons.  
It consist in a simple animation which shift 12 baskets from right to the left: the user must shoots a ball and hit the center of the basket.  <!--More -->
Each basket provides points according to is own dimension: if it's tiny the user gets a lot of points, otherwise he gets less points.  
When the time ends, the user can transform the points to coupons: 100pnt for **1$** (for purchases over 10$), 300pnt for **3$**(for purchases over 30$), 4000pnt for **15$**(for purchases over 150$), and so on.  
The graphics of the game is really nice and there are a lot of nice effects with HD images.  
The game is written in HTML and CSS and the baskets are hidden trough CSS (```display``` propriety), also the value of each basket is set trough a CSS class.  
When I saw this I wanted to try a stupid test: change the value of CSS class trough the DevTools of Chrome and run the game.  
The result? I've completed the game with an incredible amount of points and the server didn't noticed it!! I was able to trasform all the points to coupons and use them.  
This reminded me how much stupid people care about the graphics, forgetting the security of the code, even though there are real money in prize!
