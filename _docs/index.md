---
title: Welcome
permalink: /docs/home/
redirect_from: /docs/index.html
---

## Getting started

[Download the Jar](https://pages.github.com) to get started setting up your application. As a lightweight, platform independent software, you don't need any complicated installer setups or configuration. Additionally, you can pull the source code directly from my [GitHub Repository](https://github.com/ephraimbennett/Scraping) if you are more technical and would like to compile and execute yourself. 
### Coming soon
I'm working on bundling the application with a small JRE, which will allow you to run ESpider without having your own version of Java installed. It will only be compatible with windows for now.

## Writing content

### Docs

Docs are [collections](https://jekyllrb.com/docs/collections/) of pages stored under `_docs` folder. To create a new page:

**1.** Create a new Markdown as `_docs/my-page.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

**2.** Add the pagename to `_data/docs.yml` file in order to list in docs navigation panel:

```
- title: My Group Title
  docs:
  - my-page
```

### Blog posts

Add a new Markdown file such as `2017-05-09-my-post.md` and write the content similar to other post examples.

### Pages

The homepage is located under `index.html` file. You can change the content or design completely different welcome page for your taste. (You can use [bootstrap components](http://getbootstrap.com/components/))

In order to add a new page, create a new `.html` or `.md` (markdown) file under root directory and link it in `_includes/topnav.html`.
