---
title: Welcome
permalink: /challenge/home/
redirect_from: /challenge/index.html
---

## Getting started

The site was made possible through [GitHub Pages](https://pages.github.com) along with the [Jekyll Doc Theme](https://github.com/aksakalli/jekyll-doc-theme).

While in CyberStart, the challenge links are typically `play.cyberstart.com/challenge/(id)`, simply change the `.com` to `.dev` and you should find the walkthrough you are looking for.
If there is no walkthrough, feel free to make a [Pull Request](https://github.com/PrinceBunBun981/cyberstart.dev/pulls) with steps to complete the challenge, or an [Issue](https://github.com/PrinceBunBun981/cyberstart.dev/issues) requesting for a walkthrough.

<hr>

## Writing content

### For Preexisting Challenges

At the bottom of each challenge page is a button saying `Improve this page`, this will allow you to fork this repository, edit any pages needed, and submit a Pull Request with updated information.


### For New Challenges

Challenges are [collections](https://jekyllrb.com/docs/collections/) of pages stored under the `_challenge` folder. To create a new page:

**1.** Create a new Markdown as `_challenge/level-name/challenge-id.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: Challenge Name
permalink: /challenge/challenge-id/
---

Hello World!
```

**2.** Add the pagename to `_data/challenges.yml` file in order to list in challenges navigation panel:

```
- title: Level Name
  challenges:
  - challenge-id
```

Check the `_challenge` directory for examples on how pages should look and the `challenges.yml` file for examples on how to handle sorting pages in the navigation.

### Adding Assets

Assets can be added to challenge pages to show extra information or provide more help. Assets in PRs should be in the specific level directory in the assets directory (`assets/img/level`).
```
<img src="../../assets/img/level/challenge-id.png" alt="Image Alt Text">
```

*Changes to your PR may be requested or made in the event that you forget to do something, so no worries if you forget something!*