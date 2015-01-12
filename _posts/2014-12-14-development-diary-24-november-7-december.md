---
layout: post
title: "Development Diary: 24 November–14 December"
author: Ben Day
---

Hey everyone, we're back for another quick Partier update. This week had a couple surprises. First, Brandon got a new job in sunny Florida! He'll be focusing his efforts on moving south these upcoming weeks, but he'll still be on the project and helping when he gets everything settled in Mojitoland. We threw a combination going-away and Christmas party for him this weekend. He got all mushy on us at the end of the night; it was beautiful. We'll miss you too, buddy! Good luck in Margaritaville!

Second, Jeff came down with something intestinally violent and has been out almost all this last week. He promises not to be useless next week, but we'll see about that - he promises a lot of things :D

Before everyone became preoccupied with career advancement or food poisoning, we managed to get quite a bit done! Jeff got user registration working on our servers, and Gatsby, our party manager and host, is up and running again... sort of. It can create 'games' now, but they don't 'play' nor can users join them yet. He's also got some security issues figured out. We can't be sending user's registration info out in plaintext to be intercepted, so we've got secure connections working locally and we're working to get them up on our servers to test with out clients soon!

Brandon has got his issues with PubNub figured out. PubNub is the data delivery service middleware we're using to communicate with the clients. The most recent issue with it so far has been the push notifications. After fixing a simple mistake, Brandon has notifications generating in the notification tray when PubNub sends a 'push.' 

And last but not least, Zachary has been getting our blog services set up for us, including ~~ensuring I don't sound retarded~~ *editing these posts for clarity.* He's also going to be looking to help the iOS build with PubNub integration and anywhere else that could use his wizardry.

That's all for this week! We'll try to get a post up once every week or two with new content and progress. Til then, have a good one!
