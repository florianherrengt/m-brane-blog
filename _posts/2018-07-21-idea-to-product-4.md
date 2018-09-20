---
layout: post
title: "From idea to product — Part 4: Build an app that doesn’t scale"
description: "This series of articles is targeting entrepreneurs who want to build a tech product. We will explain how to transform ideas into products based on previous experiences."
tags: [Entrepreneurship, Startup, MVP, Product]
---

[Part 1: Define your product from your idea](./idea-to-product-1)<br>
[Part 2: Get your early adopters without writing code](./idea-to-product-2)<br>
[Part 3: Create your product with existing tools](./idea-to-product-3)<br>
[Part 4: Build an app that doesn’t scale](./idea-to-product-4)

# Build an app that doesn’t scale

What your product does is crystal clear. You have a design ready. You need to build it and get thousands of users onboard.

Be careful not to over-engineer your app. Always keep in mind each feature will cost time and money. Consider the opportunity cost and maintenance overhead.

There is no formula to write perfect software yet. Estimations will be wrong, bugs will happen and tech debt will be introduced. The less code you write, the less you have to deal with them.

Building a scalable app requires a gigantic amount of work, expensive resources and complex skills. It involves teams of engineers specialised in their respective domain.

By building for scale, you introduce unnecessary complexity. It slows down the business without adding any immediate value. Before scaling, you need to have an in-depth understanding of each part of your system.

You should focus on technologies that increase the communication in your team.

> “Programs must be written for people to read, and only incidentally for machines to execute.” ― Harold Abelson

Don’t spend weeks or months “building the foundations”. You need to be able to add, remove and change things in days.

# Focus on communication

Get everyone — including non-tech people — involved when introducing a new technology. Explain why you think it’s a good idea and what value it brings.

Let’s have a look at two common sentences one might hear while discussing a technological choice.

“GraphQL is a great way to help developers communicate with each other. Our API documentation tends to be out of date and this would help to solve it.”
“GraphQL has better performance. It transfers fewer data between the client and the servers. It has more libraries to speed up our development”.
The first one is centred on improving communication. The second wants to fix non-existing issues.

Now, let’s talk about the two most common arguments: Scaling and development speed.

# Scaling

If you architect your app correctly, standard technologies will scale. Thousands of monthly active users shouldn’t be an issue. Getting a bigger server will most of the time solve your problem. If the tech stack is clear and manageable, it will be easier to identify bottlenecks.

# Development speed

When you introduce a new tool, you increase the level of knowledge required. You raise the risk of introducing tech debt that will take time to refactor later. Ultimately, it will slow down the team.

It’s always hard to make the difference between accidental complexity and essential complexity. But there are common ways to improve communication and sustain development speed.

- Write tests. You don’t need a great coverage. But when you deploy a new version, you want an automated way to check you didn’t break any vital parts.
- Set up a continuous integration. You need a server that runs your tests and deploys your app automatically.

# Recommended books

- [The Clean Coder](https://www.goodreads.com/book/show/10284614-the-clean-coder) by Robert C. Martin introduces the disciplines, techniques, tools, and practices of true software craftsmanship.
- [The Mythical Man-Month](https://www.goodreads.com/book/show/13629.The_Mythical_Man_Month) by Frederick P. Brooks Jr. tackles engineering and communications issues in software development.
- [Working Effectively with Legacy Code](https://www.goodreads.com/book/show/44919.Working_Effectively_with_Legacy_Code) by Michael C. Feathers is a useful read to identify how legacy code is produced. The code written today will be legacy tomorrow.

# Recommended articles

- [Shit Startups Do](https://hackernoon.com/shit-startups-do-episode-1-cbfa73f9c25f)
