---
layout: essay
type: essay
title: Getting the Code to Fit (Specifically, Getting Javascript ES6 Code to Fit an ESLint Coding Standard)
# All dates must be YYYY-MM-DD format!
date: 2019-02-06
labels:
  - Software Engineering Coursework
  - Reflection
---

I'm at a point in my software engineering coursework where we (all the students in the class, I suppose) are making the transition from a bootstrapping set of Javascript coding systems (FreeCodeCamp, JSFiddle, etc.) to a desktop environment (IntelliJ IDEA) that I suppose is going to slowly but surely further transition into a professional-looking coding environment.  Hopefully, I can handle that.  But, for now, one of the main changes from the bootstrapping systems is the addition of a coding standard called ESLint.

## What is a coding standard?  What is ESLint?
I don't have a formal definition of what a coding standard is, but for our course, the coding standard is _built into_ the coding environment.  Our coding standard uses ESLint for Javascript ES6.  Prior to using one of these built-in coding standards, I would've thought that the only way to abide by a coding standard was to painstakingly read through the entirety of a coding standard manual and check your code to see if it abides by the standard.  Now, doesn't that sound fun?

Anyways, since the coding standard is built-in, anytime your code violates the coding standard, your coding environment will mark the text where the violation occurs with red squiggly underlining, even if the code has legal syntax that can technically run.  And just to be clear, you can run your code even if there are red squiggly underlines in your environment.  Or, at least, my environment can, I tried it!

Furthermore, having any coding standard violations will show a red icon (I forgot if it was an 'X' or a circle with a cross-out, something like that) at the top-right corner of the environment.  Having no coding standard violations will instead show a green checkmark at the top-right corner (which is what you want, I suppose).

And the real kicker is that our course requires that from here on out, code submissions must have the green checkmark, otherwise we get pointed deducted.

## What do I think of this built-in coding standard?
Now personally, I've always tried to make my code consistent even without a coding standard, so this is actually a boon for me, but I can imagine that those who are used to just making code 'work' will have to break some old habits to get the green checkmark while making working code fast.

But I only discussed how coding standards are viewed when they are used in individual projects where only you and maybe a few other people are expected to look at the code you write.  What about an enterprise-level coding project?  Even if you have two consistent coders, they can be consistent in different ways which will make sharing code on platforms like GitHub result in code that is a Frankenstein of the different coding styles involved.  When all contributors to a coding project agree on a built-in coding standard, then we don't get 'Frankenstein code' as a result and the code is written in a consistent format.

You may have heard from YouTube videos and articles about programming that there are many different ways to solve a problem, but in this context, having all those different ways of writing legal code creates unwanted chaos when all we want is to be able to read another person's code with ease and consistency.

## Some parting comments
Of course, I'm personally all for agreeing with a classroom-specific built-in coding standard as I like my code to be consistent and this actually makes it easier to write consistent code.  Without a coding standard, I would have to pick a style as I write my code, and that can be challenging with multiple styles to choose from.  Also, more often than not, I found that the error messages were actually helpful at least for the small projects that I've done with the new coding standard.

However, I should be mindful that perhaps not everyone will share my enthusiasm for a class coding standard.  Still, I think a coding standard is necessary and I'm just thankful that it's built into the environment and I don't have to drudge through a coding style manual just to make sure my code doesn't violate the standard.
