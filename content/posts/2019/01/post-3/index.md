---
title: "Post 3 with its UNIQUE title" # Quotation marks allow colons, semicolons, etc.
subtitle: "The UNIQUE Post 3 subtitle" # Quotation marks allow colons, semicolons, etc.
description: "The UNIQUE description for Post 3." # Quotation marks allow colons, semicolons, etc.
author: Your name goes here
date: 2019-01-19T09:25:00 # This would be 9:25 AM (0925) UTC on Jan. 19, 2019
lastmod: 2019-10-06T19:00:00 # Comment-out this line with a # if content is unchanged
draft: false # Make it "true" if you don't want Hugo to "publish" yet
featured_image: /images/lego-169603_1280x960.jpg # Or whatever image you want to use
featured_image_alt: Lego blocks arranged stylistically # Always include an ALT tag for accessibility
featured_image_caption: "Image: M W; Pixabay" # Quotation marks to allow colon
---

 Your opening text goes here.

## In-article heading --- it's an H2 because your title is the H1

And after another paragraph or two or three, you may want to add a subheading, which would be an H3, so it would be like the following.

### Subheading (H3)

Text here.

And here is an example of how to use the `img` shortcode in `/layouts/shortcodes` (note that the images must be in the same folder with the content, because of how Hugo bundles do image processing, so that's why the `src` references don't include a folder upfront):

{{< img src="screen-cap-from-Pippin-Williamson-s-page-builders-review.png" alt="Screen capture showing shortcodes from a WordPress page builder" >}}

Closing text. That ends Post 3!