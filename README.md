<strong>Notes on learning Laravel</strong>

<strong>TL;DR</strong>: 

To test out the login page, go to: 

link: khoo.website 

username: zus@coffee.com

password: zuscoffee

There are 5 profiles created, and the link to ZUS coffee's page would be 
khoo.website/profile/5. The 4 remaining is khoo.website/profile/#, replacing the # with 1, 2, 3, or 4. 

For this job opportunity and my curiosity on why to use a framework, I decided to pick up Laravel and went through the tutorial offered by freeCodeCamp. 

My initial understanding is web framework helps to abstract away the need to set your file directories and dependencies, hence encourage you to focus on just sprinting through an initial build of working app. A consistent file structure also helps other programmers to understand which part to look into to fix certain bugs. There are also libraries at your disposal, like the authentication package that saves us time. The framework practices a kind of software design pattern, which for Laravel's case is an MVC design pattern. 

Following the tutorial, I built an Instagram clone and called it freeCodeGram. 

The functionalities of freeCodeGram includes: 
 - Adding a new post with a caption
 - Following 
 - Unfollowing
 - Editing profile
 - Changing the profile image
 - Resizing photos using Intervention
 - Authentication (Logging in) 
 - Registering for new users 

Going through the process, my biggest yield will be practicing writing a web app using MVC. This helps to modularize Model (data manipulation, logic, etc), Views (what you see, updated by Model), and Controller (getting input from users and routing into Model to decide what to show on View). I also get to learn how to write a RESTful resource controller, passing the data to the view. This is beneficial for when I am writing the API for ZUS. Next key thing is to handle the many to many relationships among Profiles, and when correctly done, all the data on View can be dynamically generated. To resolve the N+1 problem that is caused by the query in prior, I made use of Cache. 

Overall, it was a life-changing step in my software development career because Laravel demands me to think about its highly opinionated grammar and syntax. In my coming projects, I will think in terms of MVC and I thank you, the one who is reading, for the opportunity to sharpen my skill. Hopefully, we'll be working together soon. :) 
(also, ftp is taking way too long) 
