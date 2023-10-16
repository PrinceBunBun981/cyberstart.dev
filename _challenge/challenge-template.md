---
title: Challenge Template
permalink: /challenge/template/
---

1. The top of the file should include [Font Matter](https://jekyllrb.com/docs/front-matter/) for the page:
```
---
title: Hello World
permalink: /challenge/W0148/
---
```
2. The first heading should be the challenge's briefing:
```
### Briefing: 
We've found a profile page of a known hacker that we need to get in contact with but most of the information visible on the page is useless to us. However, there is one secret real way to contact him that he's managed to inject on the page - a hidden email address. Intern, we need you to find his email address! 

**Tip:** The email address is the flag. 
```
3. The next heading should be the hint if one is available:
```
### Hint: 
Try highlighting the whole page (i.e. select all) to find text that might be the same colour as the background. 
```
4. The next should be how to solve the challenge:
```
### How to Solve: 
1. Using CTRL + A will highlight the whole page revealing the email hidden underneath the “Send me an email” button. 
```
5. The final heading should be the answer. This is only in cases where the answer to a challenge **never** changes:
```
### Answer: 
- 1337hax@myaboutpage.com 
```
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
```