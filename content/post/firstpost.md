+++
title = "CSS: REM vs EM vs PX"
date = "2016-10-13T13:39:46+02:00"
toc = true
comments = true
+++

What do these units in CSS mean?

```css
.user-profile .user-avatar {
    margin-left:    1rem;
    margin-top:     1em;
    margin-right:   1px;
}
```

## What is REM?

One REM is defined as equal to the font-size of the ROOT element. For front-end web folk, this is the ```<html>``` tag.     

## What is EM?

One EM is defined as equal to the font-size of the containing element.     

## What is PX?

PX is the only constant unit of the lot. It is independent of any attribute on the root or container. 


Believe it or not there are several other units available in vanilla CSS: cm, mm, in, pt, pc, %. 