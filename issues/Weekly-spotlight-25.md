# Weekly Spotlight #25: 

## 🖐️ Need for feedback in all of us, Cloud Cost Paradox, Evolution of Trust game, Cloud Katana and other tools, books 📚 and more 



---



Hi 

Surprise, surprise ... not really. Welcome to the next installment of Weekly Spotlight. Trying to be good at the counter and fix it this time shows it is a 25'th e-mail delivered, and some of you are here for this whole time. 

A big THANK YOU regardless of whether you have read it since the beginning or this one is your first one. 

This week I will deliver a set of information gathered through the week - no foundational knowledge or observations from me as an intro. Why? 

Fall arrived with its change of mood and weather, and like every human, I have a mild cold from time to time. Nothing severe, but  sneezing and mild headache are very effective in preventing me from thinking. 

Nothing serious that a bit of rest and hot tea would not cure. At least I hope so because next week I'm planning to run my only running race this year (half marathon). 

Instead of longer form on a specific topic, a few observations I did this week leading workshops and interacting with peers and partners: 



### Challenge your assumptions and judgments. 

Often, things are different than you think, and explanations for what you see around are more straightforward than what you have thought. 

If you assume that something is important or works in a specific way, but nobody told you it works like this; you should seek confirmation of your assumption. Ask; "Look, I think this is important and we should behave in this way, because of X will happen. Is it right?" You will be surprised how often the answer is different than your assumption about it. 

It is especially important when you enter a new environment (e.g., a new job) where you bring all your ways of doing things and assumptions from the last place and environment. Those assumptions might be wrong. You need to open a new book, use your previous experience, and not assume that things are always the same. 

I see this pattern often with new people coming to our organization. I started to expect that it would take three to six months before they would shake all the previous assumptions and behaviors and accept that it is a bit different here. 

Observe yourself and how you think about things you assume, especially in new environments. Be open. Ask questions when in doubt. It will give you a much better experience.  



### All people need feedback, and we need it often. 

It is our feedback loop (wow, Mr. Obvious ;) ). Without it, we don't know if we should correct something or what is more important; we don't know if what we do is good. Without it, even if we do a good job, our perception starts to deteriorate over time? "Am I good at what I'm doing?", "Is what I'm doing worth it?"

Feedback is not only negative or corrective. Feedback is also an appreciation of someone doing a good job or confirming it to someone. It doesn't have to be big or wordy - sometimes simple "look, I liked what you delivered, and it is well done" is enough. 

Ask yourself two questions:

When was the last time you've heard something like it from anyone at your team/company/family? 

When was the last time you said something like it to anyone at your team/company/family? 

We are being taught (at least in my part of the world) that good performance is expected (it starts with an early school experience). Often, only correction or feedback is delivered when you deviate from "excellence." We are not being taught that feedback might also confirm someone having a good outcome or behavior daily. 

The place we often forget about it in our homes and families (at least I need to pay more attention to it)/

Those are two things I've picked up from interactions with various groups this week. Now, Weekly dose of things I've picked up between sneezing from the depth of the web.



## Bookmark's spotlight 

Let's see what the current week brought into my browser. It got much more than I post here, and I'm starting to think not to dump all it on the weekend into some list (all things I bookmarked for myself for a future). 

**GitHub Codespaces vs. Gitpod – Full Stack Development Moves to the Cloud**

I've found Nader Dabit through his work around AWS Amplify, and now he moved into Web3 territory but still produces excellent content for developers. Last week I found his comparison of Github Codespaces vs. Gitpod - two dev IDE environments delivered as a service. Worth taking a look and try it. 

I'm not coding a lot, but I share the pain - setting up a dev environment with dependencies, etc., is a pain in the ass. Both services Nader reviewed delivers two things:

- IDE as a Service - run it and do your work without downloading and setting up the environment 
- Provides its configuration as a code - write a code with your IDE configuration, and it will be started by service to your liking each time. 

IDE delivered as a service, not on the local machine, in the future as it is convenient for people to run and use. This trend and benefits also show how to compute (VMs + storage) become ubiquitous and cheap for us as users.

**Can you trust me?**

I got this link from one of you (thank you, Alex) as a follow-up to my e-mail about long term, no-zero sum game approach. Do yourself a favor and spend 20-30 minutes playing with it and reading it - [The Evolution of Trust](https://ncase.me/trust/).

It takes the game theory and discusses how trust evolves if we play with each other with different behaviors (cheat, cooperate) and patterns. Interesting exercise. Play it for yourself and work on building an environment of trust! 

**You are not so smart to avoid biases**.

Biases are you and in your brain all the time. Can you spot that you are thinking and acting based on the biased view of reality? Here's an infographic, which shows and groups all the types of cognitive biases identified. 

Infographic itself is not that useful other than to be informed, so if you want to pick on this subject, take a look at [You Are Not So Smart: Why You Have Too Many Friends on Facebook, Why Your Memory Is Mostly Fiction, and 46 Other Ways You're Deluding Yourself](https://www.amazon.com/You-Are-Not-So-Smart/dp/1592407366) book. I remember reading it years ago and had my "aha" moment recognizing some behaviors and patterns.

It is hard to avoid bias. It is good to be aware of it and that you are falling into its trap from time to time. 

**Speaking about the cost of the cloud** 

Cloud is not cheap. Everyone who moved to the cloud and deployed something more than a single VM learns that you need to learn how to manage cost. This Andreessen Horowitz (AZ16) study tries to calculate how much company value is lost in cloud bills - [The Cost of Cloud, a Trillion Dollar Paradox](https://a16z.com/2021/05/27/cost-of-cloud-paradox-market-cap-cloud-lifecycle-scale-growth-repatriation-optimization/).

I'm taking a more critical look at this article for one reason: the authors focus on scaled providers of software and SaaS services, where the economy of the service and scale is different than in enterprises. 

For the typical enterprise, where computing is not the primary way of doing business IMO this economy works a bit further, and to judge it, one will have to take into account other factors as well:

- Movement of speed and drag induced by building and maintaining its operations vs. cloud data centers 
- Skills and talents required to be present in the company (for SaaS companies that's part of the core business, for pipe manufacturers not so much)
- The cost of development and operations to be able to move back and forth between the cloud. 

Anyway - it is a good read with a more critical look at the cloud hype (good!) based on the selected companies which AZ16 focuses on. Key lessons from this article apply to all the companies (based on my experience so far) going to the cloud: 

- Cloud spend as a KPI (not only for ops but also for developers and architects)
- Incentivize the right behaviors.
- Optimization, optimization, optimization.
- Think about repatriation upfront (at least as an option and judge if it is worth it for you or not)
- Incrementally repatriate (that depends on your profile and workloads in the cloud).

I tell if FinOps will be the next sought-after skill for a while, and FinOps will be embedded into the development and architecture practice. It is better to have some orientation around it, at least. 

This article also points to a Spotify (again!!!) as an example where this practice was already embedded into developing a product - [Shifting cost optimisation left: Spotify Backstage Cost Insights](https://redmonk.com/jgovernor/2021/04/28/shifting-cost-optimisation-left-spotify-backstage-cost-insights/).

**Digital nomads** 

A lot of people are traveling nowadays and changing places to live and work (or both). I've stumbled upon this site - [Nomad List](https://nomadlist.com/), delivering a great deal of information about the places to live and work and a way to connect with other people living this way. 

I don't plan to change my place of living in a short time, but you never know. I will keep it in my bookmarks, and when winter strikes, definitely browse some warmer locations. 

**What's behind bike food delivery**

We all are benefiting in one way or another from an army of people doing delivery work - food, packages, mail. What's behind it? Here's an excellent editorial on what's behind the scene of food delivery workers in New York - [Revolt of the delivery workers](https://www.theverge.com/22667600/delivery-workers-seamless-uber-relay-new-york-electric-bikes-apps).

What I found particularly interesting in it is how quickly this evolved into an invisible army of people who does the job not appreciated by others (the photo of a guy delivering ice cream during the hurricane is stunning) and how evolution works on every corner of this ecosystem:

- Apps (creating an exploitation system on top of the workers)
- Workers (organization, ways of sharing knowledge and organize themselves)
- Job requirement (electric bikes adoption)
- Industry (the moving mechanics, bike pits, charging points, etc.)

Even if you are not considering this a career choice, it is worth reading to understand how it is evolving and appreciate the next time a guy delivers your food with his bike in the rain. 

**Would you wear glasses with the camera coming from Facebook?**

You can guess my answer to this question (it is a big NO! ), but what is your take on it - [Facebook's Ray-Ban sunglasses let you take photos and video hands-free](https://www.smh.com.au/technology/facebook-s-ray-ban-sunglasses-let-you-take-photos-and-video-hands-free-20210909-p58q9z.html).

Regardless of our answer, it will become an accepted social norm at some point (sooner than later), and it will also spin a new social norm and places to follow it (no spying glasses allowed). For all brands getting one from Facebook is the worst possible choice I can imagine, but Ray-Ban and Facebook think about it differently? 

So what's your take - would you be comfortable wearing those with other people and not caring if they know about it or not? Would you be comfortable around someone with Facebook's RayBans at the party? 

**An account without a password?**

Microsoft finally delivers what was promised a few years ago - passwordless Microsoft Accounts: [The passwordless future is here for your Microsoft account](https://www.microsoft.com/security/blog/2021/09/15/the-passwordless-future-is-here-for-your-microsoft-account/). The option to not use a password has been there for a long time now. What is delivered is the ability to remove passwords as an accepted authentication factor for your account. 

What is your take? Have you removed yours already, or are you planning to do it? 

Short spoiler - for the time being, I keep mine. Why? I'm not using it - I have used passwordless authentication options for a long time now (security key and push notifications), removed SMSs, and other options. Why not do this final step? I need to plan a bit and think if I don't have gaps in my security chain which potentially might cut me off from it (backup security key should do it but anyway ... a thought exercise). 

One thing needs to be given to the Microsoft team - they set the direction and delivered on it in the last few years. 

## Tools spotlight 

This time cloud edition :). Here's not a specific tool but two resources, which might be a good tool for you in a recruitment process: 

[Interview Questions for Senior .NET Developer](https://dshergilashvili.hashnode.dev/interview-questions-for-senior-net-developer) is a blog post that provides a list of topics, questions, and expected levels of answers for the interview of Senior .NET Developer. If you are the person who does the interview or you are being interviewed, it might come in handy as a preparation list. 

Here's a similar tool in the form of a repository - [DevOps Exercises](https://github.com/bregman-arie/devops-exercises). It contains questions and exercises related to tools and technologies in DevOps / SRE roles. Pretty handy and put together, so good to keep it as a reference. At the moment, there are 176 exercises, so plenty to choose from. 

Other tools I picked this week for evaluation by myself or a team (you can do that much on your own) related to cloud projects:

- [Cloud Katana](https://github.com/Azure/Cloud-Katana) - a tool built on serverless architecture to execute and orchestrate security testing on Azure infrastructure. You can read more about it in its official documentation on [https://cloud-katana.com](https://cloud-katana.com/intro.html) (as an interesting note, this site is built as a Jupyter notebook).
- [Litmus](https://github.com/litmuschaos/litmus) - using projects own words (...) LitmusChaos is an open-source Chaos Engineering platform that enables teams to identify weaknesses & potential outages in infrastructures by inducing chaos tests in a controlled way. (...). Not much to be added to it. Interestingly, this project is the [community hub with the definition of those tests and potential outages](https://hub.litmuschaos.io/). 

## Books spotlight

There is nothing new on a read this week (I needed a break), but yesterday, I went on the books shopping spree. I read a thread about the book from Tobi and got to know about the Stripe Press. It turned out Stripe publishes books as a company, and I even read one before ([An Elegant Puzzle: Systems of Engineering Management](https://www.amazon.com/Elegant-Puzzle-Systems-Engineering-Management/dp/1732265186)) and had one already in the "to read" list ([Working in Public: The Making and Maintenance of Open Source Software](https://www.amazon.com/Working-Public-Making-Maintenance-Software/dp/0578675862)).

In anticipation of long, winter nights in Poland, I did load on books from Stripe Press: 

- [The Revolt of the Public and the Crisis of Authority in the New Millennium](https://www.amazon.com/Revolt-Public-Crisis-Authority-Millennium/dp/1732265143)
- [Stubborn Attachments](https://www.amazon.com/Stubborn-Attachments-Prosperous-Responsible-Individuals/dp/1732265135/)
- [The Dream Machine](https://www.amazon.com/Dream-Machine-M-Mitchell-Waldrop/dp/1732265119/)

I will keep you about the progress and reviews here in the weeks to come. 

If you need something to relax your brain after this whole e-mail here, it is - [Quake-like game written in JScript in 16kB of code](https://js13kgames.com/games/q1k3/index.html). Computer engineering is a great thing, and if channeled in the right direction, it can do wonders. The whole question is about which direction we should use it. 

That's all for this week, folks. This e-mail is sent from my mailbox, which means that if you reply with any question, comment, or thought, it will reach me directly. Answer guaranteed, but no SLA on it :). 

If you like this newsletter, share it with your friends - they can sign-up with no effort at https://signup.onyszko.com/. 