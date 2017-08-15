+++
date = "2017-06-07"
draft = false
title = "An Open Source Stack for Physical Science Startups"
slug = "open-source-science-startups"
tags = ["open source","science","startups"]
image = ""
comments = true	# set false to hide Disqus
share = true	# set false to hide share buttons
menu= ""		# set "main" to add this content to the main menu
author = ""
+++

It is hard enough running a ‘hard tech’ startup. Hardware is one thing, but companies bringing physical science innovations to the world have it toughest of all. Mother nature can be a very cruel compiler.

Do not abandon hope! There are many tools available to help you on your journey. As with most things in life, the best ones are (often) free. Here, I have curated a short list of open source apps and tools that have been useful to us at [polySpectra](http://polyspectra.com). I have split them into four categories: communication, collaboration, lab & engineering, and infrastructure. Hopefully this list will save you some money and make your life in the lab a little bit easier.

<center>
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">It&#39;s not that Unix won -- just that closed source lost. Big time.</p>&mdash; Jeff Atwood (@codinghorror) <a href="https://twitter.com/codinghorror/status/616377394253795328">July 1, 2015</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
</center>

## Communication:

### [Discourse](https://www.discourse.org/)

I pretty much grew up on web forums; I can safely say that Discourse is the first discontinuous innovation in that space in my lifetime. I am confident that this will become the de facto standard. It is also, as promised, highly civilized. At polySpectra, we use a private Discourse forum for long-form discussions and living documents — things that would be inappropriate for chat or email, and would never be read or updated if they just sat in a shared folder. Some examples include our company mission statement and philosophy, operational SOPs, and high-level company-wide updates.

### [Rocket Chat](https://github.com/RocketChat/Rocket.Chat)

I don’t have any problem with Slack in terms of usability, but I fundamentally disagree with their business model. The idea of having my entire company’s internal chat history held at ransom on someone else’s server makes me sick. Perhaps I am being dramatic, but if you actually think about it, that is what a subscription SaaS business model boils down to. Hopefully they have an export feature now.

Rocket.Chat to the rescue. Like most open source projects, it is not as smooth as Slack on the UX side, but it is equally functional. Aside from an issue with mobile notifications on the Sandstorm version of the app, I haven’t found anything else we need missing from Rocket.Chat. We also tried Zulip, but found Rocket.Chat more full-featured.

### [ProtonMail](https://protonmail.com/)

I currently have a love/hate relationship with ProtonMail. I love what they are doing and I think it is a very important service for the world. I am absolutely furious that they have not yet rolled out an enterprise version of the product — which is now basically a year behind schedule. I will throw money at them as soon as it is released. If you only need 5 “@yourcompany.com” email addresses — you can sign up for the Visionary plan. If you need more, you are SOL for now.

One other annoying aspect of ProtonMail is their search. Due to the current implementation of the dual-encryption, at this moment you can only search the To, From, Date and Subject fields. On the bright side — I have gotten a lot better at remembering names…

## Collaboration

### [GitHub](https://github.com/)

GitHub is great…hopefully that is not news to anyone.

### [GitLab](https://about.gitlab.com/)

For those who would rather self-host their git repos — GitLab is a go.

### [Draw.io](https://www.draw.io/)

Draw.io is a nice flowchart app — good for process diagrams, SOPs and “mind-mapping”. It is available as a 1-click install via Sandstorm. Draw.io is as good as LucidChart in my opinion.

### [Wekan](https://github.com/wekan/wekan)

Wekan is a super simple task board, kanban-style. It is also available via Sandstorm.

### [LibreOffice](https://www.libreoffice.org/)

It is tough to avoid Microsoft Office when you are working on projects with multiple organizations…but I would like to give LibreOffice a shout out for carrying the torch after OpenOffice dropped it. I will admit that it can be challenging to work with collaborative document editing with LibreOffice.

## Laboratory & Engineering:

### [eLabFTW](https://www.elabftw.net/)

I am in love with eLabFTW. As a synthetic chemist, this is the electronic lab notebook I have been waiting for (for the last decade). eLabFTW is completely free, yet it is hands-down better than LabGuru, LabArchive and CambridgeSoft’s E-Notebook. Better features, better customer support, better business model — eLabForTheWin. They have done an amazing job of improving the ease of installation and maintenance over the past few years. If anyone at Institut Curie is reading this right now, please give Nico a raise ;)

### [Jupyter](http://jupyter.org/)

In the context of science and engineering, Jupyter makes Python really easy. It is quick to understand for those who are uncomfortable with the terminal, but flexible enough to be very powerful. Think of it as an interactive notebook that can execute scripts for you in the background. For our team, this means that one person can write a script for an experimental analysis, and the rest of the team can just click ‘go’. The graphing libraries are pretty solid as well…perhaps not quite as good as Igor Pro, but close.

### [FreeCAD](https://www.freecadweb.org/)

FreeCAD is not terrible. I am not an expert with CAD tools, but I will say that this is a good place to start if you want a fully free (as in both beer and speech) solution, as opposed to something like Tinkercad.

### [GNU Octave](https://www.gnu.org/software/octave/)

Octave is basically open source MATLAB. ‘nuff said.

### [Processing](https://processing.org/)

Processing is a visually-oriented, Java-based language that is easy to use and learn. It is not particularly geared towards science & engineering, but there some solid libraries that make it useful in certain scenarios, such as algorithmic design of 2D images.

## Infrastructure:

### [Sandstorm](https://sandstorm.io/)

Sandstorm is a unique suite of web apps — you can think of it as an open source G Suite. The containerized security architecture is designed to eliminate many common vulnerabilities, which makes it significantly less terrifying to self-host. The one-click install of updates and new applications means that you don’t need to be a sysadmin to get Sandstorm up and running. Sandstorm also features 1-click versions of many of the apps above, specifically Rocket.Chat, Wekan, GitLab and Draw.io. As a programming novice, this is the glimpse of our open source future I’ve been waiting for.

### [Let's Encrypt](https://letsencrypt.org/)

I feel very strongly that Let’s Encrypt is doing one of the most important jobs on the planet right now. Democratizing access to SSL certificates (aka https://) is a necessary step towards a truly open internet. It is hard to imagine that, only a year ago, I paid GoDaddy hundreds of dollars for a single-site SSL certificate. Now you can have as many as you want for free — all you need to know is how to run a CRON job with [this script](https://github.com/Neilpang/acme.sh). Let’s Encrypt has single-handedly bumped up the use of https:// on the internet by a few percentage points over the last two years — that is no small feat!

### [Firefox](https://www.mozilla.org/en-US/firefox/new/)

Arguably the first open source consumer product ever, Mozilla has been leading the way since Day One. As more and more of our work moves into the cloud, it should go without saying that we probably want to trust our browsers. Guess what? I wrote this article via Firefox.


***
This is just the tip of the iceberg. What did I miss?

Mirror: https://medium.com/@rawwerks/an-open-source-stack-for-physical-science-startups-c83266852efc

