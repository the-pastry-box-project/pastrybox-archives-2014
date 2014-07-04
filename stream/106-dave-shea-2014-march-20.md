

CSS has seen a whole lot of significant ten year milestones lately.

Ten years ago, wired.com [rolled out](http://stopdesign.com/archive/2012/10/11/ten-years-later.html) the first
commercial all-CSS redesign. Ten years ago, the CSS Zen Garden
[launched](http://mezzoblue.com/archives/2013/05/07/10_years/). Ten years ago, we didn’t have fundamental
pieces of our development toolchain so we had to invent
[technique](http://stuffandnonsense.co.uk/blog/about/ten-years-of-sliding-doors-of-css) after
[technique](http://alistapart.com/blog/post/ten-years-ago-in-ala-faux-columns-and-elastic-design) simply to do
our jobs.

Though they were once fundamental, not all of these concepts stood the test of time. I had a reminder very
recently that one of my own contributions [just added a second digit to its
age](http://alistapart.com/blog/post/ten-years-ago-in-a-list-apart-css-sprites-image-slicings-kiss-of-death),
so before it's also relegated to historical footnote status, I’d like to eulogize CSS Sprites.

## Inception

It may be hard to believe now, but there was a time when custom web type were a pipe dream. Typography was
fairly static thanks to a [small handful of
fonts](http://en.wikipedia.org/wiki/Web_typography#Microsoft.27s_Core_fonts_for_the_Web) that were actually
considered safe to use.

The only way to add non-standard type and effects to a site was by pre- rendering it in Photoshop and saving
to an image. The `img` tag was the best way to load that image into your page at first, but in time various
[image replacement techniques](http://css-tricks.com/examples/ImageReplacement/) were invented to allow
control in CSS and use semantic markup; they were seen as an improvement.

A long-forgotten problem plagued this method: when images were used as navigation a browser had to go back to
the server and fetch the new image file on hover, causing a flash of the blank image area while it loaded.

A developer named Petr Stanicek [demoed](http://wellstyled.com/css-nopreload-rollovers.html) a way of
including multiple states of a rollover into a single background image for the sake of eliminating this flash.
However this also assumed navigation text was set as HTML text which, as we’ve already established, was a
limiting prospect at the time.

And so CSS Sprites came about as a riff on combining the fast preload concept with image replacement. With
those two pieces, we could now include in the same image both before and after states for all navigation
elements and get a result that solved both the limited typography and the flashing image problem in one
go.

## Legacy

CSS Sprites continue to live on, thanks at least in part to unintended consequences.

Five years after publication, I discovered that very large sites were [using
Sprites](http://www.flickr.com/photos/mezzoblue/3217540317/) in a way that, at the time, I thought was totally
insane. I completely missed one of the benefits of Sprites, even years after writing the original article.

File size has always been a priority for web performance but in 2004 it was far less clear that number of
requests was also a factor in load times. Big companies looking to trim every last byte didn’t overlook this
however, and Sprites evolved into a useful tool for delivering interface elements all at once.

## Future

When I look forward, I’m fairly certain we’re nearing the end of the usefulness of CSS Sprites for a few
reasons.

Sprite maps largely consist of UI images and icons, but it’s increasingly preferable to build a UI without
the use of bitmap images. You may have noticed that CSS has become a lot more capable in the past ten years,
and many interface elements and effects that were once possible only with pre-rendered Photoshop effects can
now be delivered without using images at all. And with icon web fonts and SVG, we’re now able to deliver
icons as vector outlines instead of bitmaps.

But even if the specific technique as it was originally defined for bitmaps is becoming less useful, the idea
of Sprites will likely live on. Folders full of SVG files share the same problem as images, so [sprited
vectors](http://css-tricks.com/svg-sprites-use-better-icon-fonts/) seems like a technique we’ll be using in
the near future.

Either way, I think the story of CSS Sprites is a great illustration of how the early days of building with
CSS worked. Web developers had big holes in our toolchain because the specifications were limited, support for
them even more so, and browser market share and development cycle realities didn’t appear to promise any
meaningful fixes for the situation.

So we invented our tools. We collaborated in blog posts and comments to evolve our ideas, with each new
technique building on top of earlier ideas and solutions. We dreamt of a day where specifications would
propose exciting new ideas and browsers would update frequently so we could get around to what we're really
here to do: create great sites for our users.

It took a while, but we’ve finally made it.

(PS: Bonus instant nostalgia hit for other old timers: Glish, Noodle Incident, Blue Robot, MaxDesign. Remember
those?)