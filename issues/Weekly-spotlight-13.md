# Friday's spotlight #13

## Tech trend to observe, next gen organization, tech, books and (not serious) tools ...



---



**Hi**

It's time for another Friday pack of thoughts and news from sunny Warsaw. It is Friday's spotlight No. 13 - I should really time it better to have  it on Friday 13'th :). 

Before that, we have a couple of new people - a warm welcome to all newcomers  to this list. I hope you will stay with us for the long haul. 


This week's Friday's spotlight issue has two longer topics and fewer  "links," but I hope you will find it helpful. I highlighted trends worth observing and which might be necessary from your career point of view. 

Before I jump to those topics, I spoke about this week finishing a round of  mentorship within Predica (by pure accident with one of the newsletter  readers). 

**Your attitude and expectations towards the outcome matter a lot.** 

I know. Sounds life-coaching'ish (is there even a word?), but it is  efficient. In many situations, you are the person who approaches the  problem with a certain attitude or outcome in mind. Examples? 

- I have to get this project (while in an interview or sales situation)
- I need to solve this conflict (when challenged with a project situation)


It builds pressure to get the outcome or 'nail it.' This pressure is  undermining your confidence as you perceive one of the possible outcomes as better and desirable, where in fact:

- You can walk away from the project or not close this sale, and nothing significant will happen. 
- You can present your solution and leave it on  the table or accept that the other side behaves not rationally. You need time off or walk away. 

It changes your attitude and gives you more confidence to approach this situation. Try it. 

Now let's jump into things you signed up for in this newsletter. 

​                                                                                                    ![img](https://cdn.mailerlite.com/images/default/spacer.gif)                                                                                            

### Technology trends spotlight 

A couple of weeks ago, I mentioned edge computing as a trend,  fore-fronted by Cloudflare and other cloud vendors. If you are a new  subscriber (welcome) or missed this part, here is the e-mail where I  wrote about it - [Friday's spotlight #11: The need for credibility, Vitalik Buterin, Edge computing - is it a future](https://preview.mailerlite.com/k2z1p0) ... 

A friend ([Jakub Gutkowski](http://gutek.pl/) - you can follow him through his social media) gave me feedback that if someone is not following it, such a brief introduction might be too  short and pointed me out to a great podcast explaining - [Edge computing Computing in Plain English with Lori MacVittie](https://soundcloud.com/codingovercocktails/edge-computing-in-plain-english-with-lori-macvittie).

BTW: If you want to experience Edge computing on your own, you can play[ Doom in your browser, hosted on Cloudflare Edge network with your friends](https://silentspacemarine.com/). 

​                      [ ![Doom on Edge network](https://bucket.mlcdn.com/a/2947/2947243/images/a80960d6c8e359fe44df38a61ada36ac78fd7461.png) ](https://silentspacemarine.com/)                    

Good, old-school gaming in multi-player node, running on an edge  infrastructure (it means it should run closest to your browser for each  person playing).

This week there was an MS Build conference. I have to admit I need to watch  it - instead of watching it live, I prefer for others to screen it for  me, highlight what important, and then watch it at 2X speed. No catching the rabbit here, you see only fight for a status who will bring the  news first, and I opted-out of it. 

How does it connect to Edge mentioned above? There was one interesting and  one of the key points with Microsoft presenting the ability to run some  components of Azure on other clouds. - [Build cloud-native applications that run anywhere](https://azure.microsoft.com/en-us/blog/build-cloudnative-applications-that-run-anywhere/).

What trend do we observe here? There are two which I spotted some time ago and watched as a part of my sensing machine ([my blog post about it](https://www.onyszko.com/sensing-machine/)).

**#1 - Infrastructure is being pushed further, down the value chain** 

Infrastructure running then code is being pushed down the value chain. Infrastructure  won't kill it , but over time, we will rely more on infrastructure, be  it VMs or K8s clusters, begin provided and abstracted for us by cloud  vendors. It is not going away, but it isn't something most of us will  have to handle or think about. 

The focus is on the higher layer of technology - frameworks, serverless,  edge computing where new patterns and practices emerge. You will see  more and more abstraction over the infrastructure layer and de-coupling  infrastructure from actual applications. 

Is infrastructure going away anytime soon? No way. It still will be big.  Why? The answer is inertia (another self-promotion with my blog - [Avoid inertia! How to thrive in years to come?!](https://www.onyszko.com/avoid-inertia/) ). Companies are now asking the question, "Should we go to the cloud?"  or start a transformation. It will continue for years to come, and it  will drive infrastructure usage and consumption. Cloud vendors will like it - not a complicated thing, already commodity for them - it  translates into higher margins and cloud consumption (no data to back it up, my opinion).

What does it mean for you? Even in a cloud world, there are emerging  patterns that seem pretty stable (no breakthroughs, more like constant  innovation). Observing those and looking for your space in it or  switching to it might be beneficial in the long term for your career and value on the market. 

What are those patterns and practices from my point of view (disturbed and biased by my information bubble, be warned):

- Serverless and edge application architecture patterns (with all additions around it for operations, monitoring, testing, etc. )
- Security in applications based on serverless and Edge architecture 
- Financial operations and architecture for cloud 
- Security in operations and product development 

I will look at those areas for my next career move in the cloud computing area if you want to stick to a more established technology area. Why  more established? Those are things that are already known and are  emerging as an evolution. 

We are in the transition period where new patterns will appear based on  what is happening in the crypto space right now, but it will take a  couple of years to settle it down. First movers might get an advantage,  but it comes with a risk (and potential reward). 

**#2 - Cloud vendors will go after other cloud and traditional vendors businesses** 

What is behind your cloud? Other people's clouds! 

The market has matured in some areas to the point that all vendors provide  the same (or almost the same) set of services. There are differences,  but at a high level, you can see that those offerings match. 

Cloud technology is also built on top of APIs and standards. It has the  advantage - it created the DevOps and entire practices around the  creation and operation of the cloud resources. Still, also it allows  other vendors to use your cloud if they want. You can't block them  without blocking your customers. Of course, you can stop them at  licensing level. Still, it would be inertia, and it would create an  additional level of FUD for your customers as well. 

What it enables? Cloud vendors are going after other vendor's cloud. Examples? 

- AWS going with EKS Anywhere after deployment and management of K8s across all platforms
- Azure going after cloud security with its Security Center and Azure Sentinel 


What is the next stage in this trend? Last Build conference brought the ability to deploy some components of [Azure on other clouds using Azure Arc](https://azure.microsoft.com/en-us/blog/build-cloudnative-applications-that-run-anywhere/). Why I found it interesting? 

- It uses an already industrialized component of  infrastructure to make it happen - K8s, which is available on all  platforms and delivered as a standardized service. 
- It is pushing infrastructure lower in the visibility of the user/developer (see earlier part) 
- It is industrializing the framework on which  applications are built. Use any infrastructure, but this will allow you  to run them anywhere. 
- It can be applied in the same way on other layers like Edge. 

Will it be a successful approach? I don't know. It might fail or be changed  over time, but there will be another attempt on it. Why? Because the  business of other providers is where you want to expand. 

What are the other consequences? Cloud vendors will step in on the market  and cut even more of it for companies delivering services for  on-premises or even for a cloud, but focused on infrastructure or  standardizing the environment. I would not bet my career right now on  VMWare, OpenShift, RedHat, and similar skills. Same for on-premises or  traditional security vendors for some components. 

Your point of view on this one? 

​                                                                                                    ![img](https://cdn.mailerlite.com/images/default/spacer.gif)                                                                                            

### Change spotlight - is your organization a "next-generation organization."

COVID pandemics accelerated a lot of changes. Those were on the way, but  years ahead and this unexpected event accelerated them. Now when we are  starting to get over it (still some bumps are on the road ahead of us),  there will be two types of organizations:

- Traditional - trying to behave as nothing has changed and not trying to adjust
- Next-generation - trying to figure out how to operate in this changing environment

Next-generation organizations were already on the way, but as I wrote - this even has  accelerated it. Why might it matter for you? Let's assume we have a time machine, and someone tells you how next-gen organizations will look  like in ten years from now. Would you like to choose to be in this  "next-gen" organization or keep in the "traditional" line with the  potential to be left behind? 
Simon Wardley (I introduced you already to the guy) did that kind of "sampling" of signals ten years ago and  came with the following characteristics of organizations for the "next  generation."

​                      [ ![img](https://bucket.mlcdn.com/a/2947/2947243/images/5b1e7a35376b4d330377c09680166b26a221130b.jpeg) ](https://swardley.medium.com/how-organisations-are-changing-cf80f3e2300)                    

Is it familiar? Pretty much after ten years, we see organizations with  those traits as successful ones, and for sure, those are places you  would like to be. 

Simon is a researcher, and he repeated his "sampling" now to sense what might be a "next-generation" organization for the next ten years. Here is a  table with a result for you to take a glance at. 

​                      [ ![Traditional vs Next Gen organizations - next ten years](https://bucket.mlcdn.com/a/2947/2947243/images/43a9a05456506274e9673f1a3f5da4946301865a.png) ](https://swardley.medium.com/how-organisations-are-changing-cf80f3e2300)                    

Here is a link to the entire study - How organizations are changing. It is a long one, and I bet many of you will not go through the whole study, so I want to highlight one thing from it. People who see their  organization as "Traditional" also predict that it will decline over the next ten years.

​                      [ ![Views of the Future](https://bucket.mlcdn.com/a/2947/2947243/images/26454b4af9f9647f5f58e3734bc87d2b4c2941d5.png) ](https://swardley.medium.com/how-organisations-are-changing-cf80f3e2300)                    

Why may you want to think about it? You may want to assess if your  organization is more on the "traditional" side or "next generation" and  how it is adapting to the new reality. If you see that it is leaning  towards the "Traditional" side, you may want to ask yourself a question - **do I want to be here**? 

I don't have an answer. It has to be your answer. 


***Disclaimer:** As the author states, all models are wrong, and this study might also be biased. As any study. We will see in ten years.* 

​                                                                                                    ![img](https://cdn.mailerlite.com/images/default/spacer.gif)                                                                                            

*If you like my Friday's e-mail want to send this to a friend so they can get these emails too,[ here's the link](https://signup.onyszko.com). I**t would also make my day if you shared this newsletter on Twitter. Share it with people through [this tweet I prepared to make it easy](https://www.twitter.com/share?text=I+read+this+@tonyszko+newsletter+and+I+think+you+will+enjoy+it+too:&url=https://preview.mailerlite.com/r9f3l8).*

​                                                                                                    ![img](https://cdn.mailerlite.com/images/default/spacer.gif)                                                                                            

### Bookmark's spotlight

This week will be shorter as I covered a lot already.

**On the Internet!**
I keep exploring things as part of my sensing machine. Right now, I read  and educate a lot around technologies based on crypto, but for the  utility part, not the financial part of it. I've found this article a  good starting point and explaining a lot about Ethereum, what it is,  what changes are coming, what might come out of it. 

Check it out - [Own the Internet: A bull case for Ethereum](https://www.notboring.co/p/own-the-internet).  As you can get from the title, the author has a bias towards the  success of Ethereum. Still, anyway, I've found it interesting and  informative. 

**The Limits to Blockchain Scalability** 
Here's a good one from the solid engineering side of view - again on a crypto  side (I have to check the depth of my rabbit hole here). 

Coming from Vitalik itself, a profound explanation from an engineering point  of view what are the limits on scalability of blockchain - [The Limits to Blockchain Scalability](https://vitalik.ca/general/2021/05/23/scaling.html) 
Worth reading if you want to have a solid understanding of the fundamentals of technology. 

​                                                                                                    ![img](https://cdn.mailerlite.com/images/default/spacer.gif)                                                                                            

### Books spotlight

I recommend this book - [The Art of Leadership: Small Things, Done Well](https://www.amazon.com/Art-Leadership-Small-Things-Done/dp/1492045691) - for those in a leader or manager role. Simple, down to the point,  based on the author's experience. You will appreciate it as a small  developer's team leads or goes into more people manager's roles and  projects. 

​                                                                                                    ![img](https://cdn.mailerlite.com/images/default/spacer.gif)                                                                                            

### Tools spotlight

This time it will be on a not-useful side of tools. You've been warned. It  is Friday - let's give ourselves something less serious. I [watched Scott Hanselman's session](https://www.youtube.com/watch?v=EWYYgEkGJfs) on Microsoft Build and spotted a little sheep on his screen. A quick search through Twitter topics and ... [eSheep ](https://github.com/Adrianotiger/desktopPet)is back and in 64-bits. 
Not doing anything useful, a nostalgia thing (it was a toy back in Windows 95 days). Here it is writing this e-mail to me. 

​                      ![eSheep writing this post](https://bucket.mlcdn.com/a/2947/2947243/images/a40a2d814359acad2688c7680eb5a7fe4fa8eb51.png)                    


That's it for this week. I hope you found what you looked for in this e-mail.  As always - write to me with questions, comments and keep nudge me if  I'm not holding my commitment to respond (thank's Alex). 


Till the next time, I'm hitting off for a weekend in the countryside.