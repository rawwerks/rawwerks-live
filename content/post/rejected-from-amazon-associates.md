+++
date = "2017-08-16"
draft = false
title = "Rejected From Amazon Associates"
slug = "rejected-amazon"
tags = ["rejected","accepted"]
image = ""
comments = true	# set false to hide Disqus
share = true	# set false to hide share buttons
menu= ""		# set "main" to add this content to the main menu
author = "Raymond A Weitekamp"
+++

(This is the first post in my [Rejected...](/intro-rejected) series)

Recently, I thought it would be fun to [share some of my favorite books and tools](/tools) on this site. My motivation for revamping this site was to lower my own activation barrier to sharing, this seemed like a good place to start. I had recently hung out with Spencer Wright of [The Prepared](https://theprepared.org/) fame, so perhaps his [tool guide](https://theprepared.org/tool-guide/) was in the back of my mind. The meeting with Spencer reminded about the [Amazon Associates/Affiliates Program](https://affiliate-program.amazon.com/) where bloggers and other site owners can earn a commission by linking their readers to Amazon products. Spencer seemed happy with it, so I thought I would give it a whirl. Let the experiment begin:

Unlike Spencer, I was not prepared. I didn't bother to look up any information about the affiliates program other than where to sign up. What I didn't realize was that there is a non-trivial hurdle to being allowed into the program, which makes complete sense because Amazon is giving up part of their profit. Additionally, they have costs associated with running the affiliate program that might outweigh the added revenue if they have too many 'associates' to deal with. 

So you can probably guess that within a few days of signing up, I was rejected. Here's the rejection email:

> Hello,

> Thank you for applying for the Associate program. Upon review, we are unable to accept your application. A part of our criteria is that your site has to be established with enough unique content. We rejected your application due to one or more of the following reasons.

> - Lack of content which is original to your site and beneficial to your visitors
> - Pages that are mainly empty when advertisement content is removed

> Unfortunately, we arent able to review an application once its been rejected. If your website has been further developed and now contains appropriate content, youre welcome to submit another application by using the following URL:

> https://affiliate-program.amazon.com/gp/associates/join

> Thank you for your interest in Amazon Associates.

Well of course there was a lack of content - I hadn't gotten around to importing most of the stuff I wanted to put on this site. In my mind, the tools page with the affiliate links was just part of the experiment of deciding what kind of content I wanted on my site. I wasn't expecting anyone to come snooping around here to review my application. So the clear first lesson learned is: **do your homework**.

The challenge is, there isn't really a ton of information online about what is and isn't acceptable. There are sites that suggest you need a minimum amount of traffic, others that hint at 'high quality content' as the secret to success. [This post](http://corporatetangent.com/public/2014/12/06/amazon-associates-application-rejected-lessons-learned/) claims that one should have at least 15 articles before applying. Paul Hutchings had a [similiar experience](http://www.paulhutchings.me/rejected-by-amazon-associates/) when he tried to set up the links in advance of adding all of his content. His advice: populate the site first, then apply. One of the downsides of being rejected is that (supposedly) some of the affiliate links stop working when you're rejected. (I will test this at the bottom.) There isn't a lot of advice out there, but I at least the '15 article rule' is testable. Now for the fun part - they did invite me to submit another application if my "website has been further developed and now contains appropriate content". Let's hope so!

![My flurry of git commits in response to this rejection](/media/git-commits-rawwerks.png)

*First, I would like to sincerely thank Amazon Associates for rejecting my application, because it gave me the much-needed motivation to add my posts from my old site and elsewhere to this new rawwerks site.* The big advantage of running my site with git and remote hooks is that I have a very clear snapshot of the state of the site [before](https://github.com/rawwerks/rawwerks-live/commit/e612b109bdc3720480994538bd92b6e1aa45574d) and [after](https://github.com/rawwerks/rawwerks-live/commit/053af1218c1211e10646cf82215ac26b30d775bc) I added the tools page, as well as the [state of the site when it was reviewed by Amazon](https://github.com/rawwerks/rawwerks-live/commit/23e615e79288e51677f319d60c3d6278ff84f053).

To put the current collective wisdom to the test, I've now added a significant amount of content, but I've made sure to stay clear of the famed 15 article threshold. This way we might be able to speculate about whether or not this magic number holds the secret to acceptance. This article will be the tenth 'post', and if you count the [music](/music), [science](/science), and [tools](/tools) then we're at 13 'pages'. Clearly, Amazon will likely see this article and may or may not look favorably upon this experiment - but I'm willing to take that risk in the name of the greater good. As to whether or not this is 'quality content', we shall let the lords of the intarwebs decide.

Time for the re-application. This time, I'm smart enough to notice the instructions:
![Your site must be fully developed](/media/amazon-warning.png)

I filled out the profile:
![This site is about awesome stuff](/media/affiliate-profile.png)

I agreed to the terms and conditions. I said a prayer, hoping that it would automatically give me back the prior affiliate link so I don't need to redo my tools page...and I'm back. Unfortunately, the Store ID and Tracking ID are now different from when I first applied, so I will have to redo all of my links on my [tools](/tools) page. To be honest, this makes me kind of hesitant to add items to the tools page, since the thought of re-inserting new links for the nth time isn't particularly appealing. (But hey...I'm in this experiment for the long haul.) Because I used Amazon's link shortener, I can't simply find & replace the old tag string with the new. So instead I'm following all of the links manually and using the SiteStrip to quickly create new links (full links this time in case I get rejected again).

Let the second stage of the experiment begin! You may have noticed in the instructions that my application will be reviewed shortly after I make my first referral. This means that the only way you can accelerate this experiment is by heading over to [tools](/tools) and buying something. *To be continued...*

*...Huzzah I was accepted!* Thankfully this experiment in perseverance was relatively straightforward. It only took about a week and a half, but we can now officially say that the myth of needing 15 posts to be accepted as an Amazon Associate is: busted. I also don't have any more excuses for not adding posts to the site. Back to the lab again...


