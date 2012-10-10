---
title: Re: Hello from Google
date: 2012-10-10
tags: [ perspective ]
layout: post
nofooter: true
---

### Intro

A few weeks ago, a recruiter from Google reached out to me. I asked a few
questions, took some time to think about it, and here's my final response:

### Re: Hello from Google

Hi,

Thanks for writing back - and apologies for the delay.

I appreciate your willingness to make this work, but I suppose my hesitation as
to whether to go through with the interview process is because perhaps my main
objection is philosophical and can't be solved easily by HR.

You see, as tempting as is a Google job, I still can't help but to see Google
as one of those big companies that went into "start-up eating" mode quite a
while ago. And often, I was disappointed to read about several products being
abandoned (mostly products from start-up that had been acquired a few years
back).

I completely understand the need for focus, and I think sometimes abandoning
products is painful, but the right thing to do, yet when trying to figure out
the big picture, what do we see? That acquiring - or acquihiring (ie. hiring
the team) start-ups hinders innovation as a side-effect. And I have trouble
cooperating with that.

I'm not in any position to judge the decision of Google's board - it appears
very reasonable to try and secure one's position in several markets, and indeed
Google seems to try and encourage innovation, but mostly on the inside. And I
think what I really want is bigger than that.

For example, for me, video distribution is a solved problem. Sure, we can
always up the resolution, add more synchronized metadata, organize videos
better (I noticed YouTube now shows information about Shows / Seasons /
Episodes - a smart move which I've been expecting for months), but overall the
technology is here. Video codecs work reasonably well given the processing +
bandwidth constraints we are faced with. No, the real challenge left in video
distribution is licensing - because it is an incredible mess, as I have
[detailed before](http://amos.me/blog/2012/vision/) YouTube/Google got out of it,
afaik, mostly by selling shares to the majors so that an initiative like Vevo
could flower, rather than being shut down by heavy-handed lawsuits.

And by doing that, YouTube became the #1 platform where anybody can host pretty
much anything, without worrying about copyright. There are full movies on
there, 6 months old, and they're still up. On the contrary, there's also been
flak against YT's flagging algorithm (fingerprinting) that apparently took down
legit feeds. Although a little insight tells me it's mostly big rights holders
abusing their admin rights.. but I digress. By doing that, YouTube became big,
and kinda ruined the game for everyone else. Sure, there's DailyMotion (mostly
in France), and sure, there's Vimeo (mostly high-def, original content), but
all the others are crap aggregators that steal cat videos from one another.

The result? Being stuck with one, big, central provider. And that's something
that's been bothering me lately. While the underlying structure of the internet
(TCP/IP) is widely distributed, services over it are often big, centralized
entities: Google Search, YouTube, Facebook, Twitter, Tumblr, etc. - although
hosted either on clusters of thousands of small servers (a-la-Google), or on
what cool kids like to call cloud hosting, it's a single entity we are dealing
with. And decision on the part of a single entity can ruin a lot of people's
lives, because we are so dependent on it. (Example: Twitter API rules, sparking
the App.net too-soon-to-be-called-a-revolution).

Hence, by allowing single entities to gain so much power ([relevant
XKCD](http://xkcd.com/1118/)), we have betrayed the nature of the internet. The
remedy? Everyone likes to talk about Peer-to-peer and how it's going to change
the day, but things are not looking too bright on that front: I've worked with
BitTorrent for several years, and today the situation is that Copyright lobbies
have pretty much succeeded in equating it with "illegal filesharing" - although
a technology is just what it is: a tool. Following Skype's acquisition,
Microsoft switched from peer-to-peer to central servers (also misleadingly
called super nodes). The list goes on.

Why is the world so reluctant to adopt a peer-to-peer approach to everything? I
have a few ideas. First, because peer-to-peer is order of magnitudes harder
than client-server. For example, DVCS (Decentralized Version Control Services)
are harder to understand than centralized ones, because you have to think of
the fact that every clone might be in a different state, and worse, that it
might have branches that are conflicting, you have to think about clever
merging algorithms, and remotes, etc. - there's just a lot more to think about.
Same goes for pretty much everything else. Want to send a file by HTTP? No
problem, send a content-type, a content-length, perhaps an encoding, then
\r\n\r\n and there you go, send the data. Want to send a file by BitTorrent?
You'll have to learn about a special brand of URL-encoding, SHA1 hashes,
bitfields, a custom TCP binary protocol, bencoding, scheduling algorithms, the
end game, etc. etc.

So the first reason is that migrating from a client-server perspective to a
peer-to-peer perspective is as hard as it is to migrate from a single-thread
programming environment to a multi-threaded one. The number of potential issues
just skyrockets. The second reason in my opinion, is that peer-to-peer is not
so good for business. With a client-server model (again, no matter the number
of actual physical/virtual servers), clients are dependent on servers and are
perfectly useless without one. (Example: old RTS games that you can't play
online anymore - except with open-source, reverse engineered servers). So that
puts you in a position of power. With peer to peer, every peer is independently
powerful and capable, and can connect to any other number of peer to do
whatever the initial protocol was designed to do. That's why BitTorrent Inc. is
having trouble really "hitting it off": Bram came up with a particularly
popular brand of P2P filesharing. So what now? Content partnerships? A
'Premium' version? Really, there's not much to be done there.

So, even though this is getting long and might seem off-topic, the decision
whether or not to pursue that interview process with Google has everything to
do with all of that. Should I choose the easy road (try to score a job at a big
company) or the less travelled road (keep churning out side projects until one
reveals interesting enough for a proper start-up). Should I try to lure
millions into my client-server solution, or spend my life designing
decentralized infrastructure and making it friendly enough so that the masses
can adopt them and rely on them daily? (example: e-mail).

All things considered, I think that decision is an easy one. Again, I
appreciate you reaching out, but I don't think this is for me.

Sincerely,
- Amos Wenger

