---
title: "Design Patterns"
date: 2019-04-25
draft: true
toc: false
images:
tags:
  - software
  - design patterns
---

Software design patterns are solutions to commonly occurring problems. After writing tons of code over time and experiencing the same problems over and over again programmers noticed the solution to many of these problems could be categorized, labeled, and reused. By studying and understanding these design patterns you are, in effect, learning solutions to some of the most prevalent problems in software engineering. Once we understand the core solution to a problem we can reuse this solution and tailor it to fit our specific needs.

It wouldn’t make much sense to write code, face a problem, work to solve this problem, then look back later on and realize there’s already a pattern for it. Why reinvent the wheel? There’s no need to make the same mistakes as those who have come before us, especially when these mistakes, and the solution to these mistakes, are so well documented. As many of these patterns are language-agnostic, it really is worth taking the time to learn how to use them and when to apply them to your own work.

**Pros**

- Communication: They help you communicate design ideas with other programmers. 
- Readability: They help you write more understandable code which is easier to follow and makes what you are trying to accomplish much clearer.
- Maintainability: As a result of being more readable, your code will be much easier to maintain as it can be easily understood.
- Reuse: By using common solutions to common problems you can reuse the same code when these problems arise again.
- Less Code: They allow you to write less code because you can abstract common functionality to common base classes.
- Tested Solutions: Many of these patterns have been around for years and have been tested and proven to work.


**Cons**

- Extra Level of Abstraction: Many patterns involve a level of abstraction which can make the code a little more complex.
- Knowing when to apply them: Design patterns can be abused and used in cases they shouldn’t be. Sometimes it’s better to keep things simple and avoid the extra work of implementing a design pattern.
- Different Interpretations: Programmers sometimes have slightly differing interpretations of design patterns which can lead to misunderstandings. (For example, the way the Gang of Four explain the MVC design pattern is different than the way modern web apps implement MVC)

So what’s the goal here? We want to build software that’s reusable, bug free, and makes sense. We want to reduce the common issues we face thus making our lives, and the lives of anyone who’s tasked with reading or maintaining our code, easier. Using design patterns is one of the ways we can accomplish all of this. 
Let’s take a look at the MVC (Model-View-Controller) pattern. In simple terms, it separates the concerns of our models, views, and controllers. By decoupling these from each other, we’re able to make changes to one of these component without affecting the others by very much. This leads to code that is very adaptable to change and reduces the effort needed to scale a project.
In today’s world technology is evolving rapidly and the reality is reading about or knowing design patterns alone does not mean you’ll be able to implement them effectively. Being able to recognize where and when to apply a pattern is a skill in itself that can only be improved with practice and maybe some trial and error.


