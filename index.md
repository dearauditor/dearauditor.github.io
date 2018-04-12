###Dear Auditor,

Dear Auditor,

We realize that we have been changing things in a rapid fashion from Agile and DevOps to Cloud and Containers. We have been busy, and we have had great success as companies are delivering faster than ever and able to respond to business needs. (TK: Insert DevOps Survey stats). This isn’t just icing on the cake, the only sustainable advantage in our industry now is the ability to meet customer demands faster, more scalable, more reliably than our competitors and companies not working in this way are losing market share and shareholder value.

But, with all this growth, we made a huge mistake. We forgot to bring you along for the ride. That is totally our bad, but we want to make it right. We want to make a new commitment. 

As we work closer together you will be exposed to some of our practices that, we believe, will demonstrate how better managed we are now than ever before.  The DevOps community has been experimenting quite a bit over the last number of years and common practice represents the collective wisdom across many companies, industries, and countries.  

## Separation of Duties and Empowered Cross Functional Teams

For example, a growing trend within most companies is to re-architect themselves to enable the loose coupling of services and components so changes can be made safely, quickly, and repeatedly.  These new architectures necessitate a new organizational structure that is also loosely coupled and often flexible and adaptive to new commercial opportunities.  In fact, we are seeing the growth of cross-functional teams that are autonomous and have all the skills, capabilities, accountability, and often the financial responsibility to fully own their services and applications.   We are seeing quite a bit of friction and conflict with the audit community with respect to cross-functional teams and **Separation of Duties (SOD)**.  We believe the spirit of SOD is to minimize the risk of fraudulent or malicious code being deployed to the production environment.  The fundamental assumption of SOD is that multiple parties from different organizations will be able to prevent such abuse, but we believe that modern development methodology has a better way to ensure review, rigor and correctness via tools, automation and core agile/devops practices.

What do high performing teams do to achieve the spirit of not allowing fraudulent or malicious code be deployed to production?  A key counter measure is using technologies and techniques such as secure delivery pipeline from version control to production, peer-review, heavily restricting production access to only “break glass” accounts, automated security testing, and automatically testing for functional correctness code artifacts multiple times as it travels through the pipeline. An excellent example of these practices are embodied in the Software Delivery Cleanroom developed by Capital One.

In our experience, SOD often leads to a number of undesirable side effects such as: 

* Bloated implementations
* Technical Debt
* Bouncing incidents between multiple teams
* Architectures with a large change surface area due to organizations being structured along strict discipline lines
* Diluted ownership of services or applications (Not my problem effect)

We believe that empowered teams that have full responsibility for their outcomes lead to superior business results such as:
Result

## Ephemeral Instances

DevOps, Automation, Continuous Delivery, Containers, and the cloud have changed the rules of the game.  In many cases we use extremely short lived instances because it can potentially save our organizations quite a bit of money.  In addition, the inherent elasticity of resources means that our platforms can automatically scale up as many instances as we require during peak demand periods.  

How do these short-lived instances cause friction?  Imagine it’s time for our periodic audit review and you request a screenshot for an Server-X12347987 that we used for 120 minutes 3 months ago.  This server was automatically provisioned  by the platform using source code in our version control system.  The server was subsequently destroyed after the temporary circumstance went away.  I gotta be honest with you, I was asleep when this instance was spun up and I didn’t get a chance to take a screenshot…

What can I give you?  I can provide: 
* The logs of Server-X12347987 
* The source control that was in effect at that point in time
* The recipe that would have been used for the Server
* The artifact that would have been deployed to the server
* 100% assurance that nobody tampered with either the source control or the artifact repository


## Where do we go from here?

We are confident that we can make each other more successful.  If you have an open mind, the goals of DevOps are highly consistent with the goals of audit and we will go farther together than if we fight each other at every step.  The population of Fortune 1000 companies not pursuing DevOps is rapidly shrinking.  As research from the State of The DevOps Report suggests, DevOps provides a key capability to stay commercially relevant within a given industry, so DevOps is not going away.  We won’t back down from speed and providing value....in fact, you should expect that we will be picking up speed as we go along   Don’t misinterpret this olive branch as 

XOXO

Your Local Developer

# From the Team

Created by [Ben Grinnell](https://github.com/Bengrinnell), [James Wickett](https://github.com/wickett), Jennifer Brady, [Rob Stroud](https://github.com/RobertEStroud), [Sam Guckenheimer](https://github.com/SamGuckenheimer), [Scott Nasello](https://github.com/scottnasello), [Tapabrata Pal](https://github.com/tabladrum)

Released under the CC0 License: https://creativecommons.org/publicdomain/zero/1.0/
