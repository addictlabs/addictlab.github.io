---
layout: post
title:  "Book Order Bots With Selenium"
date:   2017-1-2 20:13:11
categories: project
tags: 
image: /assets/article_images/2017-1-1-bookbot/websiteImage.jpg
image2: /assets/article_images/2017-1-1-bookbot/websiteImage.jpg
---

# Bots that automatically place orders by getting JSON file

 
# Features

> - Built bots based on Selenium with Python to place book orders by automating browser behavior. Bots were able to login, fill the shipment form, choose different ship options and record the total order price. A super bot would accept an order in JSON format and call each bot by integrating APIs.
> - Used Selenium IDE to record a generic user behavior on Firefox and generate unit test suites in Python. Used Selenium WebDriver to scale and distribute scripts across many environments.




## Demo for textbooks.com bot


![textbook bot](/assets/article_images/2017-1-1-bookbot/textbook.gif)


## Story behind it 
---
It was a pretty amazing experience that 6 of us got together and built 8 bots for bookbandit.com within 4 days. Before that, I had never built a bot and only knew that Selenium was used for browser testing.

Since Andy was going to deliver 8 bots to the client on Jan 2nd, and we started on Dec 27th, we had to work day and night to complete everything from scratch. We actually built a sample version of bots, but the styles varied, we had to use selenium IDE to refactor all bots.

We met all kinds of problems in the process, the biggest one coming from cheggs.com, which would recognize bots behavior if we made bots move too fast or sent requests too many times from the same IP address. So we had to set ```time.sleep()```to make a pause. Other problems came from selecting HTML tags, choosing different paths for different UIs, etc.

Teddy said he used Selenium to do 'evil things' to get concerts tickets, which is what Selenium is so good at. I knew this kind of exploits of bots before, but I did not realize this was how they worked.

Highly-pressed but rewarding journey anyway.
