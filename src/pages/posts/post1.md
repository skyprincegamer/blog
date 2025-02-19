---
layout: "../../layouts/BlogLayout.astro"
title : "My first blog post"
subtitle : "CloudClock"

pubDate : "17/12/2024"
author : "ME"
editDate : "2/1/2025"
---
Hello everyone this is my first blog post!
In this post, I am going to explain my new project [CloudClock](github.com/skyprincegamer/cloudclock "github repo").

CloudClock is an attempt to create an app enabling users to set alarms (and timers) on one device so that the alarm goes off on all devices on which the user has logged in with the same username and password.

While it may sound basic to a veteran coder like yourself, keep in mind that this is the first project I am creating which is being pushed to GitHub.

Talking about the tech stack, the frontend uses **Tauri**, a (framework?) which allows the creation of cross-platform native apps using HTML-CSS-JS. It isn't _React Native_ because it renders the app using the respective OS WebView engine.

The backend is a **Node.js Express** server. And I think that it is the backend server implementation that would be the real challenge.

If multi-threading was an option, this might have been somewhat easy because I could just create a new thread for any new user which would have operated separately from all the other threads but maybe I can replicate that with separate routes and then use promises in the frontend.

Maybe.

I am not just doing this project to learn. I want it to be usable by others. Of course, at this point, I am not thinking of _hosting a cloud server_ for this purpose. I will just make the code for the server public with the instructions to run such that **even a complete noob** can start their very own cloudclock server and just use the client.

I am aiming to complete this project by December, because I have classes in college from 2nd Jan 2025. I can do it. I believe I can and maybe I can.

Maybe.

