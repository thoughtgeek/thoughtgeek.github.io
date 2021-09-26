---
layout: post
title: How to write clean code

description: Clean code
summary: Clean Code Series
tags: ["Clean-code","codestyling"]
---


# Book summary series
### A Handbook of Agile Software Craftsmanship by Robert C. Martin

Clean code is an awesome book written by Uncle Bob and he absolutely nails it when he talks about the basic principles of writing well thought out human readable code. I thought I would make a small collection of takeaways from great books and I decided to start with this classic more like a reference for myself, but would be great to know if it helped someone else on thier journey.

# Chapter 1: Clean code
The first chapter was mostly a dialogue between the author and the reader. He(the author henceforth) broadly talks about these points.

  - **There will be code** 
  He argues that code is always going to exist. No matter whatever fancy future code churning AI comes out, we will always need code as means to fine tune software to the ultimate precision and objectivity to fulfill rules written by humans in our own language.

  - **Bad Code**
  Here he emphasizes on the LeBlanc's law: *Later equals never*. He talks about how we end up writing bad code or code that is difficult to read and comprehend quickly due to various practical constraints of working at a technology company and even cited a *killer app* in 80s that went down because of their messy code.

  - **Total cost of owning a mess**
  He talks how code keeps getting tangled with time and addition of new members working with the code and experienced members leaving the organisation. This ultimately leads to the next point.

  - **The Grand Redesign in the Sky**
  Too many problems, lets start redesigning our systems. However when the redesign happens, it has to keep pace with the existing legacy system. This can take a while to complete and by the time, half of the original people starting the redesign have left the firm. 
  
  - **Attitude**
  We should own up to the fact that we are the ones who keep writing messy code for whatever reason and that should change.

  - **The art of clean code**
  Clean code is more like an acquired taste over time of defining what is 'clean' and what is not. Everyone might not be easily able to write clean code but should have the eye to spot clean and unclean code.
  


### What is Clean code?
Clean code has been defined in many ways. There are some mentions of what clean code means to some of the brightest minds of the tech industry.

- **Bjarne Stroustrup, inventor of C++:**
*I like my code to be elegant and efficient. The logic should be straightforward and make it hard for bugs to hide, the dependencies minimal to ease maintenance, error handling complete according to an articulated strategy, and performance close to optimal so as not to tempt people to make the code messy with unprincipled optimizations. Clean code does one thing well.*

- **Grady Booch, author of Object-Oriented Analysis and Design with Applications:**
*Clean code is simple and direct. Clean code reads like well-written prose. Clean code never obscures the designers’ intent but rather is full of crisp abstractions and straightforward lines of control.*

- **“Big” Dave Thomas, founder of OTI and godfather of the Eclipse strategy:**
*Clean code can be read, and enhanced by a developer other than its original author. It has unit and acceptance tests. It has meaningful names. It provides one way rather than many ways for doing one thing. It has minimal dependencies, which are explicitly defined, and provides a clear and minimal API. Code should be literate since, depending on the language, not all necessary information can be expressed clearly in code alone.*

- **Michael Feathers, author of Working Effectively with Legacy Code:**
*I could list all of the qualities that I notice in clean code, but there is one overarching quality that leads to all of them. Clean code always looks like it was written by someone who cares. There is nothing obvious that you can do to make it better. All of those things were thought about by the code’s author, and if you try to imagine improvements, you are led back to where you are, sitting in appreciation of the code someone left for you—code written by someone who cared deeply about the craft.*

- **Ward Cunningham, inventor of Wiki and Fit, co-inventor of Extreme Programming.**
*You know you are working with clean code when each routine you read turns out to be pretty much what you expected. You can call it beautiful code when the code also makes it look like the language was made for the problem.*


# Chapter 2: Naming
Since naming is something that we as programmers are doing all the time, we better do it right. Here are couple of tips that Uncle Bob has for naming things.
  - **Use Intention revealing names**
  - **Avoid Disinformation** (Avoid any confusing names)
  - **Make meaningful distinctions** (*Examples to avoid:* a1,a2... or money, moneyAmount)
  - **Use pronouceable names**
  - **Use Searchable Names**
  - **Avoid Encodings**
 Uncle Bob elaborated on this point mentioning that encoding type or scope information is a bad idea. He mentions multiple notations like - *Hungarian Notation, Member prefixes, Interfaces and Implementations.* 
  - **Avoid Mental Mapping** (Avoid using single letter variables or anything that doesn't represent what it refers to)
  - **Class names shouldn't be a verb**
  - **Try starting method names with verbs**
  - **Dont use clever or cute names which can only be understood by some**
  - **Pick one word per concept**
  - **Pick one concept per word**
  - **Use solution domain words** (Use words comprehendable for any programmer)
  - **Use problem domain words** (Use words specific to the problem to the relevant code)
  - **Add meaningful context**
  - **Avoid gratuitous context** (Dont add what you dont need to)
