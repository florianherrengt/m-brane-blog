---
layout: post
title: "From idea to product — Part 3: Create your product with existing tools"
description: "This series of articles is targeting entrepreneurs who want to build a tech product. We will explain how to transform ideas into products based on previous experiences."
tags: [Entrepreneurship, Startup, MVP, Product]
---

[Part 1: Define your product from your idea](./idea-to-product-1)<br>
[Part 2: Get your early adopters without writing code](./idea-to-product-2)<br>
[Part 3: Create your product with existing tools](./idea-to-product-3)<br>
[Part 4: Build an app that doesn’t scale](./idea-to-product-4)

# Create your product with existing tools

Most products relying on apps have the following features:

- Authenticate users
- Display, collect and manage data
- Something that makes it special
- Display the outcome
- Collect payments
- How can we do this without writing any code?

We will be using the following products:

- Your favourite email client
- Typeform or Google Form to create and manage forms
- Trello to manage tasks
- Google Sheets to store and manipulate data
- Zappier to glue everything together
- Xero for accounting and invoices
- GoCardless to take payment

# Email

Building a user authentication system is time-consuming and expensive. There are 3rd parties to help you but you will have to integrate them into your product.
The product is based on email exchanges, you can identify users using their email address.

# Google Forms or Typeform

Building your own form means dealing with different browsers (particularly Internet Explorer) and responsiveness (desktop and mobile).
Google Forms and Typeform already took care of it for you. You might be limited if you need advanced kind of inputs or logic. But this means even more work if you want to build it yourself.

# Trello

You have to manage the work you have to do.
Creating columns “To Do, In Progress, Waiting For Payment, Done” is a good start. There are many alternative available but Trello is easy to use and flexible enough to adapt to most of your needs.

# Google Sheets

Spreadsheets are powerful. Actually, they are so powerful that many 6–7 figures companies rely on well-crafted spreadsheets to operate. While they will eventually be replaced by software solutions, it proves that it is possible to go a long way with them.
Have a look at all the features Google Sheets offers.

# Zapier

As the complexity of your workflow increases, you can reduce chores and mistake by automating things with Zapier.
Use it to automate many jobs like creating new cards in Trello when a user submits a form or updating your spreadsheet.

# Xero

When you make money, you have to deal with accounting. You will pay for the tools you use, collect payments and pay taxes. It’s tempting to focus only on growing the business but it’s important to keep an eye on your money and where it goes.

# GoCardless

You can easily collect payments via Typeform but there is another effortless solution. Send PDF invoice via Xero and combine it with GoCardless. Your clients will receive an email with their invoice and a link to pay it. It’s a great way to collect payment and keep your accounting up to date.

# Third parties

There is an endless stream of products you can use to help you. They usually have ways to communicate with other products (e.g webhooks or Zappier) or export data to standard formats (e.g csv).

Keep in mind that a virtual personal assistant can help you with many tasks.

> “80% of results come from 20% of effort/time” ― Vilfredo Pareto

# Example

Let’s go back to the previous product example, the real estate investment analysis.

1. The user fills up a form with all the information needed including an area to research
2. Send an email to confirm the order.
3. Create a card in the “To Do” column in Trello.
4. Move the card to “In Progress”. Use import.io to extract the required data from various websites and export a CSV file.
5. Use formulas in Google Sheets to calculate things like ROI or average price.
6. Export to PDF.
7. Send an email with the result attached.
8. Create an invoice in Xero. Move the Trello card to “Waiting For Payment”.
9. Move the card to “Done” when you received the money.

Now you have a working system and you should know enough about your product to build an app.

Revisit the design you created at the beginning. It’s a good time to use the knowledge you acquired to update it.

# Recommended books

- Automate the Boring Stuff with Python by Al Sweigart contains step-by-step instructions to automate common tasks. You will be able to transfer this knowledge to many other things.
- The 4-Hour Work Week by Timothy Ferris has some interesting idea about how to outsource your work
- Profit First by Mike Michalowicz reminds us that things are not as simple as “Increase sales and the profit will take care of itself”

# Recommended articles

- A Pest Control Service Created an MVP With No Coding
- What can you do with Sheets?
- Creating a horse racing Tableau dashboard from data scraping

# Read next

[Part 4: Build an app that doesn’t scale](./idea-to-product-4)
