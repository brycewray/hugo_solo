# Repo for brycewray.com

This is the repository from which a shortened, dependencies-free (but also [webmentions](https://indieweb.org)-free), [Hugo](https://gohugo.io)-generated version of [brycewray.com](https://brycewray.com) is built. Please note that this is just as an example; the **real** site is done in [Eleventy](https://11ty.dev).

## Not *(exactly)* a starter kit, but&nbsp;.&nbsp;.&nbsp;.

While this isn&rsquo;t truly a starter version of the real site, you can use it that way since it includes only a small number of the original posts to give you ideas about how it all works: 

1. Clone it to a local repo.
2. Make appropriate changes to `/data/metadata.json`.
3. Delete the Markdown files from `/content/**/.*` and the images from `/static/images/` (well, maybe you should keep one or two of each around at the start, until you see how things work).

## What&rsquo;s under the hood

For Hugo users unused to dealing with JavaScript from [npm](https://npmjs.org) plugins and dependencies, this repo may not be your cup of tea, and that&rsquo;s perfectly understandable. However, if you&rsquo;re willing to take a trip to the npm Dark Side, it does offer some interesting add-on possibilities. (That said, Hugo&rsquo;s single-binary, nearly-everything-out-of-the-box approach has served it well and is impressive.) In `package.json` you&rsquo;ll find dependencies and scripts to allow the following:

- Lazy-loading of some images through use of [lazyload](https://github.com/verlok/vanilla-lazyload).
- Responsive images through Hugo’s [built-in image processing capabilities](https://gohugo.io/content-management/image-processing/), using code borrowed shamelessly (and adapted for later versions of Hugo) from Stereobooster’s “[Responsive images for Hugo](https://dev.to/stereobooster/responsive-images-for-hugo-dn9).”


<hr />

For more information about the thinking behind this repo as well as a similar, [Gatsby](https://gatsbyjs.org)-generated version of the site, please refer to “[Different modes for different code](https://brycewray.com/posts/2020/04/different-modes-different-code).”