---
title: Assignment by Prashant
layout: demo_template
author: Prashant
---

| [Page 2](./web_pages/Page2.html) | [IBM Page](./web_pages/IBM_page.md) | [Titanic](./web_pages/titanic.md) |

### This page is written by {{page.author}}

# Heading 1 sample

Above line shows an example of **Heading 1**

## Heading 2 sample

Above line shows an example of *Heading 2*

{% include sampleText.txt %}

Below is the sample of a *unordered list*:

* Item 1
* Item 2
* Item 3

Below is the sample **table**.

| Column 1 | Column 2 |
|---|---|
| R1C1 | R1C2 |
| R2C1 | R2C2 |

Following are the sample for `steps`.

1. Step 1
2. Step 2
3. Step 3

Below is the for loop example with Liquid `syntax'

**Name** - **Place**

{% for item in site.data.practice_data %}
{{item.Name}} - {{item.Age}}
{% endfor %}

You can embedd an image using `image syntax`

![Sample Image](https://cdn.pixabay.com/photo/2015/04/19/08/32/marguerite-729510_960_720.jpg)