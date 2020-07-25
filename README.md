# Hugo starter set based on [brycewray.com](https://brycewray.com)

This is the repository from which a shortened, dependencies-free (but also [webmentions](https://indieweb.org)-free), [Hugo](https://gohugo.io)-generated starter-kit version of [brycewray.com](https://brycewray.com) is built. Please note that this is just as an example; the **real** site is done in [Eleventy](https://11ty.dev).

## How to use

1. Clone it to a local repo.
2. Make appropriate changes to `config.toml` to conform to your site’s parameters.
3. Once you have [installed Hugo](https://brycewray.com/posts/2019/04/ec-static), run `hugo serve` from your terminal app.
4. Read the sample posts and their Markdown files to see how everything works.
5. Edit the content to make it your own!

## What’s under the hood

For Hugo users unused to dealing with JavaScript from [npm](https://npmjs.org) plugins and dependencies, this repo may not be your cup of tea, and that’s perfectly understandable. However, if you’re willing to take a trip to the npm Dark Side, it does offer some interesting add-on possibilities. (That said, Hugo’s single-binary, nearly-everything-out-of-the-box approach has served it well and is impressive.) In `package.json` you’ll find dependencies and scripts to allow the following:

- Lazy-loading of some images through use of [lazyload](https://github.com/verlok/vanilla-lazyload).
- Responsive images through Hugo’s [built-in image processing capabilities](https://gohugo.io/content-management/image-processing/), using code borrowed shamelessly (and adapted for later versions of Hugo) from Stereobooster’s “[Responsive images for Hugo](https://dev.to/stereobooster/responsive-images-for-hugo-dn9).”