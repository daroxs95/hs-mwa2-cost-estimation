---
theme: seriph
background: /bg.jpg
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
drawings:
  persist: false
transition: slide-left
title: Cost estimation
mdc: true
fonts:
  # basically the text
  sans: 'Hebo'
  # use with `font-serif` css class from windicss
  serif: 'Robot Slab'
  # for code blocks, inline code, etc.
  mono: 'Fira Code'
themeConfig:
  primary: '#ffda44'
download: true
---

# Team West
## Cost estimating

[//]: # (<p class="">Game store for the masses</p>)

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://github.com/daroxs95/destore)
-->

---

# Individual Costs:

<div style="transform: scale(0.8) translateY(-90px)">

| Domain |         (6.57 Euros) |  
|----|---------------------:|
| VPS |         (4.51 Euros) |
| S3 | Storage (3.81 Euros) |
| Emails |        (13.80 Euros) |
| Flare |            (9 Euros) |
| Forge |           (12 Euros) |
| SSL |            (0 Euros) |
| SSL |            (0 Euros) |
| CDN |            (0 Euros) |
| Backup |            (0 Euros) |
| Total |          46.69 euros |

</div>

---

# Shared Service Costs (Example for 80 websites):

Assuming the developer has around 80 websites and shares some services among them, the cost per website will be significantly reduced:

| Domain | (6.57 Euros) |
|----|---------------------:|
| Flare | (29.9 Euros/8 =,0.37 ) |  
| Forge | (19 Euros/80 = 0.23) |
| Postmark | (55 Euros/80 = 0.68) |
| VPS | (4.51 Euros/80 = 0.06) |
| S3 Storage | (3.81 Euros/80 = 0.05) |
| Total | 7.96 euros |

---
layout: center
class: text-center
---
# Thanks 👋

