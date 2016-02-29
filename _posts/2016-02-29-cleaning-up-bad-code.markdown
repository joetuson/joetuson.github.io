---
layout: post
title:  "Cleaning up bad code"
date:   2016-02-29 08:39:13 -0800
categories: quotes engineering
---

From Robert Martin's classic, <a  href="http://www.amazon.com/gp/product/0132350882/ref=as_li_tl?ie=UTF8&camp=1789&creative=9325&creativeASIN=0132350882&linkCode=as2&tag=joetusoncom-20&linkId=FLR4PMOY2PEGKINQ">Clean Code</a><img src="http://ir-na.amazon-adsystem.com/e/ir?t=joetusoncom-20&l=as2&o=1&a=0132350882" width="1" height="1" border="0" alt="" style="border:none !important; margin:0px !important;" />


> It is not enough for code to work. Code that works is often badly broken. Programmers who satisfy themselves with merely working code are behaving unprofessionally. They may fear that they don’t have time to improve the structure and design of their code, but I disagree. Nothing has a more profound and long-term degrading effect upon a development project than bad code. Bad schedules can be redone, bad requirements can be redefined. Bad team dynamics can be repaired. But bad code rots and ferments, becoming an
inexorable weight that drags the team down. Time and time again I have seen teams grind to a crawl because, in their haste, they created a malignant morass of code that forever thereafter dominated their destiny. 

> Of course bad code can be cleaned up. But it’s very expensive. As code rots, the modules insinuate themselves into each other, creating lots of hidden and tangled dependencies. Finding and breaking old dependencies is a long and arduous task. On the other hand, keeping code clean is relatively easy. If you made a mess in a module in the morning, it is easy to clean it up in the afternoon. **Better yet, if you made a mess five minutes ago, it's very easy to clean it up right now.**

So the solution is to continuously keep your code as clean and simple as it can be. Never let the rot get started.