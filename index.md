---
title: Introduction
layout: home
nav_order: 1
description: Example Site
permalink: /
---

# Test Site
{: .no_toc }

An easier way to manage documenation — from version conrol to accessibility. 
{: .fs-6 .fw-300 }

## The Key Benefits
{: .no_toc }

- Copy is written in Markdown, a language that can learned by anyone 
- Site contents are converted into .html via a [Jekyll-based](https://jekyllrb.com/) Static Site Generator (SSG)
- Site can be previewed and utilizes git version control (hosted via Github Pages)
- All information is easier searchable. Try it above, at the top of the page
- **Best of all**: It's free. 


Use the built-in navigation menu to the left of the page. This menu is made up of all the individual Markdown files in the git repo for this site. The cascading child and grandchild navigation links are defined in the **front matter** of each Markdown file. 

---
## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Getting Started

To display code syntax, no images or strenuous formatting is needed. Surround a word with `back quotes` and it will appear with code-like syntax.

Similarly, you can introduce code blocks by surrounding entire paragraphs/blocks of code by three back quotes:

```
Syntax is okay
cd your-repository
```
Still, there will be times where you want to insert an image, like this: 

![image](assets\images\fenced-code.png)


## Additional Ways to Represent Data

Author can create tables with Markdown syntax, too. This is done with hyphens and pipes 


|Inputs|Outputs|
|----|----|
|Hello|Goodbye|
|Next|After|
|Number|Word|

If you want a reader to have more information and reference matter from you site, you can utilize footnotes [^1] anywhere. Plus, you can add as many as you want [^2]



### Highlight Text

There are methods to highlight text, too. Some Markdown platforms support "==hello==" on both sides of a word as highlighter syntax. However, not all platforms support that. So, you can use the `<mark>hello</mark>` syntax to highlight text as well. Example: <mark>hello</mark> 


### Create a Checklist
— and, apparently, you can create a task list with brackets and the letter "x"

- [x] Create git repo
- [ ] Clone remote repo with version control client[^3]
- [x] Start managing your project with version control[^4]

This line is for the fifth footnote[^5]



---
[^1]: Here's my footnote. 
[^2]: Second footnote. 
[^3]: Check out the third footnote; they're now seperated from the body copy with a horizontal line; tab in (indent) bullet points to continue your footnote.
    * hello
    * goodbye

[^4]: May the <mark>FOURTH</mark> footnote be with you
    - these are hyphens
    - do they work to continue footnote? Yes, they do!

[^5]: If you include bullet points in your Markdown file, put an extra line space between footnotes to make sure they are correctly formatted
