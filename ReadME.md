# Horiseon.com

## Table of Contents
1. [ Company Overview. ](#overview)
2. [ New semantic HTML elements. ](#html)
3. [ New accessibility standards. ](#accessibility)
4. [ Updated logical structure. ](#logic)
5. [ Additional edits. ](#edits)
6. [ Additional learnings. ](#learnings)
7. [ The other stuff: License & Badges. ](#streetcred)


<a name="overview"></a>
## Company overview

* Horiseon Social Solutions Services provides businesses with online solutions to increase audience size/reach and sales.

* Horiseon's audience includes small-to-medium sized businesses looking to increase their online presence. They have proven strategies and practices for building foot traffic to a site, increasing search rankings/visibility as well as decreasing outside advertising costs.

* Horiseon seeks to take the pressure and work of customer growth away from the business and put their practices into place. They are solution-driven with measureable results.

<a name="html"></a>
## New semantic HTML elements

* Replaced div with nav for header class content due to three page navigation links in header section

* Replaced div with section that combined .search-engine-optimization, .online-reputation-management, .social-media-marketing

* Replaced div with aside where .benefit-lead img, .benefit-brand img, .benefit-cost img was concerned

<a name="accessibility"></a>
## New accessibility standards

* IMG elements have accessible alt tag attributes & descriptive text

* Figure elements have alt tag & descriptive text

* Added alt tag to hero class for main page img

* Website title updated to Horiseon.com for clairification

* Fixed broken link (SEO)

<a name="logic"></a>
## Updated logical structure

* Reviewed CSS and grouped together duplicate styles across classes, including
    * .benefit-lead, .benefit-brand, .benefit-cost
    * .benefit-lead h3, .benefit-brand h3, .benefit-cost h3
    * .benefit-lead img, .benefit-brand img, .benefit-cost img
    * .search-engine-optimization, .online-reputation-management, .social-media-marketing
    * .search-engine-optimization img, .online-reputation-management img, .social-media-marketing img
    * .search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2

```md
![Image of css file](https://raw.githubusercontent.com/stefanieklogan/Homework1CodeRefractor/main/assets/images/cssexample.PNG)
```

* Added comments before styling as a guide to 1) what was being styled and 2) how

* Html begins with head & title. Moves to body & header before opening up to h1 & h2 along with nav, sections and their content. The document closes with a footer tag and close of body & unclosed divs.

<a name="edits"></a>
## Additional edits

* Fixed .benefit-lead, .benefit-brand, .benefit-cost class bottom-margin to align with Social Media panel.

* Resized IMG files for faster load and better user experience.

<a name="learnings"></a>
## Additional learnings

* How to format a desireable readme file. Just because it's organized on VSC doesn't mean jack to GitHub until you learn some style. I enjoyed it. And no, this comment would not appear in a profile setting/document.

<a name="streetcred"></a>
## The other stuff: License & Badges

* Copyright © Nicolas Gallagher and Jonathan Neal, The MIT License (MIT)

<img src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/>

<img src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>

<img src="https://img.shields.io/badge/<@StefanieDCP>%20-%231DA1F2.svg?&style=for-the-badge&logo=Twitter&logoColor=white"/>