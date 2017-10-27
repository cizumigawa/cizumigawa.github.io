---
layout: essay
type: essay
title: Reflect on Meteor
date: 2017-10-26
labels:
  - Software Engineering
  - Meteor Essay
summary: Reflect on Meteor
---

# Meditating on Meteor

There are many problems that I've experienced while using Meteor.  However, since I've already ranted through the things that I dislike about Meteor, I thought that I might as well dedicate this post to the three main things that impress me about Meteor: the way that Meteor auto-reloads, the way that it keeps projects organized, and the various support packages written for it.

Prior to using Meteor, I had been using Node.js for my web server needs.  As a new user who often made mistakes, I always found it irritating to have to shut down the server and restart it whenever something changed in the file I was working on -- then I found Nodemon.  
Nodemon is a npm package that allows Node to have auto-reloading functionality, and I hoenstly thought it was the best thing since making LEDs light up.  Anyway, as I mentioned before, I was a beginner who was making many mistakes and changes, so I greatly appreciated this feature, and I'm even more grateful that this feature also exists in Meteor.  Actually, I'm even more grateful that it exists in Meteor since Meteor takes a while to get up and running.

The struggles of a programmer who is new to web development are endless, but organization was exceptionally difficult to grasp in web development since literally the entire layout, design, and functionality of the whole site needs to be coded and linked together.  
Coming from a Python/C++ background where design and layout are pretty much nonexistent until UIs are necessary, I was a tad overwhelmed by the fact that not only did we have to write code for the full functionality of the site, but also, we had to design and write the code for the site itself.
In my prioir experience with web development, I was using two files to create a site which probably required at least five files, but because I couldn't quite find a good way to orgnaize myself (and I didn't want to figure out linking between multiple files), I ended up squishing a lot of technical functions into two files.
With Meteor, there is a clear file structure that is designed to help break the project into many smaller projects, and although it's a bit hard to navigate at first, I found it to be immensely helpful.

Lastly, the thing that impressed me the most about Meteor was how easy it was to find packages and functionalities for databases and websites.  For example, while I was at my job the other day, we were talking about implementing a basic security feature for a web API that I was producing.  Because the information that I work with should remain private, my mentor thought it best to start with something simple: just have someone log in before they can access data.  I honestly thought that implementing the new security function would take a day or two to complete, but low and behold, ICS 314 showed me how easy it could be to implement these basic functions using Meteor and Mongo in just 10 minutes.  I understand that some features would be better written on your own, but for what it is and how quickly it is to implement, the packages in Meteor are fantastic.

Like every framework, Meteor has its ups and downs, but in my opinion, if you're new to web development and have some spare time to learn, Meteor is a great framework to move towards.
