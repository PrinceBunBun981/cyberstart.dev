---
title: Welcome
permalink: /challenge/home
redirect_from: /challenge/index.html
---

## Getting started

The site was made possible through [GitHub Pages](https://pages.github.com) along with the [Jekyll Doc Theme](https://github.com/aksakalli/jekyll-doc-theme).

While in CyberStart, the challenge links are typically `play.cyberstart.com/challenge/(id)`, simply change the `.com` to `.dev` and you should find the walkthrough you are looking for.
If there is no walkthrough, feel free to make a [Pull Request](https://github.com/PrinceBunBun981/cyberstart.dev/pulls) with steps to complete the challenge, or an [Issue](https://github.com/PrinceBunBun981/cyberstart.dev/issues) requesting for a walkthrough.

## Writing content

### Challenges

Challenges are [collections](https://jekyllrb.com/docs/collections/) of pages stored under the `_challenge` folder. To create a new page:

**1.** Create a new Markdown as `_challenge/level-name/my-page.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /challenge/my-page/
---

Hello World!
```

**2.** Add the pagename to `_data/challenges.yml` file in order to list in challenges navigation panel:

```
- title: My Group Title
  challenges:
  - my-page
```