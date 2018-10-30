---
layout: post
title: "Are my developers good?"
description: "When you haven't spent the last 5-10 years building software products, it’s easy for people to pull the wool over your eyes. This post covers what you need to know."
tags: [Entrepreneurship, Code, Team]
thumb_image: good-code.jpg
---

When you haven't spent the last 5-10 years building software products, it’s easy for people to pull the wool over your eyes.

There are many stories about founders giving most of their money to con artists. They promised them the best app ever and a few months later, founders got nothing and everyone else is gone.

## Ask questions

### Where is the code?

In modern development, the code doesn’t stay on engineers laptop. It’s in what’s called version control and pushed to the cloud. The most popular platform today is GitHub but they are many good alternatives.

It doesn’t matter which one you use, but if you use none of this, we strongly recommend you to look at it immediately. This should be one of the first things you do when you start a project.

Every day, engineers create checkpoints called commits. You can see them in GitHub. Here’s an example of [React commits history](https://github.com/facebook/react/commits/master)

If you can’t see any commits on your project, ask questions. A high number of commits doesn’t mean things get done. But no regular commit is abnormal.

### Do you see regular updates?

Continuous integration (CI) deploys the changes when you push something to GitHub.

Don’t wait weeks or months to see results on your website or app. Updates should be incremental. You should see and approve them at least every week.

### Are they making progress?

Numbers help but do not judge productivity. Instead, you should look at progress.

There are many reasons teams do standups every morning. One of them is to make sure everyone’s doing what they’re supposed to.

_“What have you done yesterday?”_ and _“What are you doing today?”_ are the 2 questions you should ask every day.

Write it down and follow your team progress in a centralised place. Keep things simple, a notebook should be enough.

Make sure no one is getting stuck on the same task for too long. If an engineer has been working on “user profile” for 2 weeks, something’s wrong. Break it down in smaller tasks or ask why what’s taking so long.

## Keep track of progress

Ask your engineers to create pull requests.

> Pull requests let you tell others about changes you’ve pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

Source: [https://yangsu.github.io/pull-request-tutorial](https://yangsu.github.io/pull-request-tutorial)

With a clear description of what’s the pull request’s doing, you’ll know what’s going on. Get involved and ask to approve them before they get merged. If you do that, it is important that you keep on the top of every pull requests to make sure you don’t slow your team down.

## Assess code quality

That’s a tricky one. Even for a professional developer, it’s hard to recognise good code at a glance. But, anyone can spot bad ones. Here are a few red flags:

### Lines per files

Too many lines of code in a single file usually mean botched work. Recommendations usually range from 100 to 500 lines.

### Classes or functions per files

Most languages are using “Class” and “Function”. You can find those keywords in the code.

You should aim for, at most, 1 class or 10 functions per file. If those numbers are far beyond, something's wrong.

### Libraries and dependencies used

Depending on the platform you picked, you should be able to track the dependencies in the project. (E.g: Javascript project have a file called `package.json`).

If you stay on the top of pull requests, you will see when someone adds a dependency to your project.

A quick search should give you an idea about what this new dependency is about. Your goal here is to avoid redundancy.

You must avoid massive libraries doing similar things.

E.g: A project using [semantic-ui](https://semantic-ui.com) and [material-ui](https://material-ui.com) or [Bootstrap](https://getbootstrap.com) and [Foundation](https://foundation.zurb.com) together.

Those libraries serve the same purpose. Having both together is useless.

# Conclusion

This should be enough to avoid swindlers. If you are looking for professional software engineers, M-Brane can help you. We believe great communication is the key to successful projects.

We will identify your needs and build the app you always wanted.
Contact us for a free consultation.

# Recommended resources

[The Clean Coder](https://www.goodreads.com/book/show/10284614-the-clean-coder) by Robert C. Martin isn’t too technical and will give you a great idea about professional coding.

[Good Developers vs Bad Developers](https://medium.com/@CodementorIO/good-developers-vs-bad-developers-fe9d2d6b582b) by Codementor
