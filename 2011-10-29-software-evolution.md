---
title: The best technology never wins
date: 2011-10-29
tags: [ perspective, rant, draft ]
layout: post
---

### Primer

This article is the culmination of my career as a developer.

Instead of rushing into some other crazy software project, I am taking some time
to look back at what I have learned in the past 10 years, and draw observations from it.

### Technology cycles

To open such an perilous post, quoting one of the monuments of software construction
literature, Steve McConnell's "Code Complete", seems appropriate:

     "During my career I've seen the PC's star rise while the mainframe's star dipped toward
     the horizon. I've seen GUI programs replace character-based programs. And I've seen
     the Web ascend while Windows decines. I can only assume that by the time you read this
     some new technology will be in ascendance, and Web programming as I know it
     today (2004) will be on its way out. These technology cycles, or waves, imply different
     programming practices depending on where you find yourself on the wave.
  
     In mature technology environments - the end of the wave, such as Web programming
     in the mid-2000s - we benefit from a rich software development infrastructure. Late-
     wave environments provide numerous programming language choices, comprehen-
     sive error checking for code written in those languages, powerful debugging tools,
     and automatic, reliable performance optimization. The compilers are nearly bug-free.
     The tools are well documented in vendor literature, in third-party books and articles,
     and in extensive Web resources. Tools are integrated, so you can do UI, database,
     reports, and business logic from within a single environment. If you do run into prob-
     lems, you can readily find quirks of the tools described in FAQs. Many consultants
     and training classes are also available.
  
     In early-wave environments - Web programming in the mid-1990s, for example - the
     situation is the opposite. Few programming language choices are available, and those
     languages tend to be buggy and poorly documented. Programmers spend significant
     amounts of time simply trying to figure out how the language works instead of writing
     new code. Programmers also spend countless hours working around bugs in the lan-
     guage products, underlying operating system, and other tools. Programming tools in
     early-wave environments tend to be primitive. Debuggers might not exist at all, and
     compiler optimizers are still only a gleam in some programmer's eye. Vendors revise
     their compiler version often, and it seems that each new version breaks significant
     part of your code. Tools aren't integrated, and so you tend to work with different
     tools for your UI, database, reports, and business logic. The tools tend not to be very com-
     patible, and you can expend a significant amount of effort just to keep existing func-
     tionality working against the onslaught of compiler and library releases. If you run
     into trouble, reference literature exists on the Web in some form, but it isn't always
     reliable and, if the available literature is any guide, every time you encounter a prob-
     lem it seems as if you're the first one to do so."
  
        -- Steve McConnell, "Code Complete" (2nd edition)

This splendiferous quote is still relevant in 2011, and I predict it will stay so for the
decades to come, as long as software craft is alive.

To decode the current state of technology, we must consider what replaced enterprise
software as the primary focus of software development companies: the social web.

### The rise of the social web

Sharing is akin to consumption: at the dawn of the web, sharing experienced an exponential
growth that truthfully mirrored the needs and wishes of its users.

UNIX users had .plan files. John Carmack's entries became famous enough to be inventored
in HTML form, on the web. Academics built websites out of pure content, a stylesheet-free
bliss of unspoiled knowledge.

The first networking platforms such as GeoCities rose from the need of human beings
to share content with each other. Demand was then much higher than supply. This explains
its roaring success, along with the formidable expansion and lifecycles of social
networks after that.

PHP and MySQL shared hosting paved the way for a generation of enlightened teenagers
to build internet forum boards nurturing tight communities around shared interests such as
technology, literature, and lifestyle.

As a programming language amateur, PHP makes me scream for its lack of purity, strictness,
and adherence to any proper paradigm. However, its historical significance is arguably
overseen. It empowered thousands and thousands of people to communicate through platforms
that they could buy by themselves.

There was no hard dependency on any central provider. You had control of your own database.
If you didn't like a shared hosting plan, you could move to another company. Communities
were organized, self-regulated with designated moderators.

Oh, how things have changed. Monetizing social interactions is a question that not only
MySpace had to ask itself. Analysts kept seeing curves shooting through the roof and spent
the better part of their sleepless nights trying to figure out how to make their profits
have similar slopes.

Traditional local grocery stores were serving a well-defined and modest goal: to supply
hungry customers with quality food products. From a supply chain point of view, it made
perfect sense as a middleman between producers and consumers. It would be too time-consuming
for farmers to directly deal with customers, or for consumers to go all the way to a
farm to buy products, on a large scale.

In the same perspective of fitting one's function, forum software such as UBB (1996) or
the later phpBB (1999) were perfectly adequate for sharing thoughts about common interests!
But there was one problem: they had no business model **per se**. How can you make profits
when community hubs are owned by members who won't sell out out of intellectual integrity?

For social networking to evolve into a monetizable artifact, it had to become centralized,
generalized, and incentivized. In order to become reality, sharing had to be forced down
the throats of groups of people who had nothing to share in the first place.

The success of Facebook is similar to the success of a party to which you invite the whole
world with a giant room and no drinks. "So lots of people are here. What do you do now?"
is a question that came up after most of the scaling issues were resolved.

One of the apparent advantages of centralization is the promise that you are going to meet
more people. Not smarter people, not people that have shared interests with you. We have
not yet seen the emergence of algorithms obviously capable of determining the friendship
potential of two people, even though dating websites have been working pretty hard on it.
The act of 'liking' was meaningless to begin with, and tells as much about someone as
knowing the color of one's underwear.

On the flip side, centralization only made sharing poorer. For one, because it made
censorship a lot easier. When all the content people share is indexable by a single entity
(as opposed to decentralized, private, password-protected, gated communities), it suddenly
becomes a lot easier to filter unwanted opinions.

But with centralization, the neanderthal of business models can take its toll: advertisement.
As with social networking and grocery stores, the purpose of advertisement has been lost
with years. It used to genuinely advertise, ie. make publicly known, services or goods
vendors to people who needed it.

But advertising is still the favorite fallback of any start-up. As soon as you start trying
to start a business off something that really ought to be free, you find yourself cornered
by the reality of the current offering. "We'll just include ads and make it up in volume",
you say.

And the world keeps on rolling.

### Programmers love challenges, decisions-makers love trends

The firm grip of business imperatives may have adversely affected technology evolution, but
alas it is far from the only offender.

Programmers are guilty as charged in the unending succession of technology waves we are
witnessing. Skilled programmers only reach that point if they have a resolute love of the
whole learning process, because the knowledge base is so incredibly large.

It takes dedication, and mind-sharpening skills, to get from the point where you see cool
technology and wonder how it all works, to the point where you cannot use a product without
making up theories about which technologies it uses, what algorithm is behind it, what
trade-off they have done.

There is nothing new under the sun. The world of software has been stalling since the 1970s.
I could go at lengths about the failings of the academic world to maintain high standards in
teaching, but the issue that attention spans have become shorter is striking developers just
as hard as anyone else.

As a result, it is more enticing for a developer (including on their resume) to have a wide
breadth of languages and platforms, even if they have barely grazed their surfaces, than to be
highly knowledgeable in one specific area.

I am not in favor of learning one language and calling it a day. Learning different languages
is part of basic software development culture and should be the norm rather than the
exception. What I'm pointing out is that all recent languages who gain popularity are variations
on a theme rather than real innovation.

Concurrency is no better off in 2011 than it was forty years ago. Threads, coroutines, and
the higher-level, imperfect, limited abstractions we have built over them are twice as old as
me, and yet they are being rediscovered every time someone claims to have a new idae.

One of the reasons actual progress is stalled is because an awful lot of man-hours are wasted
on surfing from one technology wave to another. The current trend is to re-develop everything
on top of JavaScript (ie. Jeff Atwood's Law) so it can run in browsers.

Why is it so? Does JavaScript bring any kind of technical advantage over any other known
language? Hell no! It is, in fact, inferior to most popular languages in usage nowadays. Be it
for tooling, performance, expressivity, JavaScript falls in the weak part of the crowd more
often than not.

And yet, it is one of the top 10 programming languages according to TIOBE. The JavaScript
community seems to just keep growing and growing. Every small achievement is celebrated, often
out of proportion.

And it's not simply because JavaScript is pretty much the only choice for browser scripting.
No, people are starting to adopt it on the server side, and to build all kinds of applications,
even non-web related.

The web, after all these years of standards dabbling, of vendor battling each other whilst
trying to walk in the same direction, is still in many ways a subpar platform for many kinds
of applications.

But all of this doesn't matter, because it is, apparently, still the next thing. The surefire
way to reach billions of people. Overwhelmed by the promise of numbers, thousands of developers
are spending their nights re-developing inferior solutions on an inferior platform at the cost
of an inferior social life.

HTML5 is a war that isn't going to end any time soon. Mobile game developers are crying for
a low-level audio API so they can play multiple sounds without caring if the DOM lags for
hundred of milliseconds, making precise timing of sample playback impossible.

The standards bodies touts half-baked proposals such as the HTML5 audio tag, as if they were
the holy grail. Not only are the people plagued by their narrow-mindedness and lack of perspective,
they are also prone to corporate pressure and sabotage.

While all of this happens, a generation of seasoned programmers sigh and shrug, thinking:
"We have been doing this for decades." And Adobe Flash still remains the only viable solution
for serious audio and video on the web, because of patents, missing features, cross-browser
compatibility, market share, CDN support...

The audio and video broadcasting market is an incredible racket with unbelievable margins.
The costs of bandwidth are roughly as ridiculous as the price of SMS in 2011.

Content distribution, and in particular live content, is not an easy problem. But it's certainly
not rocket science either. However, it is no exception to the business rule: nobody (except
consumers) have any interest in improving it.

For CDN companies, it is perfectly satisfactory to be playing Adobe and Microsoft's game. They
have no interest in research, because they make entirely too much money already, much like
most VPS hosting companies.

Nobody in business has any interest in making the best codec technology win either. The most
used codec on the planet, MP3, is still plagued by patents from Thompson and Fraunhofer. AAC,
although standardized by ISO and IEC, require licenses to distribute codecs in binary form.

On the lossless side, ALAC has just been opened up by Apple. Big whoop, say audiophiles, FLAC
has been available, open-source, and technically superior for years. Yes, but only ALAC is
supported on Apple software and hardware, which millions of people keep using despite its
lockdown business system.

The case for high-definition video was easy to make, because you could show the pixels. Doing
the same with audio is a lot less obvious. Codecs are not end-product. They aren't a real
business. They are just a tool used by companies to distribute content to their customers.

The best tech doesn't win, because the best tech doesn't make the most money.

### Lovers of good things are but a wee minority

People who run the big businesses are not looking for quality. They are looking for profits.
People who buy the most food, clothes, and other necessary items are not looking for quality.
They are looking for discounts, two-for-ones, mail-in rebates and bulk sales.

As a developer, I have developed a love for the fine things in life. Things that make me
all tingly inside, and suddenly I find myself wearing a monocle and drinking Chardonay. It might
be replacing a few hundreds lines of codes with a component that's weighs in the few tens. Or
it might be just an exceptionally well crafted computer game.

The evolution of the Heroes of Might and Magic series strikes me personally as a prime
example of software gone wrong. The first three opuses, from A Strategic Quest (1995) to
The Restoration of Erathia (1999), sported a flawless progression both in riveting gameplay
and artistic excellence, through the flamboyant 2D graphics as well as the majestic soundtrack.

Heroes III was widely acclaimed as the best in the series. Two expansions were made, and
another fanmade, "In the Wake of Gods". And then Heroes IV happened. A complete clusterfuck,
with apparently no art direction. And then they tried to force 3D down Heroes V's throat.

And then Heroes VI happened, on which I wasted a good 49 euros. It's a testimony to every
modern AAA game. With average art for its budget, a lengthy and prejudiced story line, it brought
the final blow on the Heroes of Might and Magic series by betraying its gameplay in unforgivable
ways, and having this sluggish, slow-paced experienced that most 3D strategy based games seem
to have nowadays.

A profit-based economy does not aim for quality. Quality things are created by small teams
of passionate people who spend entirely too much time polishing their creation with love
and attention to detail. That kind of process does not bode well in the current economic conditions.

### Final words

In software development as everywhere else, ignorance is bliss. If you want to stay a happy
developer, you better start ignoring right now anything I said above. But remember that, the
more skilled a developer is without being conscious about all this, the bigger tool he is
to his employers.

However, if you want to continue on the road to enlightenment, delve in the past. Open the doors
of a university library and take up deciphering old papers from the 70s and 80s. Read the Journals
from the ACM. Have the resilience not to be another college dropout, and use that extra insight
to have the upper hand.

It is alright to go out there and explore. It is alright to try and create new programming
languages, even whole new platforms. As long as you are aware that it is most often playtime.
That you know when to re-use, and that you know how to take advantage of the rich and long history
of software.




