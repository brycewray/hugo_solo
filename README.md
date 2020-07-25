# Hugo starter set based on [brycewray.com](https://brycewray.com)

This is the repository from which a shortened, dependencies-free (but also [webmentions](https://indieweb.org)-free), [Hugo](https://gohugo.io)-generated starter-kit version of [brycewray.com](https://brycewray.com) is built. Please note that this is just as an example; the **real** site is done in [Eleventy](https://11ty.dev).

## How to use

1. Clone it to a local repo.
2. Make appropriate changes to `config.toml` to conform to your site’s parameters.
3. Once you have [installed Hugo](https://brycewray.com/posts/2019/04/ec-static), run `hugo serve` from your terminal app.
4. Read the sample posts and their Markdown files to see how everything works.
5. Edit the content to make it your own!

## What’s under the hood

- Lazy-loading of some images through use of [lazyload](https://github.com/verlok/vanilla-lazyload).
- Responsive images through Hugo’s [built-in image processing capabilities](https://gohugo.io/content-management/image-processing/), using code borrowed shamelessly (and adapted for later versions of Hugo) from Stereobooster’s “[Responsive images for Hugo](https://dev.to/stereobooster/responsive-images-for-hugo-dn9).”
- [SCSS](https://sass-lang.com/) [through Hugo Pipes](https://gohugo.io/hugo-pipes/scss-sass/).

**Note**: If you’re not averse to dealing with JavaScript from [npm](https://npmjs.org) plugins and dependencies, you may be interested in another Hugo repo, [hugo_site_css-grid](https://github.com/brycewray/hugo_site_css-grid) which offers the same image processing but also [Tailwind CSS](https://tailwindcss.com) and [PostCSS](https://postcss.org), rather than SCSS, plus support for [webmentions](https://indieweb.org).