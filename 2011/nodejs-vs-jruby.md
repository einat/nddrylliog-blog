    title: Congrats! You've pissed me off enough to write about you
    date: 2011-09-06
    tags: rant, benchmarking, nodejs, jruby

### A little background

On September 4, [@headius](http://twitter.com/headius), aka Charles Nutter, tweeted [this benchmark about Node.js vs JRuby vs Java](http://maxpert.tumblr.com/post/9677133069/node-on-nails):

**Facts**:

  * In his [very first tweet](https://twitter.com/headius/status/110391814569197568) @headius states clearly that it was a [sic] "simple experiment".
  * It's not @headius' benchmark -- which he has repeated clearly and repeatedly since the original tweet.

I retweeted @headius and all-in-all it got quite a few retweets of it's own.
This got noticed by [the Node.js benchmarking police](https://plus.google.com/111090511249453178320/posts/hJSKm6ra9wY).
Then @headius and I received personal tweets about concerning our apparent cluelessness.

### A little respect

Listen I'm usually the one to go balls-out and piss on everyone's work, but some of these were just too funny:

> @mraleph: @trygve_lie @nddrylliog @maboa or at least when you benchmark try to
> run equivalent apps. that means you have to understand both langs well
> 
> <cite>@mraleph</cite>

Yes I'm sure @headius doesn't understand the subtle differences between Ruby, Java, and JavaScript.
I mean, he re-implemented the whole fucking Ruby language on top of the JVM.
He's created his own [somewhat-typed](http://en.wikipedia.org/wiki/Mirah_\(programming_language\)) [language](http://blog.headius.com/2008/03/duby-type-inferred-ruby-like-jvm.html)!
So yes, surely @headius subscribes to Zohaib's primitive vision of "untyped is slow".
That's the reasoning behind [Twitter's switch from Ruby to Scala](http://www.theregister.co.uk/2009/04/01/twitter_on_scala/) and other such weird events.
As for me, I'm the developer working on the [ooc language](http://ooc-lang.org/).

As Dogbert says:

> "Wally, your problem is that you don't have enough knowledge. But it doesn't need to be
>  real! Just say the *worst* about people and you'll usually be right!"
> 
> <cite>Dogbert, of The Dilbert Comic Strip</cite>

Sounds like someone took this advice a bit too seriously.
Vya c'mon, you've worked at Excelsior (and now Google) which is a pretty good curriculum if you ask me.
I ask: Why such a primitive rebuttal?
I'll start by taking this blog post to a more constructive tone.

### Confusing models, platforms and languages

  * Everytime you say "Node.js is fast", a kitty dies.
  * Everytime you say "JavaScript is fast", that girl you used to like in college gains a pound.
  * Everytime you say "v8 is fast", a generation of Lua coders is laughing at you.

We might be able to talk ff you were to say things like:

> for web applications that have to handle a vast number of concurrent clients 
> on short-lived connections, an asynchronous event-based I/O model is probably
> adapted

Remember not-to-be-taken-seriously Zohaib's post?

> Not every web application is many connections application, you don’t code a chat system
> or a comet system everyday. NodeJS is good at few things and should be used for them. If
> you ask me to code a websocket based chat system using a IRC server, I would vote for
> NodeJS; but if you ask me to pull emails from all your email accounts and store them
> in some RDBMS or NoSQL store I would rather think twice.

According to that quote he gets it!
Even people choosing scandalous headlines such as 'Node on nails' can preface their arguments with solid conditions.
Node.js has made the interesting bet to base *all* their libraries on an asynchronous paradigm.

The problem today is that when a kid farts "X is fast, Y is dead" people believe it.
When some of us retweet an article it is because we found an interesting - yet simplistic - experiment.
It doesn't doesn't mean we endorse it.


### Nobody cares about your technology

I mean, seriously: Nobody, fanboy-me included.

What matters is your ability to turn whatever tech you're the most comfortable in, into something great.
It might be a tool thousands of people will use in their daily workflow.
It might be a product that will turn your startup into a multi-billion company.
Steve Dekorte, a good friend of mine and author of the [io language](http://iolanguage.com/) tweeted something along the lines of:

> If you could choose **n** where *your language is **n** times as slow* and *you are **n** times as productive
> with this language* were both true which value of **n** would you choose?^

(^This is not a direct quote)

In this web-obsessed realtime, social, and fast-moving world I think I would choose a really large value *n* if
it allowed me to write stuff like:

    exports.http = magic("Yet another HTTP server, but this time event-oriented")

### Lets stop the trash talk, start the shame walk

Lets stop losing our precious time writing and reading these posts and get back to work.
We should make sure we're using tools we love.
If we're doing serious shit with them, we'll need more than superficial feelings to get through the rough moments of our relationship.
