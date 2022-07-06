---
title: "Open Source and Politics"
date: 2022-06-29
tags:
- fruit
---

In conversation with [[thoughts/Coraline Ada Ehmke|Coraline Ada Ehmke]]

Intros
- Jacky:
- Coraline:

_This interview has been edited for clarity and length._

## How did we get here?

J: Maybe a good way to start is by first talking about how we kind of got involved with open source and move from there?

C: Yep. So I was an engineer, a software engineer for 26 years, in 2013, I made the decision to start my gender transition, and went full time in my true self in 2014. And it was around that time that I started becoming more interested in the issues of justice and equity and technology. Because in my previous part of my life -- it was something that I knew about intellectually -- but it wasn't until I started being around people who are experiencing the negative impacts of our approach to technology that it kind of woke something up in me.

I remember back in the early 2010s, when tech conferences started becoming popular and things, there was a big fight to get tech conferences to have codes of conduct, and it's something that seems so normal and natural today. But it was actually a very, very difficult fight.

2014 was also when I wrote version 1.0 of the Contributor Covenant, which was the first code of conduct for open source communities. I feel like over the years, eight years now, that the Contributor Covenant has been around, we've seen codes of conduct become more normalized in open source communities.

Today there, it's hard to count the number of adoptions it's in the 10,000s. And it's kind of wild! I was talking to a friend last year who said, "Coraline, there's an entire generation of engineers who have never known, they've never worked in a in an open source project that did not have a code of conduct."

One of the things I worry about though, with that normalization, is that we don't recognize our history. People in tech have very, very, very short memories, which is part of why we keep reinventing the same stuff over and over.

J: Yeah, yeah. For context, in my free time I do a lot of open source projects and hack on a lot of little things in general. I initially started posting a lot of my projects on GitHub more for backup and archival purposes and never really expected any real usage so I never really thought about being a maintainer or whatever that meant.

It wasn't until like my very first project that started getting real usage that I realized there never wasn't really any real introduction into being an open source maintainer, or like what it means to be like a good maintainer. There's no course on "here's how to be a good maintainer 101" kind of thing. It wasn't until I started getting contributors that people were like, "Hey, you actually don't have a license or a code of conduct in your repository, have you considered adding one?" And it wasn't until that happened that I realized, hey, I actually don't know much about, as you said, how did we get here? What is the history of all these code of conducts? I think that definitely kicked off a personal learning journey for me to kind of figure out the history of a lot of this as well.

C: Yes. So that kind of takes us to 2018. An activist group called Mijente were in the midst of their No Tech for Ice campaign and one of the things that they were doing was posting the names of companies that had contracts, either with Customs and Border Patrol or with ICE directly. And one of the companies that got called out was Chef has a large role to play in infrastructure, server deployments, and was very necessary for a lot of the large scale internet operations.

And one of the one of the developers at Chef at the time, Seth Vargo saw that Chef was called out as one of these companies profiting from human rights abuses at the border. And so in an act of conscience, he pulled all of his open source code that that was part of the Chef ecosystem and made a statement about why. But within two hours, all of his code was reinstated both on GitHub and on Ruby gems. 

And, and the kind of open source establishment the, what I call Open source traditionalists saw this and said "No, no, you can't do that, because, you know, open source is neutral". And I saw that as a as an epic *moral* failure on the part of the establishment. So I wrote the version 1.0 of the Hippocratic license, which was not intended to be a viable license, but rather to be a sort of lightning rod for broader discussion around the neutrality of tech in general.

J: Yeah, that's really interesting. For a bit of background as well, at school, I study computer science and philosophy. So a lot of some of my time spent thinking about how technology impacts the people that that use it. And I think one of the foundational pieces that I read that really, I think shaped my thinking around this was *Do Artifacts Have Politics*. I think that paper was really influential in terms of "Wait, actually, the this technology that we spend so long claiming to be neutral actually has political implications as well". And I think a lot of people in the space spend a lot of time trying to deny the fact that it does.

C: Yeah, and I don't know if you saw a talk that I was giving a couple of years back called "The Rising Ethical Storm in Open Source", it went in various directions. But I actually traced that illusion, or, you know, honestly, that that lie, that you know that computer technology in particular is neutral. I traced it all the way back to the 1950s with Edmund Berkeley, who was one of the cofounders of the Association for Computing Machinery, and he served on the committee called the Social Responsibility of Computer Professionals.

And their findings were that like, yes, technologists are absolutely responsible for how and what is developed. The how, what, why and it's impact. And the fledgling computer science industry at the time rejected that.

J:  Yeah. I did watch that talk that you mentioned. One specific timestamp that really resonated with me was around 21:42 in: "I believe that as technologists, we have moral imperative to prevent our work from being used to harm others. Responsibility is about impact and not intent." I think that definitely feels relevant.

One model I think about this often in terms of is thinking about tech as a multiplicative tool instead of something that's purely additive[^1]. Multiplicative in the sense that it will only exacerbate the existing discrepancies in distributions of power, right? Some people will obviously be way better off and then there's some will be that will be disproportionately harmed by it.

[^1]: this came out of a lot of thinking after reading The Ones Who Walk Away from Omelas [tk]

Whereas I feel like some people hold a very strong belief that technology is purely additive in that it will just truly raise the ground bar of everyone who uses it. Yeah, I don't know. I feel like that's always been missing from how people think about technology, that there's all always a hidden tradeoff or downside to whatever technology that you're building with.

And I wonder whether the developers of these technologies should be responsible for expecting how their tools will be used in whatever way down the line, right? If you build an open source project, it's very hard to tell what type of people will actually end up using your project. And so, at what point do developers have to start thinking about these tradeoffs, for example, who will my end users be and what is acceptable use and what's not?

Even from a developer standpoint, it obviously helps if you're educated in these issues in order to make these calculations. But even as someone who is educated about these things, how do you weigh the potential upsides and the potential downsides?

I came across the term Collingridge Dilemma a while ago that I think captures the double bind of technology quite well. In essence, it says that any efforts to influence or control further development of technology kind of faces a double bind, where you come across two irreconcilable problems: 1) which is an information problem. You can't really predict what impact your technology will have until it is extensively developed and widely used. But then, 2) you also run into a power problem where, by the time you've already extensively developed and put it into wide use, changes become too difficult because the technology has already become so entrenched in society. And at any point, it is is incredibly difficult to even begin to evaluate that type of impact. So, what is even the ideal place to start thinking about this impact?

C: Continually. You have to do it continually. You have to do it after deployment, you have to do it after it's widespread. You have to do it continuously.

So couple things on that point. In academia, if you're a sociologist, or an anthropologist, any of the social sciences, you have to go before an institutional review board when you're planning a research or development project. And one of the requirements for launching any such activity like that is having an effective plan for not only preventing harm, but mitigation plans when someone actually is harmed. We don't see that same that same principle being applied to hard science, we don't see it applied to engineering. Why not?

But to your point, it is very difficult to predict. One of the instruments that we're developing at the Organization for ethical source is something we're calling a priority of constituencies [tk: cite and add footnotes from W3C] which comes from one of the [W3 specs](https://www.w3.org/TR/html-design-principles/#priority-of-constituencies) for HTML. So there's this one sentence in the spec that was developed that said, in case of conflict, we "consider users over authors over implementors over specifiers over theoretical purity".

When you when you draw a line like that, what you're explicitly saying is that, even if this makes it inconvenient for adopters, even if it makes it inconvenient for developers, even if it makes it inconvenient for end users, you know, we have to make that decision based on the most vulnerable and work upward. It may be uncomfortable, but if the potential is there to reduce harm, to mitigate harm, or to have a plan for what to do when harm occurs, that cuts through a lot of the ethical gray areas.

J: I wanted to poke from the opposing side a little bit. I think there's a non-negligible number of people who argue that by increasing consideration for ethics, even in the medical industry where I think a lot of this regulation *is* important, they say that the regulations are too tight to enable innovation at a speed that is continually beneficial to progress by imposing all of these restrictions on what you can when you can't do[^2] -- it limits people from trying new things and innovating and developing new technologies that potentially could be have far greater upsides than we could have predicted.

[^2]: nb: silicon valley move fast and break things attitude, not all progress and innovation is good! but necessary. how do we balance progress w care?

C: Every technology for the entire duration of human history has been modulated by understanding that it doesn't exist in a vacuum -- that it exists in an increasingly complicated sociotechnological space. There's no telling ourselves that there's neutrality. Doing so ignores the actual mechanisms of human community, human society, human civilization as a whole. So if that stifles innovation, if that means a given technology is five years later, isn't it worth being careful? Isn't it worth being safe?

Regulation regulations are imperfect. But they are a way of codifying constraints or guardrails. And, you know, maybe it's okay to slow down a little bit, right? If we're gonna reduce harm, maybe it's okay to slow down a bit.

## On Agency in Technology
J: Yeah. One take I have been seeing a lot of is that top-down regulation is explicitly bad and we should 'decentralize'. And I think one interesting aspect that I spend a lot of time thinking about is the value of decentralization when it comes to comes to technology. A lot of these new technologies like blockchain kind of treat decentralization as an ends rather than a means.

- on decentralization + agency of technology [could cut if we run out of space]
	- personal research over the summer: rhizome
	- more data portability, autonomy, and permeability between systems
		- differentiating mobility and permeability
	- offramp existing systems -> onramp to existing systems
	- downloading the source code isn't enough, governance is critically important
		- chrome user-defined styled sheets example
		- frame it in terms of agency
	- participating in governance is hard, reclaiming standards
		- most standards bodies and governance structures for orgs that own standards are incredibly tight and hard for average person to participate in and make meaningful changes/decisions
		- don't know the answer but we definitely need to prioritize it
	- layers of normalization
		- we've normalized codes of conduct
		- let's now let's normalize representative equitable governance of open source technologies
		- let's go a step beyond that, and talk about like standards and enforceable standards
		- beyond that, of course, we have the legal aspects
	- metaphor of securing a server, no single layer is enough, we need all of them
- on how can we bring about these changes? help recognize technology + open source as political and non-neutral
	- what does regulating open source look like?
		- ethical source is not just about the hippocratic license
		- nb: to live in their utopia, systems of feedback and regulation are important
		- it's about building layers of normalization that this is stuff we should care about
			- "Harm reduction is not an event, it's a process. And I think we have to start normalizing those processes. If we have any chance at all of allowing the Internet to like be the incredible force for good that it has the potential to be."
		- not fire and forget either, can perpetuate systemic inequalities if not kept in check
	- interdisciplinary + multidisciplinary technologists
		- moving beyond the individualistic perception of open source as the long hacker in the basement but more so like as curators and crafters of a community around this project that you're building
		- comes down to ingroup vs outgroup: open source technology is simply tooling for people just like us
		- developers build infrastructure and dev tooling because they thats their ingroup, those are the problems they are familiar with
		- by bringing people who've had problems and experiences and other fields, then you start getting useful applications of technology in those areas
		- not through consultation but meaningful empowerment
		- nb: not treating human lives as 'externalities' to systems that spoil the purity of mathematical things 