---
layout: post
title: "First Post and Servers"
date:   2018-03-19 16:02:38 -0700
categories: tech 
---

Well this is the first one huh? The main reason I wanted to start this blog is that I could never find someone's blog that chronicled how they went from not working in tech to breaking into the industry and their subsequent growth. At most what I would find would be a single article about learning Rails in like 3 months and then somehow ending up working as a developer for Snap

I have to admit I already work in tech, but I started it all being self taught. I have always been a computer nerd, and never realized that I could make a living off it.

The other reason I started this blog was to learn how to deploy a simple app to AWS. I currently use GitHub Pages, Heroku, and Surge.sh to host all my content, but I really wanted to learn how to basically do more enterprise and nitty gritty type hosting

That's actually why I used Jekyll as the framework to build this blog since it's pretty simple and I don't want to spend a couple hours setting up a Rails app to do this.  

Here are the steps I took to get this blog on AWS:
I will also include links at the end of the post with the tutorials and 
information that I found particularly useful

#### 0. Pre-Reqs
* I built a simple bare bones blog app using Jekyll so that I could have something to deploy.
* Have already done something like added a custom domain to a GitHub Pages site

#### 1. Get a domain
Seriously get one they aren't that expensive and you can do a whole lot with one. I just got a .tech domain they are pretty cheap and if you are a student with a student email you can get one for free for one year. 

One thing I highly recommend is learning about how DNS actually works since it's one of the most important parts of the internet, and seriously it's not that complicated just sit down with it and try to mentally figure it out once you do you'll have what an old professor of mine called a Walden Pond Experience

I would also recommend against using Route 53, for security reasons. The more concentrated your hosting is the more damage someone can inflict if they get access to it.

#### 2. Get AWS free tier
This is pretty self explanatory most places you have to pay as you grow. AWS offers a free tier that for my purposes is enough and it's free for a year so that is nice.

#### 3. Deploy to AWS
This was where things got a little tricky since AWS wants you to use Route 53 and the tutorials online are either not thorough enough, 
or they have way to much tangential stuff you don't need. I found a very good tutorial by Chuck Grimmett. I didn't do the subdomain (www)
section since I just wanted the bare bones path to work. Eventually I will fix that.

#### Future ideas
* I want to move one of my apps to AWS since Heroku free tier is so slow
* I used an S3 bucket to host the app, which won't work for more complex applications
* I also want to have a fancy mail server with that domain I have

#### Useful Links
[Creating a Jekyll app]

[Hosting your own Linux server pt. 1]

[How DNS works]

[Custom domains for Github Pages]

[Understanding TTL or why is my CNAME not working?]

[Creating a Jekyll app]:https://jekyllrb.com/

[Hosting your own Linux server pt. 1]:https://www.youtube.com/watch?v=SlEQ6GGIyBc

[How DNS works]:https://cr.yp.to/djbdns/intro-dns.html

[Custom domains for Github Pages]:https://help.github.com/articles/using-a-custom-domain-with-github-pages/

[Understanding TTL or why is my CNAME not working?]:https://mediatemple.net/community/products/dv/204644120/understanding-ttl-(time-to-live)
