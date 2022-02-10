---
layout: post
title:  "My motivation to write a blog"
date:   2022-02-10 18:06:21 +0100
tags: motivation ruby arithmophilia
---

So as I cheated yesterday writing my first blog post a day after the "official"
publication date, and as I wasn’t able to write a second post in the same day,
I’ll just skip 2022-02-09 unlogged. Not a big lost for humankind I guess, and
this seems a better approach for [cognitive load][w:cognitive load],
rather than trying to catch with every gap here and there.

I think that one thing that played a motivation role into starting this blog
was simply time that pass, and will to have a more clear narative of my life,
be it for myself alone. Incidently, 8 Februabry is my birthday. As I was born
in [1984][w:1984] (yes, like the title of
[the famous dystopian book of Orwell][w:Orwell]), that was my 13,880 circadian
cycle. I know it because I asked Ruby:
```ruby
require 'Date'
Date.new(2022, 2, 8) - Date.new(1984, 2, 8)
```

How neatly it makes easy computationnal tasks easier! I love it! ❤️

As we are with some geekery, did you know that 1984 spells `11111000000` in
binary notation? That’s 5 ones and 6 zeros. I don’t know for you, but for me
it immediately catches the will to know what are the previsous number in this
sery of n ones and n+1 zeros. And is this series already registered in the
[The On-Line Encyclopedia of Integer Sequences® (OEIS®)][oeis]?

So the series start like this: 100 (4), 11000 (24), 1110000 (112),
111100000 (480), 11111000000 (1984), 1111110000000 (8064)".
Obviously, I’ll be dead by 8064. Probably no one
of this far away year will ever read this. Actually, I wonder if anyone
will read it during my lifetime? 😅
Also, by current evidences of
the life and death of calendars, by 8064 Common Era, whatever human civilization
will still roam around – if any –, it will have probably moved to another one.
By the way, you get the previous series in Ruby with,
`1.upto(6).map{|n| "1"*n + "0"*(n+1)}.map{|n| "#{n} (#{n.to_i(2)})"}.join(', ')`.
And it is registered as [A059153][A059153].

13,880 is of course also an [interesting number][w:interesting] about which
[a lot of statements can be uttered][13880]. But none that catched my attention
though. 😆

Back to motivation, an other thing is that a few years ago I red
[The miracle morning][miracle] by [Hal Elrod][w:Elrod]. From it I kept the habit
to wake up early, but didn’t fully followed the whole method, especially I never
started a diary. So far.

Finally there seems to be some interest from recruiters that ask if you do have
a blog. Until know I just had nothing to drop in for this kind of demand. But
to be honnest, I was more embarrassed with the state of my Github account which
didn’t show as much as open contributions as I would like. Indeed, I spent most
of my professional career working on inhouse software building and maintenance,
which often don’t let you release much things in the wild. This is all somehow
ironic as in my spare time I’m a firm defensor of Free Libre Open Works (FLOW),
as I like to call them. So as this blog can be hosted on Github, this will make
more wild contribution, although that is still not as contributive to the
software side of things.

Oh, one more thing regarding motivation.
I recently stopped, again, to use [Timewarrior][tw] to track everything in my life.
It was marginally useful to know where I was at some point and to who I paid
attention, how much time I had spent on some project, but in the end this wasn’t
so useful insight, at least I never got oh great WOW from looking at it.
I feel like writing prose like this one will better contribute to my personal
fulfillment than seizing tag centric chronometries, which poorly synthesis
the luxuriance of thoughts and feelings.

[w:cognitive load]: https://en.wikipedia.org/wiki/Cognitive_load
[w:1984]: https://en.wikipedia.org/wiki/1984
[w:Orwell]: https://en.wikipedia.org/wiki/Nineteen_Eighty-Four
[oeis]: https://oeis.org/
[A059153]: https://oeis.org/A059153
[w:interesting]: https://en.wikipedia.org/wiki/Interesting_number_paradox
[13880]: https://math.tools/numbers/13880
[w:Elrod]: https://en.wikipedia.org/wiki/Hal_Elrod
[tw]: https://timewarrior.net/
[miracle]: https://miraclemorning.com/
