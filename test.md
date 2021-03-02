---
title: Demonstration Document
category: Wiki
tags: 
description: >
  This whole section (wrapped in `---` is called frontmatter. It is YAML-formatted information and won't be rendered
   in the preview window. 
   It can contain any keys you wish, but Deepdwn only uses the following:
  `title` if available in the file list, but will show the filename instead if you haven't added a title yet.
  `category` is a single value, used for organizing similar content together.
  Like the category, `tags` are used to group content together. Unlike `category` a document can have multiple tags.
---


# Operation SummerSault


This is the core of the operation

## Checklists

Did you find all clues
* [X] First 
* [ ] Second

## Tables

| d4 | Description |
| :------: | ----------- |
| 1        | Deep One. |
| 2        | Thoughtful One. |
| 3        | Ascetic One. |
| 4        | Avatar. |

## Graphs and Diagrams


```
flowchart TB
    subgraph debrefing
    a1[Enter the scene of the crime ]-->a2[talk with the handler]
    end
    subgraph id1[the apartment]
    b1{did you avoid detection}--YES-->b2[deal with noisy neighbor]
    b1--NO-->b3[you are in]
    b3-->b4[find key of cabin]
    b2-->b4
    end
    subgraph id2[the cabin]
    c1[open door]-->c2[find locked basement]
    c1[open door]-.->c3[find hidden stash]
    c2-->c4{confront enemy}
    c3-->c4
    end
    debrefing --> id1[the apartment]
    id2 --> id1
    id1 --> id2
```

## Music


```abc
T:Red Book Sonata, The   % title
T:King in Yellow         % an alternative title
M:4/4
DEFG ABcd|\
DEFG ABcd|\
DEFG ABcd|]
DEFG ABcd|\
DEFG ABcd|\
K:C Major
DEFG ABcd|]
T:when the king wants you at the ball
DEFG ABcd|\
DEFG ABcd|\
DEFG ABcd|]
T:you can't escape his invitation
DEFG ABcd|\
K:C Minor
DEFG ABcd|\
K:Cm
DEFG ABcd|]
T:Always wear a mask
DEFG ABcd|\
K:C Phrygian
DEFG ABcd|\
K:C Locrian
DEFG ABcd|]
```