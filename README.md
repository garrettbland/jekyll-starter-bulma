# jekyll-starter

Quickly get a jekyll website up and going with bulma css, a smart directory structure, and community standard seo practices

[![](https://github.com/garrettbland/jekyll-starter-bulma/blob/master/README.jpg)

#### Features
- Bulma CSS framework + SCSS
- Community Standard SEO practices
- _pages (Put all your pages in a seperate directory for tidy-ness)
- Customizable permalinks
- Starter config, header, template, css and footer files

#### Installation

1. `git clone https://github.com/garrettbland/jekyll-starter.git`
2.  `cd jekyll-starter`
3. `yarn install`
4. `jekyll serve` *or*  `jekyll build`

#### Getting Started
Refer here for documentation
##### Adding a new page
1. Create a new directory inside `_pages`. Lets call it `contact`
2. Create a new file inside your new directory called `index.html`
3. Copy the YAML front matter below into your new file. Reload your page and navigate to `http://127.0.0.1:4000/contact/` to see your new page in action

```yaml
---
layout: default
title: "Contact"
description: "Contact us page. Also meta descriptions"
socialimage: "/img/social-image-contact.jpg"
permalink: "/contact/"
---
```

#### Status
This is still a work in progress. If you see something that could be added or changed for the better, please send me a pull request!

#### New to Jekyll?
Get started here
https://jekyllrb.com/docs/installation/
