---
title: Examples
type: page
description: Typography and engineering feature summary and examples
slug: examples
menu: main
date: 2018-12-29
lastmod: 2018-12-30
authors: ["patevs"]

tags:
  - engineering
  - markdown
  - math
  - graphviz
  - waveform
  - chart
  - flowcharts

mathjax: true
viz: true
wave: true
chart: true
msc: true
flowchart: true

toc: true
weight: -230
---

Here is a paragraph. **Lorem ipsum _dolor_ sit amet**, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

## Heading 2

Another one. Ut enim ad minim veniam, _quis nostrud exercitation **ullamco** laboris nisi ut aliquip ex ea commodo consequat_. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

{{% center %}}
### Heading 3

Yet another, but centered! Excepteur sint occaecat ~~cupidatat non proident, sunt in culpa qui officia~~ deserunt mollit anim id est laborum.
{{% /center %}}

#### Heading 4

1. First item
2. Second item
  - Nested unordered item
3. Third item
  1. Nested ordered item 1
  2. Nested ordered item 2

##### Heading 5

Where are the quotes!!!

> Simplify, then add lightness.  
— Colin Chapman

Now, [time for some links](/typography#heading-5)!

- [GoHugo]
 - [Hugo Themes][1]

[GoHugo]: https://gohugo.io
[1]: https://themes.gohugo.io/

###### Heading 6

Inline code: `echo "What is the meaning of life?"`. Who knows?

```javascript
// Codeblock

var meaningOfLife = 42;
console.log('The meaning of life is: ', meaningOfLife);
```

---

Who wants some table?

  Engimo  |  Caption  | More Caption
 -------- | --------- | ------------
   Cool   |   What?   |  Now, wut?!


Ah, enough for today, eh?

## Math

$
  \frac{d}{dx}\left( \int_{0}^{x} f(u)\,du\right)=f(x)
$


$
A_n = \begin{pmatrix} 
a_1 & a_2 & \ldots & a_n \\\\  
b_1 & b_2 & \ldots & b_n \\\\ 
\end{pmatrix}
$


## Graphviz

```viz-dot
  digraph g { 
  node[shape="circle" , label="", width=0.2, height=0.2]
  l1[xlabel="v\(s\)"]
  l21[xlabel="a", width=0.1, height=0.1 , style=filled]
  l22[width=0.1, height=0.3, style=filled]
  l31[xlabel="v\(s'\)"]

  l1 -> l21
  l1 -> l22
  l21 -> l31 [xlabel="r"]
  l21 -> l32
  l22 -> l33
  l22 -> l34
  }
```

## Waveform

```wave
{ 
  "signal": [ {"name": "CLK", "wave": "p.....|..."},
            {"name":"DAT", "wave":"x.345x|=.x", "data":["A","B","C","D"]},
            {"name": "REQ", "wave": "0.1..0|1.0"},
            {},
            {"name": "ACK", "wave": "1.....|01."}
]}
```

## Chart

```chart
    {
    "type": "line",
        "data": {
            "labels": ["One", "Two", "Three", "Four", "Five", "Six"],
            "datasets": [
            {
                "label": "# of Votes",
                "data": [12, 19, 3, 5, 2, 3]
            }
            ]
        }
    }
```

## MSC

```msc
Andrew->China: Says Hello
Note right of China: China thinks\nabout it
China-->Andrew: How are you?
Andrew->>China: I am good thanks!
```

## Flowcharts

```flowchart
  st=>start: Start:>http://www.google.com[blank]
  e=>end:>http://www.google.com
  op1=>operation: My Operation
  sub1=>subroutine: My Subroutine
  cond=>condition: Yes
  or No?:>http://www.google.com
  io=>inputoutput: catch something...
  para=>parallel: parallel tasks

  st->op1->cond
  cond(yes)->io->e
  cond(no)->para
  para(path1, bottom)->sub1(right)->op1
  para(path2, top)->op1
```
## Deprecated pages

<div class="deprecated">This page has been marked as deprecated.</div>

----