# jekyll-starter-bulma

_Quickly get a jekyll website up and going with bulma css, a smart directory structure, and community standard seo practices_

![jekyll-starter-bulma](https://github.com/garrettbland/jekyll-starter-bulma/blob/master/README.jpg)

### Features
- Barebons Jekyll Setup
- Bulma CSS framework
- Community Standard SEO practices
- Seperate pages and news directory. (Put all your pages in separate directories for tidy-ness)
- Customizable permalinks
- Starter config, header, template, css and footer files
- Plugin Free!
- Sitemap.xml generator

### Installation

1. `git clone https://github.com/garrettbland/jekyll-starter-bulma.git`
2.  `cd jekyll-starter-bulma`
3. `jekyll serve` *or*  `jekyll build`

### Getting Started
Refer here for documentation

#### Adding a new page
1. Create a new directory inside `_pages`. Lets call it `contact`
2. Create a new file inside your new directory called `index.html`
3. Copy the YAML front matter below into your new file. Reload your page and navigate to `http://127.0.0.1:4000/contact/` to see your new page in action
4. Add in your html below the front matter

```yaml
---
layout: default
title: "Contact"
description: "Contact us page. Also meta descriptions"
socialimage: "/img/social-image-contact.jpg"
permalink: "/contact/"
---
```

#### Adding a new post
1. Create a new file inside `_news`. Lets call it `article.md` (_or .html_)
2. Copy the YAML front matter below into your new file. Reload your page and navigate to `http://127.0.0.1:4000/news/article/` to see your new post in action
4. Add in your html below the front matter

```yaml
---
layout: default
title: "Garretts News Article"
description: "Some awesome news about Garrett. He just learned how to create stuff."
socialimage: "/img/social-image-about.jpg"
---
```

### Status
This is still a work in progress. If you see something that could be added or changed for the better, please send me a pull request!

### New to Jekyll?
Get started here
https://jekyllrb.com/docs/installation/
