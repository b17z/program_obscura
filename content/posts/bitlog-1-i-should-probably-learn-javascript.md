+++ 
title = "Bitlog Entry 1: I Should Probably Learn Javascript And How Web Tech Works"
description = "An Effective Way to Learn"
date = 2018-12-29T20:33:35-05:00
tags = ["bitlog", "entry 1", "learning", "javascript", "web development", "html", "css"]
categories = ["bitlog", "entry 1", "learning", "javascript", "web development", "html", "css"]
draft = false
+++

# A Medium to Express Ideas

I never really thought about web development until recently. I have nothing against it. I just did different things in college and in industry. It was not until earlier this year that I thought I should learn it.

I was going through the typical "computer science biyearly self identity crisis" when I said to myself, "I should probably learn JavaScript". Don't let this scare you from the industry. 

> The only way to cure the "computer science biyearly self identity crisis" is to immerse yourself into projects, learn new things, or deeply learn older things (by older, I mean stuff you already know/have experience in).

I have had so many ideas since before I even started computer science that had to do with expressing information. You'd think that I would have made that connection when I was in high school or earlier that I should have studied programming but no, I didn't until third year of college. The best way to express these ideas in the way that I want without being at the mercy of blogging platforms is web development. There's nothing wrong with blogging platforms but I do have a penchant for design that can't be fulfilled with these platforms.

# Trodding Through the Insanity of Web Tech

So, how do I learn these things needed for web tech? While working at my previous job, one of my close friends did work with web technologies so I asked her about it. Horror stories. Everyone else: horror stories. But the obvious consensus was that the three main technologies were HTML, CSS, and JavaScript.

It's a circus out there when it come to web tech and the opinions of how one should start learning it. There are new frameworks coming out each week; these frameworks keep piling on the features; there are millions (and I actually mean that literally) of ways to do things ranging from simple to incredibly complicated but complicated because it's better for scaling or whatever; there are blog posts that bash and worship the same technologies/features of these technologies... in the same blog. It can turn insiders insane and make outsiders feel hopeless.

# Or The Best Framework to Learn

> If there is absolutely anything that I have a really strong opinion on in terms of learning new things, it's this: You have to learn the fundamentals/first principles of that space. I absolutely do not subscribe to the idea of skipping over fundamentals and trying to learn stuff that is supposed to be built on foundations. It's like trying to build a house without the steel beam framework underneath. I find it absolutely insane that people try to skip over this. I firmly believe it will burn them in the future. If your foundations are built on toothpicks, the more you try to build on that, the more likely it will collapse later.

I know this sounds really harsh and I might be scaring you again but I promise you, in my heart of hearts, I believe this approach is the best approach in computer science.

An example: If you try to learn [React](https://reactjs.org/) without learning JavaScript first, you'll get burned later. I understand there are people out there who would say differently or have done differently but if there is a battle-tested "framework" (ha), it's learning the foundations.

The downside to this approach is that you'll certaintly be slower in the beginning but I promise, you'll be faster later.

# What About Project Based Learning

I believe project based learning is borne from first principles. The natural thing to do is to experiment with your new found knowledge. If you're not experimenting, you're not learning. You can read all the blog posts and technical books you want, if you're not implementing something, then come time to create or execute, you'll have more trouble than normal.

> I am a big believer in endless experimentation. Learn some foundations, experiment. Learn more things, experiment. Experimentation is the lifeblood of this space. If you're not going to bring your inner kid into the sandbox or your inner mad scientist to the lab, then you're capping yourself.

Many of the top companies in this space use the idea of the 10,000 experiment rule. They just keep running experiments internally to find out what sticks.

> I have not failed. I've just sucessfully found 10,000 ways that won't work.

Since whoever said above is up for debate, I won't attribute it to anyone but this is an excellent way to think about computer science. You will succesfully find millions of ways that won't work. Much of your job will be debugging what's wrong. So instead here's a quote from [Paul Graham](http://www.paulgraham.com/) from his essay [Hackers and Painters](http://www.paulgraham.com/hackpaint.html):

> “I tended to just spew out code that was hopelessly broken, and gradually beat it into shape… For a long time I felt bad about this, just as once I felt bad that I didn’t hold my pencil the way they taught me to in elementary school. If I had only looked over at the other makers, the painters, or the architects, I would have realized that there was a name for what I was doing: sketching. As far as I can tell, the way they taught me to program in college was all wrong. You should figure out programs as you’re writing them, just as writers and painters and architects do.” - Paul Graham, Hackers and Painters

# How I Introduced Myself to Web Tech

Now that you got an idea of my insufferable dogma, with that out of the way, let's get into why you're really here.

## What the Foundational Web Technologies Are

1. HTML
2. CSS
3. JavaScript
4. Bonus: I should probably know how the web works at a high level so its protocol would be nice to know: HTTP/S

Note: I won't get into backend development just yet. This is more about crafting frontends because I know a bunch of you will start asking about PHP or Node or some backend based language but we need to build up to that.

Let's start with how the internet works (4).

## High Level Overview: How the Internet Works

### Resources

- [There and Back Again: A Packet's Tale. How Does the Internet Work?](https://www.youtube.com/watch?v=ewrBalT_eBM)
- [How the Internet Works in 5 Minutes](https://www.youtube.com/watch?v=7_LPdttKXPc)
- Playlist: [What is the Internet?](https://www.youtube.com/watch?v=Dxcc6ycZ73M&list=PLzdnOPI1iJNfMRZm5DDxco3UdsFegvuB7)

### Some Background on the Internet

#### HTTP

HTTP stands for Hyper Text Transfer Protocol. This is what makes the internet work because it gives browsers a common language to communicate to servers that hosts web pages. HTTP became standardized in 1991 through the work of [Tim Berners-Lee](https://www.w3.org/People/Berners-Lee/).

Note: HTTP is considered insecure because it isn't served over an encrypted connection which is why there is pressure to move to HTTPS.

HTTP transfers HTML files that would be represented graphically by your browser; Chrome, Safari, Firefox and yes, even Internet Explorer. The big thing to note here is that the HTTP protocol helps us interactively link with different pages. That's how the internet spread like wildfire.

#### The Anatomy of a Link

```
┌───Protocol────┬───────Domain Name────────┬───────────────────────Document URL────────────────────────┐
│    ┌─────┐    │   ┌───────────────────┐  │   ┌──────────────────────────────────────────────────┐    │
│    │https│    │   │programobscura.com │  │   │posts/bitlog-1-i-should-probably-learn-javascript/│    │
│    └─────┘    │   └───────────────────┘  │   └──────────────────────────────────────────────────┘    │
└───────────────┴──────────────────────────┴───────────────────────────────────────────────────────────┘
```

- The https is the protocol
- The programobscura is the domain name
- The document url is posts/bitlog-1-i-should-probably-learn-javascript/

Together these make up an address that your computer is on currently right now as you are reading this specific blog post.

When you type the address into the address bar of your preferred browser (hopefully not Internet Explorer), your computer (also called a client) that is connected to the internet through your ISP (Internet Service Provider) sends something called a request to a web server. At which point, the server will send an appropriate response.

#### The Anatomy of a Request

Your browser does all the communicating for you but we will see a basic example of a request. Open up a terminal and type:

```
telnet programobscura.com 80
```

Note: For Mac Users of High Sierra and above, you don't have telnet anymore so you can substitute with the command:

```
nc programobscura.com 80
```

Or if you want to use telnet and you have homebrew just do a:

```
brew install telnet
```

And then do the first command again.

When you do this, you get this back:

```
Trying 151.101.65.195
Connected to programobscura.com
Escape character is '^]'
```

Now do this:

```
GET /axios/ HTTP/1.1
```

Press enter and then type:

```
HOST: programobscura.com
```

Press enter again and then you will get this something like this back (the response):
```
HTTP/1.1 301 Moved Permanently
Server: Varnish
Retry-After: 0
Location: https://programobscura.com/axios/
Content-Length: 0
Accept-Ranges: bytes
Date: Sun, 30 Dec 2018 03:46:19 GMT
Via: 1.1 varnish
Connection: close
X-Served-By: cache-jfk8141-JFK
X-Cache: HIT
X-Cache-Hits: 0
X-Timer: S1546141579.390533,VS0,VE0
```

At a high level, this is what happens behind the scenes when you request my web page to be shown to you. We won't get into the specifics of everything just yet but the one thing I want you to note is this:

```
Server: Varnish
```

I use [Firebase](https://firebase.google.com) to host this website so I will assume they use a server called Varnish. If I were to use something like [Netlify](https://www.netlify.com/), I'll get their equivalent server. You made a request to this server and this server processed your request and responded with the appropriate web page with the combination of the HTML, CSS, JS that I (and someone else) created for that specific page. I say "someone else" because the browser does inject a lot of things that isn't created by the web developer when requests get sent. Then, the browser translates this HTML, CSS and JS into something that you can read. This process happens on every single request made and has to be done for billions of people at any point in time. Crazy, right?

You can find more information on the videos in the resources section of this part of the post. When I create cuter diagrams, I will share more deeply how the internet works. But those videos are fantastic.

### The Frontend Holy Trinity

Let's talk about the frontend now that we know how the internet works.

First, since I told you that I would talk about backend later, let's briefly discuss the differences between frontend and backend.

![Frontend vs. Backend Development](https://img.devrant.com/devrant/rant/r_1645342_hUdx5.jpg "Frontend vs. Backend Development")

> Frontend development is all the things you see: the cool designs; the cool interactions; the cool information.

> Backend development is everything else you don't see: how the frontend shows information; how the website scales, how the frontend gets information; how the website stores data, etc.

If we were to use an everyday analogy, it would be like a restaurant: The frontend is your plate of food, the backend is the kitchen where the food is made. You don't know how (and hopefully they don't spit on it or worse) it's made but you eat it. Only difference here is that you don't eat the web page that is being served to you (at least, I hope not).

![Frontend vs. Backend](https://static1.squarespace.com/static/5a5f73f5d7bdcef66b1ec204/5a6207e771c10ba72c82ef1b/5ab29223758d46af93cd9065/1523468664033/Front-End+Vs+Back-End.png?format=1500w)

#### HTML

HTML stands for HyperText Markup Language. It defines the structure of a webpage. It is commonly referred to as the "nouns" of the page.

- Paragraphs,
- Lists,
- Images, etc.

#### CSS

CSS stands for Cascading Style Sheets. It defines the style of the HTML. It is commonly referred to as the adjectives of the page.

- Make all paragraph text fuschia
- Make this list have a green background and white text
- Make this image spin around 360 degrees everytime a user hovers over it

#### JavaScript

JavaScript adds interactivity and logic to the page. It is commonly referred to as the verbs of the page.

- If the user clicks on this paragraph, pop out the paragraph, change its color to white, and dim the background
- Load data from Twitter into this list
- Load image from database

# Wrapping Up

I do apologize for cutting this off here but it was getting a bit long. I probably should have put the brief "how to learn" part in a different section or just abstract it into an entire different, philosophical based post but I thought it was appropriate here to get started.

In the upcoming posts, I will focus more towards code, specifically with getting started with JavaScript. I might squeeze some HTML and CSS in some but for the most part, we will be looking at JavaScript since it's a general purpose programming language as well and would be an excellent way to start our journey. There will be whole Bitlogs focused around CSS and how to make web pages look somewhat nice. Disclaimer: I am not a designer.

This may look weird but this is exactly how I started acquainting myself with web technologies. I hope you join me on the next ones!

Another disclaimer: I will try my best to provide some sort of order of how I learned things but my notes are not always perfect and sometimes I don't add dates; this means that some of my notes may be out of order but I will do my best to provide an optimal experience with these Bitlogs!