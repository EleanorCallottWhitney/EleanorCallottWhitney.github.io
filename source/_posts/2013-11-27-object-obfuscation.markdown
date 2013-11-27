---
layout: post
title: "Object Obfuscation"
date: 2013-11-27 17:36
comments: true
categories: 
---

In Ruby "Everything is an object!" Okay, I know, but really not EVERYTHING is an object. For example, methods are not objects (or are they?), attributes are not objects, and so forth. I tihnk what was really tricky for me these past to weeks was to take the theory that we learned in class, which makes a lot of sense in the abstract and when it's being explained to me, and be pushed to make something (very basic) with it in practice. This felt frustrating. I knew where I wanted to get to, but didn't feel like I really had a grasp yet of the tools I had been equipped with to get there.

The exercise was simple and I couldn't figure it out. After hours of starting at the screen, reading Ruby tutorials, exclaiming to a friend on gchat I, "Couldn't make my duck quack! [the point of the exercise, sort of]" and looking through Stack Overflow for answers I began to understand the finer points of objects, but I still couldn't make my objects do what I needed them to do. Honestly, it made me question my ability to do just about anything. Include solve complex, or not so complex, problems. I had flash backs to high school Calculus where I'd sit in class, completely befuddled and stare at my homework for hours, pencil poised over the paper, producing nothing. 

Thankfully, Ruby is much easier to understand than Calculus (for me anyway) and with some coaching from Zach and talking through with classmates Vish and Elizel, I was able to sort out, line by line, exactly what I needed my code to do and then, finally, write it. 

Here's a few of big takeaways:
attr_accessor is my friend! It has the abilit to both read and write instance variables and avoid that pesky "Undefined method" error.

Puts simply prints a string to the screen - it's not dynamic. I was getting tripped up because I was using puts and not return. Now I know in the future I learn further subtlties, but this was really helpful to understand.

It's amazing how such a small change and undrstanding more information could help me break through hours and hours of defuddlement. 