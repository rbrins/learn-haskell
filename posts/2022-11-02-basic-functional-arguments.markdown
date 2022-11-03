---
title: Functional Programming Thoughts
tags: haskell, functional programming
---

# Functional Programming Thoughts

"""
There are all kinds of things that you're used to doing as a programmer that you cannot do any more with Functional Programming.

Just like in your car, you used to backup to get out of the driveway. But in a spaceship, there is no reverse. Now you may think, "WHAT? NO REVERSE?! HOW THE HELL AM I SUPPOSED TO DRIVE WITHOUT REVERSE?!"

Well, it turns out that you don't need reverse in a spaceship because of its ability to maneuver in three dimensional space. Once you understand this, you'll never miss reverse again. In fact, someday, you'll think back at how limiting the car really way.
- Charles Scalfanil
"""

Functional programming evangilist claims to solve lots of problems that arrise from things like mutable data, null pointers, and stateful functions. It could be that I'm so used to my life with the car (seem above quote) that I don't see even recognize the spaceship as anything but a terrible car. 

But in my personal experiences I didn't think I had these issues. I suspect it is a combination of mostly doing scripting applications, with my largest solo project and tool being only a thousand lines. When I put some thought into it, I did have lot of trouble with mutable data from reading and trying to edit arrays of dictionaries on the fly, and ended up taking the approach that I would read the array then create a return a new array from the changes I wanted to make. So slightly functional in implementation.



## Readings and Resources
* https://techbeacon.com/app-dev-testing/4-functional-programming-advances-redefining-app-dev-cloud
* https://github.com/readme/guides/functional-programming-basics
