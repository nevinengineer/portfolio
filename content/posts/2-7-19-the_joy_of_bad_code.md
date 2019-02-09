---
author: "John Nevin"
date: 2019-02-07
title: The Joy of Bad Code
tags: 
  - Coding horror
  - Improvement
  - Python
---
### <u>Part 1</u>
## How can you put *joy* and *bad* in the same sentence?

From any developer's point of view, bad code brings nothing but frustration, confusion and makes our inner-perfectionists cringe.
If you are anything like me, you may be so bold as to scoff and wonder ***"who actually got paid to write this?"***

Before you jump to any conclusions that I'll be defending lazy coding habits and anti-patterns, lets first look into what should be classified as truly "bad code" 

## The earmarks of "bad code"

As a developer in the wild world some have dubbed "Enterprise Software" I have had the distinct displeasure of inheriting a less-than-stellar codebase written by another company.
I'll stop sugar-coating it. There is some straight-up ***hot garbage.***<br/>
Listen, a large portion of it could be straight out of [r/ProgrammingHorror](https://www.reddit.com/r/programminghorror/).

In no particular order of poor taste, I'm talking:

###  * Global variables<br/>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<div>Seriously, if you think you need one, you probably DO NOT.</div>

### * Enigmatic variable names<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<div>IMHO, one letter variable names are only okay for iterator *i*</div> 

### * Mix of cases<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<div>camelCase and snake_case in the same function? More like ***dys***function!</div>

### * Poor code reuse <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<div>Rewriting the *same. exact. function.* across different programs.</div> 

### * ***No*** comments or a ***stitch*** of documentation<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<div>(Want to know what the original author was thinking? Good luck!)</div>

This is like a case-study in how ***not*** to code.

I joked with my fellow devs that the OG authors probably pushed to source with
```bash
git commit -m "changes"
```
***P.S.*** If you found that funny, congrats! Yout get *git* (get it? ha ha ha... )

## The real kicker
Saving the best (or worst) for last?

Our codebase is written in ***Python.***

In case you are unfamiliar with the language, Python has very strong opinions on how code should be styled (thank you, [PEP8](https://www.python.org/dev/peps/pep-0008/)) and designed (keep it [D.R.Y](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)).<br/>

In fact, ***Pythonic*** is a real adjective to describe adherence to Python's principles.

Our codebase was about as un-Pythonic as you can get. This is especially egregious since Python's conventions emphasize readability, clarity and maintainability!

Messy Java? Forgiveable; its a big, verbose language. 

Messy Python? Beg for mercy on your reputation. 

**TL;DR:**
Vented about a poorly written codebase.
Listed telltale signs of bad coding practices.
Extolled the virtues of Python's principles.
<div ALIGN=CENTER>
**[[Part 2]](http://localhost:1313/posts/the-figure-shortcode/)**
</div>

---