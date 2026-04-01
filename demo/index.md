---
title: "Elephes Sung"
subtitle: "Something of a scientist"
author: "King of the Clingenland"
author-url: "https://github.com/ElephesSung"
lang: en
# toc-title: "Contents"
# description-meta: "Personal academic website of Elephes Sung / Fanxin Song at Imperial College London"
# keywords:
#   - bioinformatics
#   - life sciences
#   - Imperial College London
---


## About ME

<table class="about-card">
  <tr>
    <td class="width-min about-photo-cell">
      <figure class="bw-photo about-photo">
        <img src="demo/profile_2.JPG" alt="Elephes Sung" />
        <figcaption>print("hello")</figcaption>
      </figure>
    </td>

    <td class="width-auto about-copy">
      <p>I am currently a PhD student in Life Sciences at Imperial College, with a research interest in <strong>mathematical biophysics and immunology</strong>.</p>

      <p>Previously, I completed an MRes in Systems and Synthetic Biology, also at Imperial College. Even prior to that, I got my bachelor’s degree in Nanomaterials and Nanotechnology.</p>

      <p>Approximately 84% of people mispronounce my name on first reading, while 52.1% confidently assume it is Greek. Neither observation is especially concerning: you are entirely welcome to pronounce it however you wish.</p>

      <p>You can email me at <a href="mailto:eu23@ic.ac.uk?subject=Hello_from_webpage">eu23@ic.ac.uk</a></p>
    </td>
  </tr>
</table>

<br>

---

<br>

## Academic Career Trajectory

This is a horizontal plot, scroll right to check it.

```
/*
            I need more quantitative                                                                                  
            & systematic methods to                                                                                   
            immunological mechanisms                                                                                  
                     │                                                                                                
  2019-2023          │       2023-2024                                                                                
 ┌───────────────┐   │      ┌────────────────────┐                  ┌─────────────────────────────────────────┐       
 │ B.Eng.        ┼───┴─────►│ M.Res. Systems     ┼──────┬──────────►│ PhD in Life Sciences Research           │       
 │ Nanomaterials │          │ & Synthetic Biology│      │           │ President's Scholarship                 │       
 └┬──┬──────────┬┘          └─────────┬──────────┘      │           └──────┬──────────────────────────────────┘       
  │  └─────┬────┘                     │             in between:            │   Project 1. dynamics of interactions    
  │        │~3yrs                     │             ESA Hackthon           │          between killer immune cell      
  │        ▼                          ▼             Bayesian inference     │                     & target cells       
  │   UG project               Master's project       for astronauts'      │                                          
  │   Injectable Hydrogel      Agent-based modelling    health prediction  │   Project 2. dynamics of immune receptors
  │   NK cell delivery         NK cell-tumour                              │          & cell decision-making          
  │         cancer therapy             interactions                        │                                          
  ▼ ~1yr                                                                   │                                          
  lab intern                                                               small confidential project:                
  solar chemical                                                           Google Deepmind & Imperial College         
  battery                                                                                                             
┌──────────────────────────────────────────────────────────────────────────────────────────────────────────────┐      
│  TIMELINE                           TIMELINE                        TIMELINE                     TIMELINE    │      
└──────────────────────────────────────────────────────────────────────────────────────────────────────────────┘      
 */
```

<br>

---

<br>

## My Crappy softwares

<div class="software-list">
<div class="software-card">
<figure class="software-media">
<img src="demo/animation_Tu_12.gif" alt="Animated CytotoxicVision output showing a target cell, nearby immune cells, and fluorescence traces over time." />
<figcaption>Single-cell dynamics from CytotoxicVision.</figcaption>
</figure>
<div class="software-copy">
<h3>CytotoxicVision</h3>
<p>A small but useful imaging pipeline for analysing time-lapse fluorescence microscopy data of NK-cell interactions with 721.221 target cells. Demo data from Dr Cathal Hosty (he was at Dan Davis lab by then)</p>
<!-- <p>It stitches together segmentation, tracking, fluorescence quantification, and contact analysis into one workflow, using <strong>Cellpose</strong>, <strong>CellDetective</strong>, and <strong>btrack</strong>.</p> -->
<p>The current version is still more of a demonstration framework than a polished package, but it already produces interpretable single-cell and population-level readouts.</p>
<p><strong>Repository:</strong> <a href="https://github.com/ElephesSung/CytotoxicVision" target="_blank" rel="noopener noreferrer">github.com/ElephesSung/CytotoxicVision</a></p>
</div>
</div>
<div class="software-card">
<figure class="software-media">
<img src="demo/vis_test.gif" alt="Animated MantiShrimp simulation showing killer and target cells moving within a bounded region over time." />
<figcaption>Agent-based killer-target simulation from MantiShrimp.</figcaption>
</figure>
<div class="software-copy">
<h3>MantiShrimp</h3>
<p>A lightweight agent-based simulator for killer-target immune-cell interactions, built to study migration, contact formation, probabilistic killing, and target death dynamics in 2D.</p>
<!-- <p>It returns both full time-resolved trajectories and analysis-friendly tables, so the same run can be used for animation, mechanistic inspection, and downstream quantification.</p>
<p>The project also includes visualisation tools for simulation playback and a caterpillar-style decision-map analysis for killer contact histories.</p> -->
<p><strong>Repository:</strong> <a href="https://github.com/ElephesSung/MantiShrimp" target="_blank" rel="noopener noreferrer">github.com/ElephesSung/MantiShrimp</a></p>
</div>
</div>
<div class="software-card">
<figure class="software-media">
<img src="demo/lineage_1_raw_only.gif" alt="Animated zebrafish lineage view showing 3D microscopy data and tracked lineage-level structure over time." />
<figcaption>Lineage-level visualisation from the zebrafish analysis pipeline.</figcaption>
</figure>
<div class="software-copy">
<p class="software-status">Confidential software under development</p>
<h3>zebrafish</h3>
<p>An internal zebrafish time-lapse imaging analysis pipeline for preprocessing 4D microscopy data, generating nuclei masks, tracking cells across time, and performing lineage-level heterochromatin dot detection. Data from May Liu at PDN Cambridge. </p>
<!-- <p>The current practical workflow is script-driven: preprocessing, Cellpose segmentation, Ultrack tracking, lineage splitting, crop normalisation, and downstream puncta or big-fish style dot detection.</p> -->
<p><strong>Status:</strong> private repository, active development.</p>
</div>
</div>
</div>



<br>

---

<br>

## Publications

<p>
  <a class="icon-button scholar-button" href="https://scholar.google.com/citations?user=HcFouHYAAAAJ&hl=en" target="_blank" rel="noopener noreferrer" aria-label="Open Google Scholar profile">
    <span>Google Scholar</span>
  </a>
</p>



<details>
<summary> Mathematical Biophysics </summary>
<p>coming soon...</p>
</details>






<details>

<summary>Nanomaterials & Drug Delivery</summary>
<p>
<table class="pub-cards">
  <tr>
    <td class="width-auto">
      <p><strong>Review</strong></p>
      <p>Precision Medicine: The Road to In Vivo Synthetic Therapeutic Agent.</p>
      <p>Yang‐Bao Miao, Zhao Wang, <strong>Fan-Xin Song</strong>, Renchi Gao, Zheng Deng, Guohui Zhang</p>
      <p><em>Advanced Functional Materials</em>, Vol. 35, Issue 47, p. 2510183 (2025)</p>
      <p><a href="https://doi.org/10.1002/adfm.202510183">Read more</a></p>
    </td>
  </tr>
  <tr>
    <td class="width-auto">
      <p><strong>Review</strong></p>
      <p>Recent Progress in Nanomaterial-Based Biosensors and Theranostic Nanomedicine for Bladder Cancer.</p>
      <p><strong>Fan-Xin Song</strong>, Xiaojian Xu, Hengze Ding, Le Yu, Haochen Huang, Jinting Hao, Chenghao Wu, Rui Liang, Shaohua Zhang</p>
      <p><em>Biosensors</em>, Vol. 13, Issue 1, p. 106 (2023)</p>
      <p><a href="https://doi.org/10.3390/bios13010106">Read more</a></p>
    </td>
  </tr>
  <tr>
    <td class="width-auto">
      <p><strong>Article</strong></p>
      <p>Achieving Precise Non-Invasive ROS Spatiotemporal Manipulation for Colon Cancer Immunotherapy.</p>
      <p>Yang-Bao Miao, Hong-Xia Ren, Guohui Zhang, <strong>Fan-Xin Song</strong>, Weixin Liu, Yi Shi</p>
      <p><em>Chemical Engineering Journal</em>, Vol. 481, p. 148520 (2024)</p>
      <p><a href="https://doi.org/10.1016/j.cej.2024.148520">Read more</a></p>
    </td>
  </tr>
  <tr>
    <td class="width-auto">
      <p><strong>Article</strong></p>
      <p>Tailoring a Luminescent Metal–Organic Framework Precise Inclusion of Pt-Aptamer Nanoparticle for Noninvasive Monitoring Parkinson's Disease.</p>
      <p>Yang-Bao Miao, Hong-Xia Ren, Qilong Zhong, <strong>Fan-Xin Song</strong></p>
      <p><em>Chemical Engineering Journal</em>, Vol. 441, p. 136009 (2022)</p>
      <p><a href="https://doi.org/10.1016/j.cej.2022.136009">Read more</a></p>
    </td>
  </tr>
  <tr>
    <td class="width-auto">
      <p><strong>Article</strong></p>
      <p>All-in-One, Solid-State, Solar-Powered Electrochemical Cell.</p>
      <p>Yu Zhao, Chenyang Li, <strong>Fan-Xin Song</strong>, Yi Li, Yan Liu, Yajie Zhao, Xiaohong Zhang, Yu Zhao, Zhenhui Kang</p>
      <p><em>ACS Applied Materials & Interfaces</em>, Vol. 12, Issue 51, pp. 57182–57189 (2020)</p>
      <p><a href="https://doi.org/10.1021/acsami.0c19167">Read more</a></p>
    </td>
  </tr>
</table>
</p>

</details>







<!-- 
## The Basics

This document uses a few extra classes here and there, but mostly it's just markup.
This, for instance, is a regular paragraph.

Look at this horizontal break:

<hr>

Lovely. We can hide stuff in the `<details`> element:

<details>
<summary>A short summary of the contents</summary>
<p>Hidden gems.</p>
</details>

## Lists

This is a plain old bulleted list:

* Banana
* Paper boat
* Cucumber
* Rocket

Ordered lists look pretty much as you'd expect:

1. Goals
1. Motivations
    1. Intrinsic
    1. Extrinsic
1. Second-order effects

It's nice to visualize trees.
This is a regular unordered list with a `tree` class:

<ul class="tree"><li><p style="margin: 0;"><strong>/dev/nvme0n1p2</strong></p>

* usr                               
    * local                         
    * share                         
    * libexec                       
    * include                       
    * sbin                          
    * src                           
    * lib64                         
    * lib                           
    * bin                           
    * games                         
        * solitaire
        * snake
        * tic-tac-toe
    * media                         
* media                             
* run                               
* tmp                               

</li></ul>

## Tables

We can use regular tables that automatically adjust to the monospace grid.
They're responsive. 

<table>
<thead>
  <tr>
    <th class="width-min">Name</th>
    <th class="width-auto">Dimensions</th>
    <th class="width-min">Position</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Boboli Obelisk</td>
    <td>1.41m &times; 1.41m &times; 4.87m</td>
    <td>43°45'50.78"N 11°15'3.34"E</td>
  </tr>
  <tr>
    <td>Pyramid of Khafre</td>
    <td>215.25m &times; 215.25m &times; 136.4m</td>
    <td>29°58'34"N 31°07'51"E</td>
  </tr>
</tbody>
</table>

Note that only one column is allowed to grow.

## Forms

Here are some buttons:

<nav>
    <button>Reset</button>
    <button>Save</button>
</nav>

And inputs:

<form class="grid">
<label>First name <input type="text" placeholder="Placeholder..." /></label>
<label>Last name <input type="text" placeholder="Text goes here..." /></label>
<label>Age <input type="text" value="30" /></label>
</form>

And radio buttons:

<form class="grid">
<label><input name="radio" type="radio" /> Option #1</label>
<label><input name="radio" type="radio" /> Option #2</label>
<label><input name="radio" type="radio" /> Option #3</label>
</form>

## Grids

Add the `grid` class to a container to divide up the horizontal space evenly for the cells.
Note that it maintains the monospace, so the total width might not be 100%.
Here are six grids with increasing cell count:

<div class="grid"><input readonly value="1" /></div>
<div class="grid"><input readonly value="1" /><input readonly value="2" /></div>
<div class="grid"><input readonly value="1" /><input readonly value="2" /><input readonly value="3" /></div>
<div class="grid"><input readonly value="1" /><input readonly value="2" /><input readonly value="3" /><input readonly value="4" /></div>
<div class="grid"><input readonly value="1" /><input readonly value="2" /><input readonly value="3" /><input readonly value="4" /><input readonly value="5" /></div>
<div class="grid"><input readonly value="1" /><input readonly value="2" /><input readonly value="3" /><input readonly value="4" /><input readonly value="5" /><input readonly value="6" /></div>

If we want one cell to fill the remainder, we set `flex-grow: 1;` for that particular cell.

<div class="grid"><input readonly value="1" /><input readonly value="2" /><input readonly value="3!" style="flex-grow: 1;" /><input readonly value="4" /><input readonly value="5" /><input readonly value="6" /></div>

## ASCII Drawings

We can draw in `<pre>` tags using [box-drawing characters](https://en.wikipedia.org/wiki/Box-drawing_characters):

```
╭─────────────────╮
│ MONOSPACE ROCKS │
╰─────────────────╯
```

To have it stand out a bit more, we can wrap it in a `<figure>` tag, and why not also add a `<figcaption>`.

<figure>
<pre>
┌───────┐ ┌───────┐ ┌───────┐
│Actor 1│ │Actor 2│ │Actor 3│
└───┬───┘ └───┬───┘ └───┬───┘
    │         │         │    
    │         │  msg 1  │    
    │         │────────►│    
    │         │         │    
    │  msg 2  │         │    
    │────────►│         │    
┌───┴───┐ ┌───┴───┐ ┌───┴───┐
│Actor 1│ │Actor 2│ │Actor 3│
└───────┘ └───────┘ └───────┘</pre>
<figcaption>Example: Message passing.</figcaption>
</figure>

Let's go wild and draw a chart!

<figure><pre>
                      Things I Have
                                              
    │                                     ████ Usable
15  │
    │                                     ░░░░ Broken
    │
12  │             ░            
    │             ░            
    │   ░         ░              
 9  │   ░         ░              
    │   ░         ░              
    │   ░         ░                    ░
 6  │   █         ░         ░          ░
    │   █         ░         ░          ░
    │   █         ░         █          ░
 3  │   █         █         █          ░
    │   █         █         █          ░
    │   █         █         █          ░
 0  └───▀─────────▀─────────▀──────────▀─────────────
      Socks     Jeans     Shirts   USB Drives
</pre></figure>

## Media

Media objects are supported, like images and video:

![A room in an old French castle (2024)](demo/castle.jpg)

![[The Center of the Web (1914), Wikimedia](https://en.wikisource.org/wiki/Page:The_Center_of_the_Web_(1914).webm/11)](https://upload.wikimedia.org/wikipedia/commons/e/e0/The_Center_of_the_Web_%281914%29.webm)

They extend to the width of the page, and add appropriate padding in the bottom to maintain the monospace grid.

## Discussion

That's it for now.
I've very much enjoyed making this, pushing my CSS chops and having a lot of fun with the design.
If you like it or even decide to use it, please [let me know](https://x.com/owickstrom).

The full source code is here: [github.com/owickstrom/the-monospace-web](https://github.com/owickstrom/the-monospace-web)

Finally, a massive shout-out to [U.S. Graphics Company](https://x.com/usgraphics) for all the inspiration. -->
