    title: Congrats! You've pissed me off enough to write about you
    date: 2011-09-06
    tags: rant, benchmarking, nodejs, jruby

### A little background

On September 4, @headius, aka Charles Nutter, tweeted this benchmark about Node.js vs JRuby vs Java:

http://maxpert.tumblr.com/post/9677133069/node-on-nails

Facts:
    * In his very first tweet, Charles stated clearly that it was a 'simple experiment' 
    * It's not Charles' benchmark - as he repeated clearly and repeatedly afterwards.
    * Did you really take seriously a guy using 'n00bs' and writing on a blog? n00bs.

I retweeted Charles, and all in all it all got quite a few retweets, getting ourselves
noticed by... the Node.js benchmarking police.

And then we got personal tweets about our apparent cluelessness for linking to an article.

### A little respect

Listen, I'm usually the one to go balls out and piss on everyone's work until I was born,
but this was just too funny:

  @mraleph: @trygve_lie @nddrylliog @maboa or at least when you benchmark try to
  run equivalent apps. that means you have to understand both langs well

Yes, surely Charles does not understand the subtle differences between Ruby, Java and JavaScript.

I mean, it's not like he re-implemented the whole fucking Ruby language on top of the JVM or any
of that. Or not like he created his own somewhat-typed language (Mirah, nee Duby).

So, yes, surely Charles subscribe to Zohaib's primitive vision of "untyped is slow". I mean,
everybody knows that, right? That's the only reasoning behind Twitter's switch from Ruby to Scala,
and other such weird events.

As for me, well, if you spent even two minutes stalking me, you surely know that I'm behind the
ooc language - which must mean I'm a staticly-typed retard right? Right? Nevermind the fact that
I recently wrote a whole freaking MP3 decoder purely in JavaScript to prove a point.

As Dogbert says:

   "Wally, your problem is that you don't have enough knowledge. But it doesn't need to be
   real! Just say the *worst* about people and you'll usually be right!"

Sounds like someone took this advice a bit to seriously.

Now let's take this blog post somewhere constructive.

### Confusing models, platforms and languages

Everytime you say "Node.js is fast", a kitty dies.

Everytime you say "JavaScript is fast", that girl you used to like in college gains a pound.

Everytime you say "v8 is fast", a generation of Lua coders is laughing at you.

If you were to come to say things like "for web applications that have to handle a vast number
of concurrent clients on short-lived connections, an asynchronous event-based I/O model is probably
adapted", then, THEN we'd be talking.

And OH WAIT, remember not-to-be-taken-seriously Zohaib's post?

    "Not every web application is many connections application, you don’t code a chat system
    or a comet system everyday. NodeJS is good at few things and should be used for them. If
    you ask me to code a websocket based chat system using a IRC server, I would vote for
    NodeJS; but if you ask me to pull emails from all your email accounts and store them
    in some RDBMS or NoSQL store I would rather think twice."

Even he, gets it! So apparently even people writing on blogs, using 'n00bs', and choosing scandalous
headlines such as 'Node on nails' now a damn thing about technology. Interesting.

Just because Node.js has made the interesting bet to base *all* their libraries on an asynchronous paradigm
(resulting in horrible code by people who use that particular hammer for every nail) doesn't mean one couldn't
exactly the same with another language.

The problem today is that everyone a kid farts "X is fast, Y is dead", everyone believes it. Just because
some of us retweet an article because we found an interesting - yet simplistic - experiment doesn't mean
we endorse it. Cut it out already.

### Nobody cares about your technology

I mean, seriously. Nobody. Fanboy-me included.

What matters is your ability to turn whatever tech you're the most comfortable in, into something great.
It might be a tool that thousands of people will use in their day-to-day workflow (for Christ's sake,
most of emacs is hacked together with Lisp!), or it might be a product that will turn your startup into
a multi-billion company.

Steve Dekorte, a good friend of mine and author of the io language (then ripped off by Ola Bini, who has
this interesting Seph experiment going on also), once tweeted something along the lines of:

    If you could choose 'n', where 'your language is n times as slow' and 'you are n times as productive
    with this language' were both true, which value of n would you choose?

(Except his was less poorly worded, because I suck at writing)

And, well, in this web-obsessed realtime/social fast-moving world, I think I'd choose a really high 'n' if
it allowed me to write stuff like:

    exports.http = magic("Yet another HTTP server, but this time event-oriented")

I mean, nothing's impossible right? It could pull out the RFC, analyze the human language contained in them,
make sense of the gazillions of special cases that specifications contain, and allow events for just about
anything that could happen in an HTTP exchange.

Sounds like rocket science to you? Maybe it is - but if it's not, your grandkids will laugh at you because
you're still, like, handling sockets manually instead of using something robust and higher-level like 
[ØMQ](http://www.zeromq.org/).

### Stop the trash talk, resume the shame walk

Don't fucking insult people's intelligence over the internets. You Just Don't Do It (TM). n00bs.

The world is huge, and it has existed for a long time. Heck, less retarded people than me have said that we
haven't invented anything in CS since the 70s, and that so far, we've just been repeating the same dumb stuff.

And that's true, right? Everybody keeps re-implementing the same basic fucking ideas in their languages.
Everybody suddenly rediscovers async (Hi node.js community!), and then everybody suddenly discovers that hey,
making it scale across cores, processors, and nodes is a tad harder than it looked like.

And then Rob freaking Pike comes to save the day with Google Go (hey it has Google in the name so it must be
good right! Like, you know, Buzz, Wave, all that stuff), presenting a naive implementation of a 1970s paper
(CSP, look it up n00bs) attached with a horrible syntax and an oh-my-god-that's-fast compiler, and the world
is "Hurray!" because most of you can't see past their own shit.

Is Mr. Pike wrong in doing so? Must he be laughed at during language design events - the only time where self-proclaimed
language designers grow a pair of balls and abandon their ivory tower to come down and attempt to talk 20 minutes in public?
FUCK NO. He's got it right - a pragmatic approach that solves real problems, rooted in old research (which is
still good!), and a syntax he likes, with a fucking great toolchain, and he uses it internally for projects.
It's win, win, and triple-win.

So stop losing time writing and reading stupid blog posts and get back to work. Make sure you're using tools
you love, because if you're doing serious shit with them, you'll need more than superficial feelings to get
through the rough moments of your relationship.
