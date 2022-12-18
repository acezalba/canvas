# Canvas Theme

A starter theme for Grav CMS. Designed for small, text-heavy personal sites and blogs. Uses [sanitize.css](https://csstools.github.io/sanitize.css/) and a customized [simple.css](https://simplecss.org/). Mostly classless.

## Features

- Support for the following templates:
	+ `default`
	+ `error`
	+ `blog` - creates a list of its child pages
	+ `item` - intended as a child page of `blog` directories.
- Supports `category` and `tag` modules for `item` templates.
- SEO-Friendly
	+ natively supports and generates basic OpenGraph, Twitter Card, and Schema.org metadata for your content
	+ allows you to customize your preview image for social sharing on a site and page level.
- Light and dark themes
- Color customization
- Favicon customization
- Switch navigation between the header and footer.

## Installation

The current iteration of Canvas can only be installed via cloning the directory to your `user/themes`. Activate it by editing or adding the following line in your `user/config/system.yaml`

```yaml
pages:
	theme: canvas
```

Clear your cache via the Admin panel or through `bin/grav cache` in your project terminal. Copy the default `canvas.yaml` bundled with the theme to your `user/config/themes` to start customizing the colors of your site using hex codes. However, editing the site via the Grav Admin panel is recommended to use features not included in the theme config file.

## Upcoming Features

The following features are planned before the release of Version 1.0:

- support for `modular` and `form` templates
- support for the following official Grav plugins
	+ Form (`form`)
	+ Related Pages (`relatedpages`)
	+ Feed (`feed`)
	+ Pagination (`pagination`)
	+ Breadcrumb (`breadcrumb`)
	+ Simplesearch (`simplesearch`)
	+ Sitemap (`sitemap`)
	+ TaxonomyList (`taxonomylist`)
	+ MarkdownNotices (`markdownnotices`)
- incorporate useful `hypertext` theme settings
- demo and testing content
- Google Font customization
- Support Grav's asset manager in handling js and css resources.
- accessibility improvements.