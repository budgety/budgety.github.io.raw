---
layout: post
description: "This article focuses on employing functional composition to perform the common task of saving data"
title: "On Values, Principles, and Practices"
tags:
- software
- development
---

A little over a month ago, Robert C. Martin published an article on the 8th light blog titled [Extreme Programming, a Reflection](http://blog.8thlight.com/uncle-bob/2013/12/10/Thankyou-Kent.html). It's an interesting article that outlines how Extreme Programming (XP) changed the software world forever. After reading the article I was amazed by how many of my programming habits, ideas, and beliefs have been informed by XP. The joke of course being that I had never actually read Kent Beck's book.

So now, I am showing up 15 years late to the party. Kent kicks his book off with a treatise on values, principles, and practices. I thought it would be a good practice for me to do my own reflection on this subject, and think about how the current industry I find myself in regards these things.

Values
------
As Kent puts it, values bring purpose to practices. XP embraces five values to guide development.

###Communication###
Problems can arise from a lack of communication. The lack of communication can be between developers, between a client and the developers, between the client and the organization, etc.. In my experience, these sort of problems involve doing the wrong thing for lack of clarification, doing too much for lack of understanding, or doing nothing at all for lack of a much needed response.

To be fair, sometimes problems arise from lack of knowledge. We can't know everything, but chances are someone on your team knows the answer. Communicating that lack of knowledge can go a long way to solving that problem.

The value of communication is one reason I am against one person shows. Some work environments put some kind of odd value on a person's ability to do work by themselves *all of the time*. I've rarely seen these single person shows be a resounding success. Yes it might be possible, but that doesn't mean it's the best solution.

> Communication is important for creating a sense of team and effective cooperation.

###Simplicity###
I think there is tendency for many developers, myself included, to overthink things. There is an odd desire to try to cover every situation or problem that could arise (guilty). We may even go so far as to complicate a problem so we can satisfy some itch to employ a recently learned pattern or tool (guilty). Maybe we want some grand solution that we can later open source for street creds (guilty).

Wherever our drive for extra complexity is coming from, we need to cool it. XP encourages us to ask ourselves "What is the simplest thing that could possibly work?" Naturally that question places a special emphasis on **that could possibly work**. Communication complements simplicity by elminating unecessary requirements and helping us focus on *today's problem*.

###Feedback###
The amount, quality, and frequency of feedback seems to be an overlooked value in my circles. We understand the benefit of stand-ups, but not fully. They are rarely daily, and there is a tendency to focus on "where are we at on this feature" instead of "how is development going, and how can we improve?" We need feedback often and as quickly as possible, and we need time to respond to that feedback.

Once again, our values are tied to one another. Feedback is a good litmus test for simplicity. Simple things are easy to give feedback on, and feedback also allows us the opportunity to simplify things. Naturally communication between team members facilitates good feedback.

When we look at practices, we can see how test driven development and automated tests are great feedback mechanisms.

> The sooner you know, the sooner you can adapt.

###Courage###
Courage allows us to act in the face of fear. I've seen inaction as a result of a developer fearing for their job. I've seen brilliant people stay silent for fear of ridicule. It's become a regular practice to overestimate for fear of consequences on an unmet estimate.

Hopefully you work for a company that doesn't fire you for first time mistakes. Hopefully your team doesn't belittle you for not understanding something, and hopefully estimates are truly estimates and not promises. Whatever your circumstances, if fear keeps you from acting in the best interests of your team, then courage will cure what ails you.

One again this value works in concert with the others.

> The courage to speak truths, pleasant or unpleasant, fosters communication and trust. The courage to discard failing solutions and seek new ones encourages simplicity. The courage to seek real, concrete answers creates feedback.

###Respect###
For some reason, many developers place value on the amount of esoteric knowledge someone has. The reality is, a team is full of people making varying kinds of contributions - that is real flesh and blood humans who wish to bring value to the project.

Everyone involved in a project has value as a person, and software succeeds when team members respect one another, and respect the project. I like to think respect fosters education and growth. Respect means no backstabbing or gossip, and it means a willingness to acknowledge gifts and foster understanding where it might be lacking.

Things won't get done if people don't care about eachother or the project.

Principles
----------
Principles act as the bridge between values and practices. Principles are domain-specific guidelines for life - that is I am a software developer, and these guidelines apply to me as such. Principles may actually guide our actions as developers.

###Humanity###
People make software. Human beings write code. Forgetting this can create a pretty unbearable environment. I certainly don't want to feel like a number in the system. People are social creatures, and this is a principle that ought to guide the creation of teams instead of lone rangers.

People need interaction and intimacy. People want to feel like they are contributing to the team. It's nice to know you are bringing value, and that you are being given opportunities to grow. Knowing you work with humans encourages you to act towards these basic needs and build trust within the team.

I work for a company that is quite fond of using the term "resource" to refer to people that are availble for certain tasks. Now I know these people well enough to understand there is no ill intention behind it. Perhaps I will use this paragraph to politely discourage it's use in favor of terms like "person", "consultant", or "Brian". Something a little more humane ;)

###Economics###
Somebody has to pay for this stuff. Our goal should be to bring the highest amount of value as early as possible. Communication is key here. We need to find out what will bring the most value early, and try to accomodate that sooner. The sooner we can make money with our efforts, the better.

I've seen it way too many times - indeed I've been on projects - where a team will try to gather a laundry list of requirements and try the "lowest hanging fruit" method. This can leave software looking incomplete and invaluable for a good stretch of the project. Scratch that, the software *will* be incomplete and invaluable for a good stretch of the project.

###Mutual Benefit###
Let's do things that benefit everyone. We shouldn't do things that benefit us at the cost of others. I might get my feature done faster if I cowboy code that business and omit tests, but the future inheritors of the project will pay dearly for my sins when they try to decipher my cryptic names and copy pasta.

Things like writing tests, refactoring, and naming methods, functions, variables, and classes clearly not only benefits you, but it also benefits all future developers which in turn benefits the customer. Less time spent on messes, means less cost. We should generally discourage "Every man and woman for themselves" approaches to software development. 

> Mutual benefit in XP is searching for practices that benefit me now, me later, and my customer as well.

###Self-Similarity###
I'm not sure I entirely understood this principle. What I gathered was: the rythms, structures, and practices you have successfully used before are a good starting point. They may not fit perfectly for your given context, but they are a good starting point.

I've created presentation agnostic baselines for [PHP](https://github.com/brianium/driven) and [.NET](https://github.com/OSTUSA/ndriven) systems for just this reason.

###Improvement###
There is no silver bullet. The bottom line is to pick a starting point and actually start. You can keep improving from there. I think alot of our time is wasted trying to figure out "one size fits all" processes. 

> In software development, "perfect" is a verb, not an adjective

###Diversity###
Diversity says we need differences on the team. People with different backgrounds and apptitudes. Diversity dictates that differing opinions and ideas on the same problem all need to be valued.

When conflict arises, it ought to be resolved productively. 

For me its tempting to value perfect homogeny, but this just creates comfort, not valuable software.

###Reflection###
We ought to think about what we are doing, and how we can improve upon things when they are complete. Reflection is important for the individual as well as the team.

Reflection has allowed me to learn no brainer lessons throughout my career. Lessons like "do not reinvent the wheel" and "stop testting getters and setters". This might be common sense to some people, but for a vast majority of us, we learn these things by reflecting on what we did and what did and did not add value.

###Flow###
Let's deliver a steady flow of valuable software. We should not shoot for big chunks of value, but we should shoot for small but frequent chunks of value.

This can be accomplished with things like daily builds and deploys. Let's end our day with working software. I've seen flow get interupted all too easily and then never returned to. If there is a problem in communication or knowledge that disrupts the flow, we should get back to it as soon as possible.

Flow is another principle that is adversely affected by "lowest hanging fruit" methods of development.

###Opportunity###
It takes a pretty major shift in attitude to perceive problems as opportunities for growth and learning, especially when problems are compounding. I've been so overwhelmed by problems before that It's been easy for me to tuck into myself and just try to survive.That is a great way to burn out quickly and start thinking about self rather than team.

It pays to analyze problems and use them as opportunities to try something that works better.

> Part of being extreme is consciously choosing to transform each problem into an opportunity: an opportunity for personal growth, deepening relationships, and improved software.

###Failure###
Failure is not a waste so long as it imparts knowledge. Courage plays into this one. Too many of us are afraid to fail. I've wasted time on "spikes" that serve a purpose of research. This seems more wasteful than trying several solutions to the problem. 

There might be three possible solutions, and all but one fail. Maybe all of them fail. However, those attempts and the knowledge they impart are much more valuable than me browsing stack overflow for 8 hours.

> When you don't know what to do though, risking failure can be the shortest, surest road to success.

###Quality###
This one gets to me a lot. I feel like there is this common notion that we can get things done faster if we sacrfice quality. This might be right in the short term, but there is always a price to pay. We may skip tests because "there is no room in the budget for them" as if testing is some line item a client needs to pay for.

The quality generated by tests speeds up the process down the road. We implement features and fix bugs faster. The time we spent creating an easy to understand metaphor enables new comers to more easily understand the problem. There is also the added benefit that I am proud of the work I do.

Quality is measured different ways, but the main point is to always do the best you can.

###Baby Steps###
I am terrible at this. When I see a need for a change, I am typically pulled towards "go big or go home." This usually ends up being very disappointing when I come to grips with the fact that I am a human being and only capable of so much within a given period of time.

No need to recoil from failed big changes if you take baby steps. Celebrating small victories keeps a team motivated.

###Accepted Responsibilty###
"Here is your project Brian; we estimated it at 1000 hours. Good luck!" 
XP practices dictate that whoever signs up for work is responsible for estimating it. If I accept the task of implementing a story, then I am responsible for everything that goes into that implementation.

As Kent puts it, with responibility comes authority. If my project manager tells me how to do my work but does not share in that work or any resulting consequences, then authority and responsibility are misaligned. We can't get or give meaningful feedback to someone who doesn't know what is going on.

Not knowing who is responsible for what, and who is the authority on a given item leads to some ugly kinds of paralysis. You might hear something like "why is this outstanding issue everyone's lowest priority?" The answer might be because nobody has a clear understanding of their responsibility, and therefore has no ownership of the issue.

One of the fallouts of XP seems to be an over abundance of "process experts." There are plenty of certified SCRUM masters who know process but don't know a thing about the code that their team is writing. For some reason this seems to be a trend in my native midwest.

Practices
---------
Practices are the things that XP teams actually do! The experiences I have had have definitely been impacted by some of these things, but they are by no means ubiquitous. Some of these practices have made their way into software development as a whole, and therefore show up in different situations for me.

Some of these practices sound absolutely ridiculous to companies in my neck of the woods, and therefore our exposure to them has been limited - much to our chagrin. 

###Sit Together###
Do what it says. Sit together. Sit close enough where you can communicate effectively and enjoy shared accomplishments. I think most of us who don't work remotely have figured this out. This seems to be a generally accepted and enjoyed practice.

###Whole Team###
This practice states that we should include people on the team with all skills and perspectives necessary to see the project succeed. I still see problems with lone ranger development. On one level is flattering to have people put that much trust in you, on another level its frustrating because being alone is depressing and not as effective as being with others. The bright side is I have noticed this falling out of favor more and more; some of us catch up a little later in life.

For smaller greenfield projects, Whole Team might consist of a backend developer exposing an API, and a front end developer consuming that API. We may hire a designer to give us a style guide to meet that need of the team.

When you're organization has a group of people with varying skills and backgrounds, there is this desire to place these "resources" into multiple teams, therefore fracturing teams. It is important to make is the team's responsibility to respond to the client instead of the programmers - otherwise individuals will suffer from fractured thinking.

We are still ironing this out. 

> Identifying with this program on Mondays and Thursdays and that program on Tuesdays, Wednesdays, and Fridays, without having other programmers to identify with, destroys the sense of "team" and is counterproductive.

###Informative Workspace###
Someone should be able to walk into a workspace and get a general feel for how the project is going. With the over emphasis on process and tooling, this has become less obvious.

I may be able to communicate with other team members via a Jira board, but that is closed to some of the other vested parties. I think it would be nice to favor paper story cards on the wall - just for transparency to anyone in our work space.

We have tried to make a "digital" workspace informative by granting Jira access to clients, or displaying burn down charts on walls. However, this doesn't really make our "Sit Together" workspace all that informative.

###Energized Work###
Work as many hours as you can be productive and only as many hours as you can sustain. We are problem solvers, not machines. A rested mind is better at solving problems. Period.

I've worked on projects with people where I see commit notifications coming through at 11pm. Often times these people aren't billing for the added effort. It's an attempt at grabbing back control - to take the pressure off of deadlines and feel comfortable. The irony is that the exhausted programming will likely introduce defects and add less value than if the programmer were rested.

Some companies may incentivize "billable hours" by creating contests that reward people who can bill the most in a given week - rewarding the depraved soul that puts in an 80 hour work week. In my opinion, this is in direct violation of the Humanity principle and is like paying people to do poor work.

###Pair Programming###
This is perhaps the most misunderstood practice. It is worthy of a book on its own, and indeed many have been written. This practice has not been common at the companies I have worked for. According to XP, pair programmers:

* Keep eachother on task.
* Brainstorm refinements to the system.
* Clarify ideas.
* Take initiative when their partner is stuck, thus lowering frustration.
* Hold eachother to the team's practices.

There is still a misconception that pair programming is paying 2 people to do the work of one. It just seems like double cost to clients, and therefore is typically discouraged.

I think the misconceptions arise because people believe pair programming allows no time for privacy or personal thinking, where XP says both are necessary. The key is to let private time result in new ideas/information being brought to the team.

I am currently reading [Remote Pairing: Collaborative Tools for Distributed Development](http://pragprog.com/book/jkrp/remote-pairing), and pursuing a pair project with a friend and coworker to understand the value better, and I do believe there is some real value there.

###Stories###

###Weekly Cycle###

###Quarterly Cycle###

###Slack###

###Ten-Minute Build###

###Continuous Integration###

###Test-First Programming###

###Incremental Design###
