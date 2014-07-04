

Until recently, I had thought that course-teaching was for the seasoned veterans of the web world, those who
knew HTML, CSS, and Javascript like tying their shoes, for whom Powerpoint and networking over coffee and
sandwiches comes easily (without worrying about how many sandwiches is too many given the number of students
and the number of food items on offer). I am not one of these people. I worry about sandwiches, handshakes,
and other such mundane things. Unsurprisingly, then, I had thought that I was not cut out to teach a course.
Perfectly happy in my design and development corner, I didn’t feel like I could be a poster child for tech
as the cool new thing, standing before a group of students with their eyebrows raised, expecting to be taught
the virtues of a career in code. 

That was, of course, until I was actually asked to teach a class. I was on my way out of the office for lunch
a few months ago when I was approached by one of the organisers of a Code First: Girls event about teaching
some young women about the basics of coding. It was far enough away for me to think it harmless (or to think I
could read a Wikipedia article/several motivational blog posts about how to teach), so I agreed. And I
wouldn’t be teaching it alone, they said; much to my delight, I would be with one of these seasoned
course-teaching veterans, [Alan Gardner](http://twitter.com/mr_urf). 

On the whole, I was terrified of teaching, mostly because I have the perpetual feeling that I’m not actually
very good at what I do. Rationally, I understand that I must be, but I can’t get away from the belief that
I’ve somehow tricked everyone around me. A course would surely expose that lack of understanding. 

This fear was only exacerbated when I first sat down to write the materials. We agreed that Alan would teach
the HTML and I would follow immediately with CSS. I had no idea where to begin, as what I thought were the
most basic of concepts were like nesting dolls; there was more and more inside of them, all of which needed
explained. It was instructive for me personally to keep trying various methods to find a good starting point
from which to teach the basics, and which order to teach them in. Code is a non-linear thing, and trying to
wrangle it into a linear, structured format can often be frustrating. 

The trouble with web development in general is that there are so many different ways to approach a problem
that there is simply no time to teach them all. The act of choosing one method to teach over a multitude of
others caused no shortage of headaches and fear, but eventually I had something I was happy with. It was a
humbling process, and I realised that I didn’t have to teach them the *right* way, but simply the way that
made the most sense to me. 

The course itself, we decided, would have a loose general structure that we could adapt along the way,
depending on how good (or how terrified) our students were. We would do a very short introduction to our topic
and immediately throw the students into the deep end with an exercise. This was because we know as developers
that it’s not at all helpful to have someone talking about code you haven’t yet seen. Slides go past, but
the syntax is unclear, and the student has no idea where to look. For this reason, they did an exercise first,
usually for about thirty to sixty minutes, to get a handle on the basic principles of HTML, CSS, or
Javascript. It was only afterwards that Alan and I talked about the subject with a little more depth, once
they had a context for it. 

We used pre-made materials from Dash and Codecademy; the rationale behind this was that we didn’t want to
reinvent the wheel. The materials were already on the internet, far better than anything we could make given
the constraints, and it made no sense to spend time creating a coding environment when there were already some
excellent ones out there. This also touched on the point that there are so many good resources out there on
the web; you just have to know how to look and, when you have a question, who or where to ask for help. We
thought it would be more useful to be the help, to guide students through the myriad of materials and
resources available, rather than redundantly adding to those materials. 

In teaching CSS, I enjoyed distilling it down to its very basics, extolling the virtues of external
stylesheets and demonising inline styles. However, it showed me just how many assumptions I’d made when I
saw the girls trying to negotiate their very first external stylesheet. For example, I had forgotten to tell
them that they didn’t need the `<style>` tag in an external CSS file. This had been so simple that I
had taken it for granted, and forgotten to point it out as a result (something which I immediately rectified).
It was great for me to see the thought process and expectations of someone completely new to the languages
that I’d been working with for over half my life. And these languages are fickle; it was difficult sometimes
to tell a student that their expectations were correct, but that the language or browser simply didn’t work
that way. Semicolons and syntax were a continual source of frustration, but that is why short lectures and
external exercises were so helpful, because it meant that Alan and I could walk around and help them with
these small errors and reinforce the basics, so that they didn’t get too disheartened too quickly. 

I also had to continually remind myself to slow down, especially if I was writing code myself. I had to
remember that they don’t know the salient points of what I am trying to show them; they’re trying to take
it *all* in. They cannot distinguish between personal preference in coding, unwritten etiquette, and
hard-and-fast syntax rules. The shortcuts that I have become so used to, the likes of Coda and Emmet and
multiple selections in SublimeText— all of this went out the window, but it was useful for me to see just
now engrained those little personal preferences are to my workflow, and how demanding it is to step out of
them so as not to overload the people I’m teaching. 

Despite my best efforts, that overload came quickly. Once I began to teach the more complicated aspects of the
course, Bootstrap in particular, I realised how unwieldy the web’s simplest principles can be. I also
realised just how lucky we’d gotten with the students we had, and how big a part their demeanour and
attitude plays when it comes to teaching code, or anything at all. 

We like to think of the coding world as having a very low barrier to entry. Whoever has the attitude and the
desire to learn is welcomed. In general, this is true, and there is an incredible wealth of materials
available online for those who want to learn at their own pace. However, the sheer scale of this material
proves a double-edged sword almost immediately, and the freedom of the profession is quickly turned against
us. When someone is first learning something novel, whatever that something may be, they almost always require
structure. They need to learn basics, sets of rules and heuristics on which they can build the rest of their
knowledge. Coding doesn’t always lend itself well to this; there are so many quirks, so many personal
preferences and so many materials that it can be hard to choose one thing to learn from. There are so many
different websites, bloggers, and startups trying to teach coding in different ways that the simple act of
choosing one can be overwhelming. Searching for a solution on StackOverflow can be horrifying on its own; a
solution that is lauded in one place is vilified in another, and a beginner has no idea why. They don’t yet
know how to apply these solutions to their code, and the strong opinions within the development community
occasionally scare these people out of asking a question. 

There is also the curious idea that the very things which should be making web development easier for
beginners— things like Bootstrap (or whatever jQuery plugin is the fashion this week)— are only usable by
those who are already in the industry. For example, Bootstrap should make it easy to create a simple,
responsive website for those of all abilities. However, it has gotten more and more complex in its versions,
adding quite a few different components and classes that make it very unwieldy to teach and use, especially to
someone who has just learned the nature of CSS classes recently. 

Don’t get me wrong; I think the web development world is a better place for having these frameworks, but
there is nothing more unfortunate than presenting a beginner, the very person who will gain the most
satisfaction from a quick Bootstrap mockup, with its documentation page. Imagine a beginner reading this
sentence: “To ensure proper rendering and touch zooming, add the viewport meta tag to your
`<head>`.” It isn’t clear from this that the line of code that follows is absolutely integral to the
site’s rendering on phones, and that it *must* be added. The grid system is confusing at the best of times,
with its different classes depending on screen size. As a result, the learning curve is far steeper than
intended, and the simple act of creating one’s first grid is an inordinately difficult thing to teach and
learn. It shouldn’t be. 

This isn’t a personal vendetta against Bootstrap, but a general point about web development for beginners.
It is ironic that the tools which make our lives easier are only accessible when we don’t really need them.
I can very much understand the value of all of this documentation, but the observation did strike me that
it’s perhaps not as beginner-friendly as it can and should be. There is something to be said for learning
the ins and outs of responsive design, for coding a responsive site by hand to get to grips with its
functionality, but this should not be a prerequisite. I believe that not everyone should have to learn raw
Javascript inside and out to know how to use a jQuery plugin just to display a simple animation on their web
page, and not everyone should have to know CSS inside and out before using Bootstrap (or any responsive
framework, for that matter). 

In spite of all this, however, the students dug in brilliantly, tried their best using an example I gave them
and after a few hours, had truly grasped the basics of responsive design and made their own small websites.
They asked questions, engaged with the code, and were unafraid to say when the documentation or my material
wasn’t what they expected.

At the risk of sounding a bit ridiculous, it was all very self-affirming. I had thought myself woefully
unqualified, but each time there was a question asked that I could answer, I understood that my knowledge was
perhaps better than I’d given myself credit for. And at the same time, when I didn’t know the answer, it
was easy (and perhaps even more helpful) to work through the process with them, to show them where I would
look and which terms I would search in order to find a solution to that particular problem. It was integral to
me that they understood that they didn’t have to know everything; nobody does. There is that stereotype that
somehow still persists about the lonely programmer, sitting at his (and it’s always a man) desk on his own.
He wears glasses, eats pot noodles, has a degree in Computer Science or mathematics, and is far smarter than
you. It was important to me to break down this stereotype and show them that the web is filled with problems
and their solutions; if you are sitting there slaving away on your own trying to reinvent the wheel, not
bothering to engage with the community, then you’re doing web development wrong. Asking for help isn’t a
sign of weakness. 

It is that tenacity and that desire to improve which is the most important, either in teaching or in learning.
Given enough time, I can teach someone anything, be it programming or sport or mathematics. I can’t teach
them to have that drive and passion, and that terrier-like tendency of a great developer to grab a problem and
never let it go, despite its best efforts to squirrel away and get the better of them. Not everyone has that
and that’s okay, but these students did. They had a drive to learn that made my job as a first-time teacher
very easy. They wanted to be there. That’s more than half the battle: having students in the classroom who
actually want to learn, and believe that they can. 

By the end of the weekend, I felt I had learned just as much as the students, if not more. I had been able to
engage with them, teach them a few things, and offer them some support for the future. It was that support,
direction, and mutual fear (that is, the feeling that someone else is or has been just as afraid as you are,
and has pulled through) that had been so difficult for me to find when I was just starting out, and that I
feel is integral to the beginning of a career in code. It was incredibly fulfilling, and something that I hope
to do again in the near future. In the future, I will be much more open to teaching, and I would recommend it
even more to those who feel they don’t know enough. Teaching our passion very quickly affirms what we *do*
know, and shows us what to learn next. 

Of course, there are still a few things that haven’t changed. I still worried about how many sandwiches were
too many, what my cake choice said about me, and I forgot a few names. I said a few nonsensical things and
perhaps I cursed a little too much, but I think we taught the girls something really useful and maybe broke
down a few stereotypes, not just about women in tech but men as well. They came away with a responsive,
individual website, and I can only hope that we inspired them to create more. It definitely inspired me to
continue teaching, and learning in turn. 