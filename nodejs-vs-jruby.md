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











