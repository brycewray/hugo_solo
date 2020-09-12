# Hugo starter set

This is a starter set for the [Hugo](https://gohugo.io) [static site generator (SSG)](https://staticgen.com), based on my website at [brycewray.com](https://brycewray.com).

See the [online demo](https://hugo-solo.netlify.app).

[![Netlify Status](https://api.netlify.com/api/v1/badges/124673ed-cd4c-4174-86c5-7da8785985fb/deploy-status)](https://app.netlify.com/sites/hugo-solo/deploys)

## How to use

1. Clone this to a local repo.
2. Make appropriate changes to `config.toml` to conform to your site’s parameters.
3. Once you have [installed Hugo](https://gohugo.io/getting-started/installing/), run `hugo serve` from your terminal app. You can then view the site in [http://localhost:1313](http://localhost:1313) on your computer.
4. Read the sample posts and their Markdown files to see how everything works.
5. Edit the content to make it your own!
6. When ready, [deploy the site](https://gohugo.io/hosting-and-deployment/) to your chosen host.

## What’s under the hood

- Lazy-loading of some images through use of [lazyload](https://github.com/verlok/vanilla-lazyload).
- Responsive images through Hugo’s [built-in image processing capabilities](https://gohugo.io/content-management/image-processing/), using code borrowed shamelessly (and, where necessary, adapted for later versions of Hugo) from Stereobooster’s “[Responsive images for Hugo](https://dev.to/stereobooster/responsive-images-for-hugo-dn9)” and Strict Panda’s “[Using Image Processing to Load Images in Hugo](https://blog.strict-panda.com/post/image-processing-media-queries/).” (The **real** site’s repo now uses [Cloudinary](https://cloudinary.com) rather than having the images in the repo and processing them as such.)
- [SCSS](https://sass-lang.com/) [through Hugo Pipes](https://gohugo.io/hugo-pipes/scss-sass/).

**Note**: If you’re not averse to dealing with JavaScript from [npm](https://npmjs.org) plugins and dependencies, you may be interested in another Hugo repo, [hugo_site_css-grid](https://github.com/brycewray/hugo_site_css-grid), which offers not only the same lazy-loading and image processing but also **[Tailwind CSS](https://tailwindcss.com)** and **[PostCSS](https://postcss.org)**, rather than SCSS.