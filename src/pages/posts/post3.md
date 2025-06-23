---
layout: "../../layouts/BlogLayout.astro"
title : "The CloudClock Update"
subtitle : "I have actually almost completed it lol"

pubDate : "23/06/2025"
author : "ME"
editDate : "23/06/2025"
---
After trying dozens of different frameworks , languages, backends, I finally decided to make CloudClock in Flutter.

Flutter is the kinda thing that you cannot neither love nor hate.
You cannot hate it because it allows your app to run literally everywhere.
You cannot love it because its so fricking **VERBOSE**. Coming from Jetpack Compose , Flutter felt
like Im back in those days when I had write Java code for school. Heck , Dart gives me Java PTSD
all the time. 

Honestly ,if there were no platform considerations, 
I would have definitely made every single app in my life in QtWidgets (not QML).
QtWidgets is just soo understandable. Their "Signals and Slots" model is just a piece of absoulute genius.
Something will happen, signal will be emitted , which will trigger some slot.

Qt has wrapper classes for **EVERYTHING**. Strings, websockets, SQL Tables. And they their
"abstract" superclasses and you can extend them with subclasses (Although that is not even needed most of the time).
Combined with modern C++ features like std::optional, lambda functions , it is Object Oriented Programming at its peak.

I could have used some cross platform Javascript stuff. Maybe Electron. But Flutter is definitely
better than Javascript.

But the real game changer that truly allowed me to complete this project is **Supabase**.
All the routes in my backend, got reduced to a single SQL table. It just took my entire backend and solved every single problem.

Realtime updates to all users? Done. 

Auth? Ez Just use Supabase Auth.

Deployment? Generous Free Tier.

Security? Row Level.

Oh you dont trust the Cloud? Just run Supabase locally using Docker.

I feel like such a fricking idiot for not using Supabase the whole time. I was doing WebSockets,
WebHooks, even learned GoLang cuz it was created for writing servers. Supabase just simply works.

bUt mAyBe tHe rEaL "tReAsUrE" , wAs tHe sKiLlS We lEaRnT AlOnG ThE WaY. (right?)

