

Where I work, we spend a lot of time talking about how to make websites that work “everywhere” and work
even better in favorable browsing conditions. The term often used to describe this approach is “Progressive
Enhancement,” or “PE”—and lately, I’ve noticed it may have an unfair stigma attached.

I sometimes hear concerns from developers that building with PE will hold them back from innovating and
“moving the web forward,” because it requires spending a lot of time making things work in old or obscure
browsers that aren’t presumed to be common within their audiences.

I find the opposite to be true. For us, building with Progressive Enhancement moves almost all of our
development time and costs to *newer* browsers, not older ones. Perhaps that’s because our approach to PE
has evolved beyond a mere [separation of
concerns](http://en.wikipedia.org/wiki/Separation_of_presentation_and_content) to a more controlled
[test-driven application of technologies](http://alistapart.com/article/testdriven)—which is a rather
abstruse way of saying that we just serve something basic and useful to everyone and then [heavily qualify
everything we do from there](http://responsivenews.co.uk/post/18948466399/cutting-the-mustard). This means
that ancient or under-featured browsers like IE 6 or BlackBerry 5 still have access to the core content and
functionality, but newer code doesn’t reach them and potentially break their experience. There are so many
new, popular browsers for us to care about nowadays that we rarely have time to test in older/unqualified
browsers until the late stages of a project, but when we do, things frequently work as expected—which is to
say very simply, and that’s often appropriate anyhow.

The hard part of building with Progressive Enhancement isn’t supporting older browsers, it’s supporting
*newer* browsers. But that’s hard no matter the approach. I suspect that building *without* PE would
actually increase time spent fiddling with older browsers, that is, as long as basic access remains a
priority. But in fairness, I can only speak to the approach that works for us. Progressive Enhancement frees
us to focus on the costs of building features for modern browsers, without worrying much about leaving anyone
out. With a strongly qualified codebase, older browser support comes nearly for free.