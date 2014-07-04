

Web developers can be a pretty outspoken bunch. Get a few of us in a room and it’s not unusual for someone
to start talking about a new project they’re working on, or start debating various libraries or best
practices.  And while there’s a lot we do talk about, not every topic gets the same attention. Web
accessibility is one of those topics.

Paul Lewis recently wrote that web accessibility was one of the “[3 unsexy pillars of web
dev](http://aerotwist.com/blog/web-components-and-three-unsexy-pillars/)” (the others being security and
performance) because it’s very rarely something that clients really care about (and will pay for). I’ve
seen this to be true and think it’s one reason why web accessibility is often seemingly ignored by
developers. We may think that it’s an “expert’s job” so we’re exempt from learning about it, or that
our sites don’t need to cater to that wide an audience ([statistics be
damned](http://www.cdc.gov/nchs/data/series/sr_10/sr10_256.pdf)!). I know I’ve been guilty of assuming both
at one point or another. But while these reasons seem pretty flaky, my goal here isn’t to scold anyone. I
think most of our silence boils down to the fact that many developers just don’t know much about web
accessibility, and we may not even realize that we’re behind.

Development is constantly changing, but over the years, I’ve found a way to (at least somewhat) keep up.
I’ve invested countless hours learning and re-learning CSS3 syntax, or reading about framework after
framework for building JS applications, and yet until just over a year ago, I had never even heard of WAI-ARIA
or bothered loading up the screen reader that’s built into both my laptop and phone. My (very poor) excuse
was that it just didn’t occur to me to look into either, and without much discussion from the larger
dev community, I didn’t know I was missing anything.

Oddly enough, it was only through a client’s project requirement that I finally started looking into
accessibility, and I realized I had a lot to catch up on. Slowly, I read through documentation, learned about
keyboard navigation and screen readers, and broke some of my bad habits that were hurting the accessibility of
my work. Sorting through all the articles and techniques, the biggest lesson for me was appreciating how some
of the seemingly trivial decisions I make as a developer actually have a huge impact on who is able and unable
to use what I build. Suddenly I understood how foregoing basics like image alt text and proper form labels
meant certain users would be excluded from functionality. On the other hand, I also learned that by being more
thorough with my code, building responsively, and leveraging tools like ARIA meant functionality would be
available to more users.

Though that particular project is long over, learning about web accessibility will be an on-going effort for
me. Just like keeping up with new CSS syntax and JS frameworks mentioned earlier, more and more I view web
accessibility as a key strength of any well-rounded developer, and part of that means participating in the dev
community to increase its awareness as such. Although there’s still a ways to go, I’m encouraged by the
recent increase in discussion around accessibility, from its role in new technologies like [web
components](http://www.polymer-project.org/articles/accessible-web-components.html), to several recent
[blog](http://alistapart.com/article/designing-for-easy-interaction)
[posts](http://www.sitepoint.com/learning-to-focus/). Better yet, new demos and tools are cropping up to
provide developers with real-world [implementations](https://github.com/paypal/bootstrap-accessibility-plugin)
and [improved workflows](http://quailjs.org/).

Now is as good a time as ever to start learning about accessibility for those who are still unfamiliar, and
there are [countless](http://www.w3.org/standards/webdesign/accessibility)
[resources](http://webaim.org/intro/) [to ](http://www.w3.org/standards/webdesign/accessibility)help
[get](http://a11yproject.com/) [started](http://blog.paciellogroup.com/). Given its purpose and power to build
an inclusive audience, there’s no excuse for us to ignore this “unsexy pillar” any more, and as we learn
more we can contribute our own experiences back to the growing dialogue. This will encourage still more
developers to finally catch up as web accessibility becomes a regular part of our discussions, debates, and
best practices. Who knows, maybe as a group, developers can even become outspoken about web accessibility.