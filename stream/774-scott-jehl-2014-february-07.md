

They say a picture is worth a thousand words. As web users, I think we should be so lucky. 1000 words of
English text weighs a mere 5 kilobytes, and less than half that when compressed for delivery across the web.
I’ve got favicons bigger than that. The average “picture” on the web is nearly 11 times that size, [at
26 kb](http://httparchive.org/interesting.php#responsesizes), and in JPG format, that doesn’t deliver a
whole lot of quality. Which is why we encounter images much, much heavier than that every time we use the web
– each one adding time to our wait, chipping away at our limited data plans, and for some, chipping away at
our ability to access the web regularly.

This month [the average webpage weighs just shy of 1700
kb](http://httparchive.org/interesting.php#bytesperpage), and at its current rate it’ll hit 2 megabytes
within the year. Images alone hold a 61% share of that weight. It’s a hard problem. Perhaps we should just
modernize our proverb… say, “a picture is worth about 11,000 words, if it’s a pretty small image, and if
the words in question would have been compressed with gzip.” Or maybe something hip for the kids: “an
avatar is worth a thousand words.”

Fortunately, we won’t have to consider such things, because the past few years in our field have witnessed a
movement to address this very problem directly, and from many angles. At the core of the issue is that not all
browsers, devices, networks, and data plans are equal. We need better tools to tailor our imagery to our
users’ needs, and finally starting this month, we’re getting to see the tireless work of the folks in the
[Responsive Images Community Group](http://www.w3.org/community/respimg/) (and the web community at large)
start to come to fruition. Real, standardized tools are beginning to land in browsers such as [HTTP
Client-Hints](http://tools.ietf.org/html/draft-grigorik-http-client-hints-01) (which may help us create assets
that retain responsive characteristics when reposted and shared), and client-side (HTML) tools like [the
srcset attribute](http://www.w3.org/html/wg/drafts/srcset/w3c-srcset/) and its wonderful parent element,
[picture](http://www.w3.org/TR/html-picture-element/) (another “picture” that cost well over a thousand
words, if you read the standards mailing lists). These tools will be available to us [very
soon](https://twitter.com/yoavweiss/status/429879569790033920), and will be easy to
[polyfill](https://github.com/scottjehl/picturefill) for existing browsers as well. I simply can not wait to
see the effect that they will have across the web.

That’s all I’ve got this month. I hope this post was worth 407 words (2306 bytes, 1201 after gzip).