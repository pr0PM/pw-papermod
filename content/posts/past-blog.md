
---
title: "Building a blog without static site generator in 2022"
date: "2022-04-03"
draft: true
summary: "Building a blog without static site generator in 2022"
---

Going back to the old ways until I scale this site...

Using static site generators is easy, choose a theme, claim ownership by editing config few files and voila we're up and running. All that is left is to generate content and format it into markdown files. Use github pages and you don't even need to bother about domain name configuration anymore.

This will get things done, it's the most efficient way to diy, but isn't as adventureous.

Want to know what you missed? Check out my upcoming blog about things that I learned while setting up this blog which is a 10 min guide to learn about easy way to use css, getting perfect lighthouse score of 100 and setting up SEO and bring your website on top 5 google search results in the first week.

#### Searching themes
At first I was planning to clone some openly licensed blog and make some customizations, and I still have around 3-4 unfinished themes lying in the dump. I even tried cloning some hugo themes, but this was taking too long.
The search for inspiration took me to my mastodon account where I landed on kev's post about simple.css and was instantly sold (tbh this is the first css framework I ever used, yes that's how distant I've been from frontend).

#### fASTf0rward >>
Without wasting more of your time the next steps were clear after reading the simple.css demo page and I had the boilerplate ready, which currently is being hosted on gh-pages -> netlify (customizability) -> cloudflare pages (since i'm managing this domain here).
All of the above services get the job done but gh-pages lacks customizations (to edit headers) that's the sole reason to skip it.

#### The end
This initial setup of the blog included setting up SEO, opengraph, getting perfect 100 on lighthouse and getting A+ score on mozilla observatry. I have plan to cover the above steps in a separate well organized post. 
