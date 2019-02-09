---
author: "John Nevin"
date: 2019-02-07
title: The Joy of Bad Code
tags: 
  - python
  - improvement
  - business
---

## How can you put *joy* and *bad* in the same sentence?

From any developer's point of view, bad code brings nothing but frustration, confusion and makes our inner-perfectionists cringe.
If you are anything like me, you may be so bold as to scoff and wonder ***who actually got paid to write this?"

Before you jump to any conclusions that I am defending lazy coding habits and anti-patterns, lets first look into what should be classified as truly "bad code" 

## The Earmarks of "Bad Code"

As a developer in the wild world some have dubbed "Enterprise Software" I have had the distinct displeasure of inheriting a less-than-stellar codebase written by another company.
And by less-than-stellar, I mean heinously poor. 
Okay I'll stop sugar coating it. I have straight up told my boss it is ***hot garbage.***
Listen, a large portion of it was straight out or r/CodingHorror.

In no particular order of poor taste, I'm talking

* Global Variables 
(seriously, if you think you need one, you probably DO NOT)
* Awful variable names 
(IMHO, one letter variable names are only okay for iterator *i* )
* Mix of cases
(camels and snakes in the same class? Even Noah kept them separate on the Ark!)
* NO comments or a STITCH of documentation
(Want to know what the developer who wrote it was thinking? Good luck!)

Yeah really, it is like a case-study in how ***not*** to code.

My fellow developers were joking that whoever wrote this monstrosity also used **git commit -m "changes"** when pushing code!






> An apple is a sweet, edible fruit produced by an apple tree (Malus pumila). Apple trees are cultivated worldwide, and are the most widely grown species in the genus Malus. The tree originated in Central Asia, where its wild ancestor, Malus sieversii, is still found today. Apples have been grown for thousands of years in Asia and Europe, and were brought to North America by European colonists. Apples have religious and mythological significance in many cultures, including Norse, Greek and European Christian traditions.[^1]

---

Inline styles：

**strong**, *emphasis*, ***strong and emphasis***,`code`, <u>underline</u>, ~~strikethrough~~, :joy:🤣, $\LaTeX$, X^2^, H~2~O, ==highlight==, [Link](https://example.com), and image:

![img](https://picsum.photos/600/400/?random)

---

Headings:

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

Table:

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ | :-------------: | ------------: |
| col 3 is      | some wordy text |         $1600 |
| col 2 is      |    centered     |           $12 |
| zebra stripes |    are neat     |            $1 |

Lists:

* Unordered list item 1.
* Unordered list item 2.

1. ordered list item 1.
2. ordered list item 2.
   + sub-unordered list item 1.
   + sub-unordered list item 2.
     + [x] something is DONE.
     + [ ] something is NOT DONE.

Syntax Highlighting:

```javascript
var num1, num2, sum
num1 = prompt("Enter first number")
num2 = prompt("Enter second number")
sum = parseInt(num1) + parseInt(num2) // "+" means "add"
alert("Sum = " + sum)  // "+" means combine into a string
```

[^1]: From https://en.wikipedia.org/wiki/Apple
