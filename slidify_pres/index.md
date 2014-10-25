---
title       : Would You Rather?
subtitle    : 
author      : Kevin Fischer
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Did you ever want to know where people sit on the hard hitting questions?

<figure>
<img src="./assets/img/socks.jpg" style="float: left;"" />
</figure>

<figure>
<img src="./assets/img/hair.jpg" style="float: left;" />
</figure>


<div style="position: absolute; bottom: 10px;">
Images and idea courtesy of
http://www.buzzfeed.com/javiermoreno/the-toughest-game-of-would-you-rather-you-will-ever-play</div>

--- .class #id 

## Implementation



1. Multiple questions not dependent on each other.

2. Handles multiple users and computes in real time.

3. Simple, quick calculations.

People choosing wet socks: 43
Number of submitted answers: 68

<div style="position: absolute; bottom: 150px;">

```
## [1] 0.6323529
```
<div>

--- .class #id

##App
<figure>
<img src="./assets/img/screen.jpg" style="float: left;" />
</figure>


--- .class #id

## User Input
>1. Radiobuttons to allow only on selection.
>2. Selection not calculated until user hits the submit button.
>3. Seperate button for each question.
