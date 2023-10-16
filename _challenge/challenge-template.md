---
title: Challenge Template
permalink: /challenge/template/
---

1. The top of the file should include [Font Matter](https://jekyllrb.com/docs/front-matter/) for the page.
2. The first heading should be the challenge's briefing.
3. The next heading should be the hint if one is available.
4. The next should be how to solve the challenge.
5. The final heading should be the answer. This is only in cases where the answer to a challenge **never** changes.
6. Assets for the challenge can be placed where needed, but if there is no specific place for them, add a heading titled `Assets` and place them there.

*HTML can be used throughout the Markdown files if needed, an example of this can be found [here](https://play.cyberstart.dev/challenge/W0001/) in the table.*

<hr>

Here's a full example of what the file should look like:
```
---
title: Still Hiding
permalink: /challenge/S0001/
---

### Briefing:
This is some example text for the briefing.

**Tip:** A tip is often included in the challenge briefing.

### Hint:
You can spend points on a hint or after completion of a challenge, you can look at the hint for free. (Hints are greatly appreciated in PRs!)

### How to Solve:
1. Step 1
2. Step 2
3. Step 3

### Answer:
- answersAreSometimesStatic!

### Assets:
<img src="./assets/image.png" alt="Image Alt Text">
```