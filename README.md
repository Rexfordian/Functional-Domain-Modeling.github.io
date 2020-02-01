# Functional Domain Modeling

## Why?
Are you a developer of enterprise business applications?  Are you tired of being stuck with stale technologies because rewriting all of that arcane business logic in the latest technologies is just too risky?  So you're stuck with some crazily complex SQL stored procedures that nobody understands but "just work".  Or maybe you are rewriting your application and your scared to deploy it because you know you've missed vital but arcane rule.  Or maybe you're new to a project and you're trying to figure out what the thing is supposed to do but your getting lost in all of the boilerplate code.  These are just a few of the common symptoms that make enterprise development such a challenge.  So what's the cause and what can we do about it?  The cause actually seems pretty straight forward: *For most enterprise applications, the business concepts are tightly entwined with the technology choice of the moment.*  It's simple and it has major repercussions.  The obvious solution is to decouple them:

**The business logic is an application's most valuable asset.  Free it so that it can run across multiple technologies!**

It makes sense.  If we know technology is going to evolve rapidly, why should we embed our most important asset in the choice of the moment?  That's just going to lead to the endless cycle of costly and risky rewrites that we've all come to think of as a necessary price of doing business. 

Maybe you're thinking that this has already been attempted through the plethora of design patterns, blueprints, frameworks, and methodologies that attempt to accomplish this.  To date, these have had limited success and so we give up on the idea.  But maybe it's not the idea that's the issue.  Developers want to do the right thing.  It's just too challenging with the tools that we're using.  So maybe we should look at the tools.  One big culprit is the tool in front of us on a daily basis:  The general purpose programming language (GPL).  It turns out that these are a minefield of temptations that lead developers pepper implementation complexity into their business complexity.  And let's face it, most mainstream OOP languages are really not that great at capturing busienss concepts succinctly and unambiguously.  Which brings up the next topic.

*Most business applications are too complex for people to understand.*  Where does the majoritly of complexity lie?  For most business applications, the majority of complexity is *accidental complexity*. This is the complexity of the deployment topology, frameworks, communication, persistence, etc.  This complexity has nothing to do with the purpose of the application, yet it does the most to keeps humans from understanding it. 

Of course, there's also the *necessary complexity*, which is the complexity of the business itself.  Ideally, the software should be so well designed that the necessary complexity is easier to understand.  In fact, we could say that:

**A primary job of application developers should be to provide knowledge of how the business is supposed to function.**

By doing so, we ensure that the application is correct, which increases the confidence all around.  

These are the aspects of enterprise application development that Functional Domain Modeling seeks to address.  The primary goals are:

* Agility
* Knowledge
* Efficiency

From these, come a whole set of benefits that should appeal to anyone who develops applications for a business.=

## What?

## How?

## Who?
[TODO] link to education and implementations who sign on.

