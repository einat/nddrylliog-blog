---
title: What I would have missed
date: 2012-09-25
tags: [ perspective ]
layout: post
nofooter: true
---

### Intro

This is a follow-up post to the "oh fuck moment" post. While most of my posts
here are seemingly ominous and/or generally dark, it's not like me to blog
about giving up, so I got a few surprised reactions to it.

But most importantly, I got an e-mail from the co-founder of goodfil.ms
himself :) While I won't take the liberty to reproduce it here, it was, overall,
very encouraging. They're a hardworking team as well, and I admire what they've
been able to put out, but they appreciate the competition as much as anyone.
Between small structures, the relation is rather friendly: we all know there's
a problem, but no one's been able to crack it quite yet, so as long as there's
cash around, we'll keep trying.

Since the last week has been crazy, I found myself compelled to write about
what I would have missed, had I given up on movies.io altogether at the time of
that previous blog post.


### UXRomandie

Even with the gloomy perspective my wednesdsay left me in, I went ahead and
gave a small talk about movies.io at UXRomandie. It's an event part of a larger
UX organization, focused on exploring new venues to improve user experience in
technology in general. Since movies.io is usually praised for its interface, it
seemed like a good fit for an evening at UXRomandie.  (Lots of thanks to Simon
Farine for inviting me there, by the way!)

The first surprise was that there was already movies.io users among the
audience, and that they started to use it even before they had heard of the
conference. So I got to meet a few of them and get direct feedback on the
website.

Overall, the evening was very positive: the talk was followed by a
mini-workshop on the interface of the future movies.io desktop client. It was
fascinating to see that many minds (and pencils!) at work on my baby product. I
was humbled to see the iterative process, all the ideas presented, and I got to
walk out of there with a big pile of A4 concept drawings.

I don't know how much of that will be put to use in the actual desktop client,
but overall it was very heart-warming to see that overall, people loved the
idea and the execution. It seems I've come a long way from being a purely
backend engineer at official.fm!

### SUISA

A bit pumped up following the UXRomandie event, I got started thinking again
about licensing (ie. how to turn movies.io into a fully legit business), and
thought again about the global license: a system were all internet users are
billed a flat subscription, and their contribution is redistributed to the
rightsholder, in a fair way. I tweeted a thought or two, and was put in contact
with [@SwissTengu](st), a member of the Swiss pirate party, and blogger.

[st]: https://twitter.com/swisstengu

Apparently there was to be a meeting the next evening in the SUISA offices,
about the reform of copyright law in Switzerland. I quickly decided to attend,
just to see what it was like. We were about 15 participants, in a cosy Lausanne
office, discussing about the future of retribution for artists and producers.

The participants were either artists, producers, pirates, or jurists for the
SUISA.  SUISA is a rights management cooperative for all of Switzerland. Most
Swiss artists are signed up there, which allows them to outsource the licensing
of their music for public broadcasting, compilations, etc. It handles
everything that has to do with reproduction and derivatives of a copyrighted
piece (music, book, etc.).

The first good surprise was that a representant from SUISA reaffirmed some of
the things I assumed, but was never quite certain of. First, that it was - and
remains - perfectly legal to download copyrighted content in Switzerland, and
copy it at will, as long as it's for personal, non-commercial use. The SUISA
has never taken legal action against individual downloaders: its role would be
only to penalize third-parties trying to monetize copyrighted content without
paying the rightsholder dutifully. (For example, if movies.io started to sell
movies to Swiss citizens without worrying about rights.)

Another point was that, even though there's an official "discussion group"
assembled in Berne, to the request of the Swiss government, to overhaul
copyright law in Switzerland, it seems unlikely that the law will change in the
next few years. Part of the reason is that, in Switzerland, there's always a
certain inertia: officials want to be sure that they're doing the right thing
before changing anything. Nevertheless, the current situation is basis for
political pressure on Switzerland mostly from American lobbies: recently, it
was even put on a "black list" of pirate countries.

However, getting out of this ditch isn't going to be really easy. Any move
regarding the legislation in the area of copyright and downloading in
Switzerland would be regarded as backwards by the general population. The least
backwards initiative could be, perhaps, the global license. But, again, the
idea is still very fuzzy.

Would individuals be billed (perhaps by their internet service providers, on
top of their internet subscription), or would it be third-parties (music/movie
stores)? And how much would they be billed? How would the redistribution be
handled? There was some confusion about the technical possibility to accurately
track usage for a fair redistribution, which I tried to clarify: on the
internet, and particularly on traditional online marketplaces, it's very easy
to establish a precise report of who buys what, and how much.

An ex-SUISA lawyer mentioned the case of [MX3](http://mx3.ch), and experiment
made in Switzerland in fair retribution based on the popularity of the content,
and explained that they quickly ran into issues of artists "gaming the system"
by clicking many times on their own tracks: the resulting top 10 was utterly
worthless. Again, I explained that analytics abuse have been around for almost
as long as the internet and that today we have reliable ways to make the system
a lot more robust. In short, that it was not an opposition on an ideological
level, but rather on a single implementation that was, apparently, half-assed.
(In the same fashion, one shouldn't abandon sex just because they've had a
shitty partner once.)

At the end of the evening, nothing was resolved as far as the law was
concerned, but I advanced one of my proposals which I've had in mind for quite
some time: a universal licensing API. The idea would be to open the audiovisual
market for any "two-students-in-their-basement" start-up that can come up with
a great interface and play around with a business model, basing their product
on a huge catalog. It would allow near-perfect competition in this arena, in
contrast with the incredibly-closed nature of music and video distribution
today, where only major actors can succeed, with insider knowledge, and often
dishonest deals.  (It really is quite terrible, anyone in the industry can -
but often won't - testify about this. I detailed part of the procedure in "four
months of movies.io")

The proposal for an API generated mostly positive reactions from all sides.
Some participants were confused as to the nature of an API, and of the
possibilities that it would open. But in general, people understand that
allowing more competition is good (except for the big monopolies) and that
ultimately, both artists and consumers would be the winners of such a move.
What's more, it doesn't require great architectural changes for current rights
management organizations (such as SUISA, SACEM, etc.), just to interface their
internal system with the universal API. Of course, they'd have to give up on
most of their manipulation methods and other tricks to make the prices go up
and play on availability by region and time windows.. but, again, it would be
a big win for the consumer.

I'm looking forward to the next meeting, which should start by a short
presentation from techies about what an API is, how it works, and what are
the advantages over a "spend weeks over the phone" workflow.

As for me, the personal conclusion is that it remains safe to run movies.io
from Switzerland, as long as it stays non-commercial. Even copyright officials
from here don't seem shocked by my approach, and rather appreciated the
design and amount of work put into it rather than seeing first the legal
challenge that it causes.

### What's next?

Among the flow of other generally good news, I got an invitation from the
organizers of [HackDayParis][hdp] to attend either as participants (hackers)
or as members of the jury. Fred and I accepted the invitation as members of 
the jury, but we're still waiting for the final confirmation. What's really
interesting here is that the premier sponsor is France Télévision, the network
behind France 2, France 3 and others, which are very big in France. Our approach
(indexing torrents) is seen as "fundamentally disruptive" rather than "illegal/
morally reprehensible"

[hdp]: http://hackdayparis.org/2012.html

Other reactions I've gotten on Twitter and co. were that no matter how cool
other websites were, movies.io has gotten itself a loyal core user base who are
looking forward to improvements to the website, and shutting it down would be
letting them down.

And since I'm never entirely satisfied with anything I do, I kept working on
it.  One big point was i18n, I've integrated tr8n, a rails-friendly
internationalization plug-in, which will allow our userbase to translate the
website in over 233 languages.  Integration is not quite ready yet but I'm
willing to test it with a limited amount of users to see how it goes.

I've also overhauled almost all pages on the website that deserved some love.
Most of them are subtle tweaks, but there are more fundamental changes also:
the story view for watchlists has been completely revamped and now makes
watchlists into "works of art", taking full advantage of the gorgeous backdrops
TMDb gracefully makes available. Editing watchlists now also show you
"suggested additions" so that you can discover films similar to what you
already have in your list. In a similar fashion, movie pages show the top 4
most popular watchlists containing a particular movie: I think this will help
with watchlist discovery.

The put.io integration got some love as well. I discovered a bug in their API
that made it impossible to stream many movies, simply because the API response
claimed there was no MP4 available, even though we had requested its conversion
earlier.  I've implemented a work-around and now all movies should play files.
The "log in" / "session expiration" issues are still present, but there's
nothing I can do about them for now, unfortunately. I still recommend using
[XBMC](http://xbmc.org) to watch movies from put.io though, that's the best way
for me!

The topbar has seen some love: it's a lot clearer, the "loves" is gone :( but
there's additional information: notifications can now be seen from any page
thanks to a pop-over (a-la Facebook), and if you have a linked put.io account
you can see the remaining space directly in the topbar, which is very useful.
When adding a torrent to put.io, it'll also warn you if you don't have enough
space, very useful for trial users that only have 1GB.

Another often requested feature was the ability to report bad torrents: that's
now done, registered users can hit the 'Report' button and it will divide our
internal secret score by two. The result is that if several users report the
same torrent, it will go down in the rankings and will be replaced on the movie
page by another, better torrent. There's still no manual submission system or
fully-fledged moderation system, alas, but let's hope this will be better than
previously.

There's been lots of discussion about a form of commenting on watchlists, and
even on "movies in the context of a watchlist" (a 'WatchlistBelongship', in DB
jargon).  While I think it would be a great interaction point for users, I'm
still looking for a good way, interface-way, to make it non-intrusive and
generally not make it seem out of place. I swear, that story view is so pretty
I really don't want to pollute it with extra bloat.

All these changes haven't been deployed yet, but as soon as I feel better &
successfully work out the anxiety associated with deploying a big chunk of
changes to production, I'll make them available for everyone.


