# Hugo Lithium

A simple responsive blog theme for [Hugo](https://gohugo.io/).

![Hugo Lithium Theme Screenshot](https://raw.githubusercontent.com/janikvonrotz/hugo-lithium-theme/master/images/screenshot.png)

## Features

- Blog
- Search template
- Responsive
- Disqus
- Google Analytics
- Tags and Categories
- Featured Image
- Twitter Cards
- Open Graph metadata
- Archive template

## Installation

Run the following inside your Hugo site folder:

```
$ mkdir themes
$ cd themes
$ git clone https://github.com/janikvonrotz/hugo-lithium-theme
```

## Configuration

Take a look at the sample [config.toml](https://github.com/janikvonrotz/hugo-lithium-theme/blob/master/exampleSite/config.toml)
file located in the [exampleSite](https://github.com/janikvonrotz/hugo-lithium-theme/blob/master/exampleSite) folder.

### Search

Checkout this blogs post for deails: [Janik von Rotz - Simple Hugo page search with Lunr.js](https://janikvonrotz.ch/2019/06/10/2019-06-10-simple-hugo-page-search-with-lunrjs/)

By default this template will create a JSON document of all posts. If you define a `search` page using [this search page template](https://raw.githubusercontent.com/janikvonrotz/hugo-lithium-theme/master/exampleSite/content/page/search.md) you will get a site wide search based on [lunr.js](https://lunrjs.com/).

## Content Types

### Post

Used for blog posts. Blog posts are listed on the homepage.

Run `hugo new post/<post-name>.md` to create a post.

### Page

Used for site pages.

Run `hugo new page/<page-name>.md` to create a page.

## License

The code is available under the [MIT license](https://github.com/janikvonrotz/hugo-lithium-theme/blob/master/LICENSE.md).

## Color Scheme

    font very dark: #222
    font dark: #555
    font light: #888
    font very light: #ccc
    theme dark: #A2DAC3
    theme light: #CBF8DF
    background light: #f5f5f5
    background dark: #bbb
    font header: #111
    font header active: #000

## Source

[Mozilla Docs - Main Element](https://developer.mozilla.org/de/docs/Web/HTML/Element/main)  
[Mozilla Docs - Article Element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article)
