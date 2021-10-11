# Weekly spotlight #27: 

## What you changed in your defaults? 🔥How IBM lost cloud? Netflix and security at scale? New tools, Azure cloud links, books ... and more 



---



Hi 

I hope you enjoy the beautiful weather whenever it finds you. In Poland, we are in this time when autumn breaks and when the world looks just stunning when the sun shines. This week there were a lot of suns here, and the world looks better because of it :). 

 

## Random thoughts on defaults 

The place where you live matters a lot for different reasons. Your well-being, how you spend your time, with whom you interact, and how. One thing is obvious, but it is well worth mentioning here - the last two years made a massive change in how people approach it. 

You likely had this choice before: work where you want, move to other places while still keep your job of finding a new one remotely. For some of us it was given, but we have rarely used it at the same time. Why? 

Because our environment around us was not encouraging us to do so. 

Fast forward the last two years to the moment we are now. I speak with many people about why they want to change the job, and one thing stands out. People have learned to appreciate their life more, the place they live and how it matters for them, and how they spend time. 

People run away from places:

- Which does not give them a choice about how they want to work and from where.
- Force them to come back to the offices full time.

It is not a revolt against the world order, but someone who realized that he can get a couple of hours back every day now does not want to give it up in exchange for what? Commute? 

Those things sound obvious, but the exciting part will be to watch how this will impact our society in the long term. People who will stay in their homes more will start to notice their surroundings and care about it fully?

Those hours you get back every day will not be spent in front of the TV. People will use it to do more, but not necessarily to do more at work. They will pursue their ideas and hobbies, spend this time with families or go out and exercise more. 

I see it as an opportunity to change our society in many ways for the better. Why we needed the pandemic period to make this switch? Because we accept the world with its defaults as a way it is, and it is hard to change. 

Once we are getting back to "normal" with pandemic (or not) becoming our business, as usual, it is vital to ask yourself a question: what do I want to do with this change and time I suddenly got back from other activities. 

It is an important question I have kept asking myself recently as well. Quoting recently late Abel Wang mentioned few e-mails back - "Don't Accept the Defaults." The question is what defaults you have experienced so far you want to change now. 

On the other note ... 

This week I had to do a bit of tinkering with good old stuff, write a piece of code, restore some files from failed NAS box (I bought it in 2009, and it still worked until now). I have to admit, getting things dirty with stuff like this is still fun. It is fun, but I couldn't do it full time. 

Having a failed Linux NAS drive mounted in the WSL and copying the files from it through Windows Explorer on Windows 11 still makes me think about how much has changed over those years in the way we work with technology. 

It is a great moment to be in this industry. 

With this, let's jump to this week's portion of spotlights. 



## Bookmarks spotlight

Oh, my boy, this week is loaded, I've done a quick count, and I have 30 links stored in my Obsidian note for this edition. Of course, I will not put all of them, but the choice is hard. 

First, a minor errata to previous week's content; I forgot to link an article ["GitHub Codespaces vs. Gitpod – Full Stack Development Moves to the Cloud,"](https://www.freecodecamp.org/news/github-codespaces-vs-gitpod-cloud-based-dev-environments/) so with it, I'm fixing this mistake. Thank you for pointing it out, [Kuba](https://twitter.com/gutek).

Now, let's go with this week's portion of links, news, and resources (no China this week :), a bit more on tech ). 

### How's IBM lost its war on public cloud

Here's an excellent piece - [How IBM lost the cloud](https://www.protocol.com/enterprise/ibm-lost-public-cloud). I think they lost by starting it all together and trying to catch up. It was too late; Amazon had a massive head-start, Microsoft had come late, but its leadership (shout to Satya) managed to do some things right to land where they are now. The interesting thing will be watching Google for the future. 

It is an excellent case of how a company lost not because of lack of capital or technical talent but because of lack of situational awareness and its culture. Even trying to compete on the IaaS when they started was, in my opinion, a mistake. It is summed up nicely in [Simon's thread on Twitter](https://twitter.com/swardley/status/1443611460438011905?s=20). 

After I wrote about it on LinkedIn, I got some private messages that confirmed their efforts were in a dire state. 

Does it mean that IBM is gone? No way - they will be around for a long time, and I wish them well. Hopefully, they will find their space with the right moves, but unfortunately, what I see on the market are not the right moves (which confirms what Simon wrote in his thread). It is about pushing customers towards on-premises solutions, which will cement IBM's presence at the customer site. 

### Risk on the building of other people's platforms and not taking security seriously.

I've stumbled about this cry for help on Medium with a story - [How Google destroyed our startup by terminating our Google Play Developer Account](https://medium.com/@sixacegames/how-google-destroyed-our-startup-by-terminating-our-google-play-developer-account-6a8cca09ea88). In short: after three years of work, a small game studio is done because Google shut down their Google Developers Account and cut them off from the platform. 

That's the risk many businesses are now facing - building a business on top of significant players' platforms, which is totally outside of their control. The same is true with many communities making on top of Facebook without its platform or place. If you are one of them - consider this as a risk.

Interesting in this piece is an attempt to find a reason for Google's decision by company and its conclusions. One possible thing - they suffered a security breach, and as a part of it, their Google account was compromised and used by someone. 

From these reasons they found out, I think this is the most likely one. Someone destroyed this business (hopefully, they will find a way to salvage it) as collateral damage of ransomware. Nothing personal; it was most likely a bot used to extract money with no human intervention. 

Take care of your security, kids! 

### Pave the way Wall-E- Securing Netflix Studios At Scale

Here's a piece from Netflix - [Securing Netflix Studios At Scale](https://netflixtechblog.com/the-show-must-go-on-securing-netflix-studios-at-scale-19b801c86479). It is not interesting because of the tool itself, but for me more because it shows how changing the approach to the problem might bring better results. 

We all know security checklists (do we?). We all know that people find following it hard. Mistakes are made. Netflix faced the same problems but at scale. It could focus on making dev people's lives hard or ... pave the way. They choose the latter. 

Instead of enforcing hundreds of things and policing the developers, they gave a choice. Live with a checklist or use Wall-E, and we will handle it for you. Think about it - it is so different than 99% of security departments choose to do. Make life easier for developers by giving them a service that handles things for them, controlling it. 

We need more thinking down this road in the industry. 

From a technical point of view, I'm more than happy to read this: *Our second observation centered on strong authentication as our highest-leverage control. Missing or incomplete authentication in an application was the most critical type of issue we regularly faced, while at the same time, an application that had a bulletproof authentication story was an application we considered to be lower risk.* 

My professional experience tells me it is true. Good to have it confirmed by Netflix. 

### Hey Astro! Would you welcome Amazon "Wall-E" in your home

Have you watched a "Wall-E" movie (considered by some a horror story about our future in a climate crisis)? Do you remember a cute robot trying to clean up the world? 

 

Amazon announced many new products, and among others, the world welcomed "Astro," a home surveillance bot. Here's a piece about it - [Life with Astro: What it's like to use Amazon's robot in your own home](https://www.fastcompany.com/90682103/amazon-astro-home-robot-hands-on).

An author wrote about a "two weeks trial." I'm not sure if it was a trial of the user for technology or Astro is a trial of Amazon how people will adopt such tech in their home. My thinking leans towards the latter, and I think we will find such tech more common regardless of our personal preference. Have they ever heard about [boiling frogs](https://en.wikipedia.org/wiki/Boiling_frog) :)? 

Would you keep Astro at home? 

### Speaking about Amazon - what is Bezosism?

Speaking about Amazon, one thing that constantly builds controversy about how it handles its fulfillment centers and people working in those. Here's a piece covering it from WSJ - [The Way Amazon Uses Tech to Squeeze Performance Out of Workers Deserves Its Own Name: Bezosism](https://www.wsj.com/articles/the-way-amazon-uses-tech-to-squeeze-performance-out-of-workers-deserves-its-own-name-bezosism-11631332821?mod=djemalertNEWS).

As you can see, they coined a new name for it, and it was invented to give a negative vibe to it. Regardless of the author's point of view, knowing what goes behind the convenience of next-day delivery is good.

Behind every convenience in our life, there is someone who pays the price. 

### Do one thing well. Then compose

Here's a piece from the Applied Complexity blog - [Doing Many Things by Doing One Thing](https://appliedcomplexity.substack.com/p/doing-many-things-by-doing-one-thing) (blog and its author worth putting on a "to watch" list). Why I've included this one? 

More often, when facing a choice of a tool or device which does things, I lean towards this one, which does one thing and lets me connect with others. Focusing on a single item makes those tools fulfill this single thing much better than multipurpose tools. 

A recent example: I was looking to refresh my e-Ink device (my Kindle is 8yrs old, still works great but a bit worn out). The choice was an e-Ink tablet for notes and reading or separate devices. After consideration, I went for a refreshed Kindle for e-books and reMarkable for note-taking (Interested in review? Drop me an e-mail). 

I'm probably missing some things on a tablet, but I have two devices that let me focus on doing only one thing with them and not be distracted by other things. It has value. 

### Cloud repo extravaganza - a couple of tools I've found in recent weeks 

There is a couple of tools and reports on the more technical vibe I've found in recent weeks, and I've decided to group them here. Maybe you will find them helpful in your daily job or for future education (I know at least some of you are in tech). Here it goes in random order. 

[GitOops!](https://github.com/ovotech/gitoops) - GitOops is a tool to help attackers and defenders identify lateral movement and privilege escalation paths in GitHub organizations by abusing CI/CD pipelines and GitHub access controls.

[Azure Databricks MLOps using MLflow](https://github.com/Azure-Samples/azure-databricks-mlops-mlflow) - template or sample for [MLOps](https://github.com/microsoft/mlops) for [Python-based](https://www.python.org) source code in [Azure Databricks](https://docs.microsoft.com/en-us/azure/databricks/) using [MLflow](https://docs.microsoft.com/en-us/azure/databricks/applications/mlflow/) without using [MLflow Project](https://mlflow.org/docs/latest/projects.html#). Very specific, but I think we will see requirements around Data operations and ML operations more and more in the wild. 

It is related to the above for Azure cloud architects - [Enterprise-Scale Analytics and AI - Data Landing Zone](https://github.com/Azure-Samples/azure-databricks-mlops-mlflow). Landing Zone is a well-established concept in cloud infrastructure. This repo gives its version for Data projects deployed on the Azure cloud. 

[KEDA](https://keda.sh/) - Kubernetes Event-driven Autoscaling. Not a new thing, but I think many people still don't know about it. With all my reservations to Kubernetes as a solution to all world's problems, it is good to know it exists. 

[Aziz](https://ridicurious.com/2021/04/08/automated-azure-infrastructure-diagrams-with-powershell/) - Azure infrastructure visualization in Powershell. We all love diagrams; this tool might make preparing them a bit easier. 

[Kubescape](https://github.com/armosec/kubescape) is a tool for testing if Kubernetes is securely deployed as defined in [Kubernetes Hardening Guidance by NSA and CISA](https://www.nsa.gov/News-Features/Feature-Stories/Article-View/Article/2716980/nsa-cisa-release-kubernetes-hardening-guidance/). 

[AllStar](https://github.com/ossf/allstar) - is a GitHub App installed on organizations or repositories to set and enforce security policies. Its goal is to continuously monitor and detect any GitHub setting or repository file contents that may be risky or do not follow security best practices. 

I think for this week I will stop here. 

### Debriefing facilitation guide 

Things go wrong. Sometimes things go terrible. What is important is how we learn from it and how to capture this learning. Doing a good post-mortem or problem analysis is not easy. I stumbled upon this PDF - [Debriefing Facilitation Guide](https://extfiles.etsy.com/DebriefingFacilitationGuide.pdf) from Etsy. After the first glance at it, I intend to read it as a whole and keep it bookmarked for the future. 

How are you doing debriefs and post-mortem? Any specific method you are using for it? 

This section is long today ... and still, plenty of links moved to the stash for the next week. 

## Books spotlight

Another one added to a pile - [How to Live](https://sive.rs/h). Primarily because of the author, [Derek Sivers](https://sive.rs/about), and his approach to life, which I have to admit is close to mine in some areas. Pile is growing and being un-loaded with reading in progress, so few reviews are coming soon. 

I am currently reading through ["The Revolt of the Public and the Crisis of Authority in the New Millennium,"](https://www.amazon.com/Revolt-Public-Crisis-Authority-Millennium/dp/B07K6Y6KGZ/) mentioned in a previous e-mail. In the context of the book, you may want to read an older piece from HBR (not a huge fan but still, some pieces are good) ["Understanding "New Power."](https://hbr-org.cdn.ampproject.org/c/s/hbr.org/amp/2014/12/understanding-new-power)

## Tools spotlight 

I've onboarded two new tools around the lifestyle, and I'm giving it a try. 

[Exist.io](exist.io/) is the one I started a trial with this week. Exist gathers information about what you do, your lifestyle, health, work habits and tries to give you hints about your life and correlation between those. Now - it is mixed feelings. I have some concerns because it is a lot of data in a single tool. On the other side, I'm really curious if I will spot something new out of it. 

So far, I'm in the trial period, and I have to say at least one thing - this tool is nicely done. Good job, Exist, team! I will give you more of my impressions about it in a month after the trial period. 

The second tool is hardware - I on-boarded on [reMarkable](remarkable.com/) as a replacement for paper notes. I make a lot of notes on paper during the calls and meetings. There is a different outcome for me when I write. Not using a computer gives me a different experience during a session. Writing a note on paper is less intrusive and faster. 

For last week, I haven't used a single piece of paper (it still is on my desk with a set of pens, in case of emergency). First impressions - it is remarkable how well this device delivers this experience - writing on paper. On the other side, it provides only this - writing on paper—no fancy integrations, tools, etc. Let's see how our friendship will go :). 

That's it this week. I hope you enjoyed it. As always - if you have any questions, thoughts, or just a random need to chat over e-mail, drop me a line. It goes into my Inbox, and response is guaranteed (no strict SLA). I always enjoy and appreciate those interactions. 