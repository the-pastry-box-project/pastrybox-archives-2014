

Not more than 5 minutes ago a friend working for another agency asked me for help. He’s the CEO of his
company — a much larger agency than mine and definitely not a programmer at all. He was concerned about
integrating Tumblr posts onto the home page of a project his team was working on and they were having some
issues pulling as much content as possible in. He and his team were curious as to how I would approach the
problem.

Here’s what I wrote back:

> I haven’t prototyped or tested with this but just going
> on what I’m reading here’s what I tried.
> __RSS Feed__
> The downside is it appears to be static: It only updates when there’s a new post. It’s probably limited to
> like… around 20 posts or so. I couldn’t find a way to say… get an RSS feed with 100 items, or the second
> page.
> Examples:[http://howtobuildanapp.tumblr.com/rss](/)
> [http://howtobuildanapp.tumblr.com/rss?start=2&num=1 ](/)
> [http://howtobuildanapp.tumblr.com/rss?num=1](/)
> All seem to return the same data. ¡No bueno!
> __Tumblr API__ 
> (doc page: [http://www.tumblr.com/docs/en/api/v1#api_read](/))
> This doesn’t seem to require an access token or an app, so there’s no real downside as far as I can see
> for loading stuff in. The format returned is different than RSS (XML or JSON), but then there’s more
> control. Examples:
> [http://howtobuildanapp.tumblr.com/api/read/json ](/)
> [http://howtobuildanapp.tumblr.com/api/read/json?num=1 ](/)
> [http://howtobuildanapp.tumblr.com/api/read/json?num=1&start=2](/)
> You don’t need to be a code expert to tell you’re getting different data on each of those links. Different
> data means you can load in more stuff.
> I haven’t prototyped or tested with this so I don’t know how far back the data goes — if you had 5 years
> worth of Tumblr posts it’s not out of the question that perhaps not all the data is accessible. I’d
> recommended the dev team over there do more thorough tests to discern that.
> __CONCLUSIONS__ 
> Sounds like the dev team is using the RSS feed. I’d switch to using the Tumblr API — there appears to be
> no con or penalty whatsoever — you don’t even need to create a Tumblr Developer account. If it were me,
> I’d load in the first X number of posts (let’s say 20). Then a user could trigger more via some kind of
> interaction — scrolling to the bottom of the page, clicking a “More” button, whatever. 
> Further I’d recommended caching responses for a week or so to reduce the # of requests sent to Tumblr,
> depending on how often the clients’ blog would update and assuming that’s not an outright violation of
> Tumblr TOS. That might result in the data getting slightly out of sync but also be far less stressful on
> Tumblr’s servers. I don’t know exactly what “caching strategy” I’d use because well, it’s not my
> project. :)
> J

You might think this is more information than the CEO needs. You also might think that I spent an egregious
amount of time researching all of this. And if you’ve ever gotten an email from a friend asking for a bit of
help like this, you may have put off responding while you took care of other more important (read: paid)
work. 

To that I say:

 *  There are links for him to click and see for himself the differences between one approach and the other.
There is research for his team to go off of and a recommendation or two to decide the best course of
action.

 *  The whole of this research took about 10 minutes. It may not be exhaustively researched but it’s an
account of what I tried.

 *  Unless I’m doing something that truly demands all of my time helping a friend out is always a worthy
priority. Maybe I can’t respond to everybody the instant they need me but I can at least find the time to
respond with something helpful. 

Last month [Brad Frost](http://bradfrostweb.com) wrote
[“Just”](https://the-pastry-box-project.net/brad-frost/2014-january-28) right here on this site. Brad’s
right, and I’d add that explaining things well goes far beyond code and pixels. Helping others make sense of
something you understand is extraordinarily valuable — maybe the most valuable skill of all. It’s the
difference between the people around you feeling __empowered__ to make decisions and being __subjugated __by
what they don’t understand.

Designers should be teaching engineers more about color and typography and the decision making process. CEOs
can always be more transparent about the business decisions driving the direction of a company. And coders…
well, I think Brad covered that pretty well.

Take the time to explain stuff you understand to others that don’t. Empathize. Ask for better explanations
for things you don’t understand yourself. Be helpful and allow yourself to be helped. Only good can come
from that.

*Oh, and if anyone out there reading this better understands the Tumblr API feel free to ping me with your
thoughts. I’d love to learn more.