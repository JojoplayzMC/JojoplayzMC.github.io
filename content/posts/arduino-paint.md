---
title: "Running paint on an Arduino Mega 2560"
date: 2026-02-08
draft: false           # IMPORTANT: Set to false or it won't show up!
tags: ["arduino", "c++"]
categories: ["projects"]
showToc: true          # This adds a Table of Contents (PaperMod feature)
---
## The idea
So at night, I always get random ideas, and last night, I thought of running an app on an arduino. You see, arduinos, while amazing at running LED strip lights behind your bed, they aren't nearly as powerful as any modern computer. But what if we tried anyway? My idea was to have a python script running on my computer that sends my mouse movement to the arduino, and the arduino would then send an image back.
## The First Image
After about an hour of thinking, programming, testing and debugging, I eventually managed to get the first image out of the arduino. While it wasn't much, it was proof that this was possible.
[![Screen showing blue, green, red, and black stripes](/images/ap1.png)](/images/ap1.png)
I then proceeded to keep working at it until I could get a clean image, and finally, eventually, I did it.
[![Screen showing completely random dots](/images/ap2.png)](/images/ap2.png)
[![Screen showing black and red stripes with some random interference](/images/ap3.png)](/images/ap3.png)
[![Clean Blue, Green and Red stripes as expected](/images/ap4.png)](/images/ap4.png)