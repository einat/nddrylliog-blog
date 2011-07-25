title: Why BitTorrent rocks
date: 2011-05-12
tags: short
--

### So, what's so great about BitTorrent?

The standard is simply golden. There's a [very nice wiki](http://wiki.theory.org)
explaining it in details. All the little details just shows how well designed it
is. It was a pleasure to study and to implement.

### Can you cite a few great things about the standard?

It was built to scale. The piece/block concept is awesome: with
2<span class="sup">32</span> max pieces, and 2<span class="sup">32</span> max
piece size, it means that we can have torrents that are 2<span class="sup">64</span>
bytes long, approximately 17 millions Gigabytes.

It defines its own protocol to control congestion. Turns out, TCP isn't that good 
at preventing bandwidth exhaustion. The funny thing is that people blame BitTorrent
for *eating up all the bandwidth*. Yet it's entirely up to how the client implement it.

### How come you're so familiar with it?

I chose it at the subject of a semester-long assignment for first year CS students.
With my friends Bruno and Ismail, we built a prototype client, tracker, added our
own (insecure) layer of encryption so that the students would learn as much as possible.

### What's the best BitTorrent client?

Vuze is certainly the most feature-complete. Even with all the crap they've added
lately, it's still the only client I know which does intra-piece streaming. Their
media server implementation is simply brilliant. Kudos to those guys.
