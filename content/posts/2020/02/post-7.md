---
title: "Post 7 with its UNIQUE title" # Quotation marks allow colons, semicolons, etc.
subtitle: "The UNIQUE Post 7 subtitle" # Quotation marks allow colons, semicolons, etc.
description: "The UNIQUE description for Post 7." # Quotation marks allow colons, semicolons, etc.
author: Your name goes here
author: Bryce Wray
date: 2020-02-28T21:30:00 # This would be 9:30 PM (2130) UTC on February 28, 2020
lastmod: 2020-04-02T12:23:00 # Comment-out this line with a # if content is unchanged
draft: false # Make it "true" if you don't want Hugo to "publish" yet
featured_image: /images/globe-life-park-rangers-1402096_1280x853.jpg # Or whatever image you want to use
featured_image_alt: "Baseball game at Globe Life Park, Arlington, Texas" # Always include an ALT tag for accessibility --  Quotation marks allow colons, semicolons, etc.
featured_image_caption: "Image: rwelborn; Pixabay" # Quotation marks allow colons, semicolons, etc.
---

There are no images within this post's body so it's OK to name it whatever you want and Hugo will make that the end of its URL. This is different from Posts 1 through 3 and Post 8, each of which has images in its respective body section and, thus, has to exist as `index.md` inside a folder with the post's end-of-URL. Of course, if this apparent inconsistency bothers you, you can just do all your posts the same way as those posts with body images: i.e., put each post inside a *folder* named (*e.g.* for this one) "post-7" and then calling the folder's Markdown file "index.md" rather than its current name.

Your opening text goes here

## In-article heading --- it's an H2 because your title is the H1

And after another paragraph or two or three, you may want to add a subheading, which would be an H3, so it would be like the following.

### Subheading (H3)

Text here.

Maybe you want a code block to illustrate something. Here's one:

```js

/* =========
This is some simple JavaScript, 
just so you can see how Hugo handles 
a code block.
It doesn't **do** anything in Hugo, of course.
Helpful on a dev blog, eh?
========= */

var i, j
for(i = 0; i < 10; i++) {
  j = i
  console.log(j)
}

/* ========= 
When run, the above would output:

0
1
2
3
4
5
6
7
8
9
========= */

```

Closing text. That ends Post 7!