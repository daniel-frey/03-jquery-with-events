![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 03: jQuery Events
===

## Code Wars Challenge

Complete [today's Kata](https://www.codewars.com/kata/insert-dashes) and follow the submission instructions from Lab 01.

## Lab 03 Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[jQuery cheatsheet](https://oscarotero.com/jquery/)

[Template Literals MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)

## Configuration
_Your repository must include:_

```
03-jquery-with-events
└── starter-code
└── driver-navigator
  ├── .eslintrc.json
  ├── .gitignore
  ├── LICENSE
  ├── index.html
  ├── scripts
  │   ├── article.js
  │   ├── articleView.js
  │   └── blogArticles.js
  ├── styles
  │   ├── base.css
  │   ├── layout.css
  │   └── modules.css
  └── vendor
      └── styles
          ├── fonts
          │   ├── icomoon.eot
          │   ├── icomoon.svg
          │   ├── icomoon.ttf
          │   └── icomoon.woff
          ├── icons.css
          └── normalize.css
  └── PULL_REQUEST_TEMPLATE.md
  └── README.md
```

## User Stories and Feature Tasks

*As a user, I want to be able to filter my articles so that I can selectively view articles by author or by category.*

- Complete the new requirements for setting `data-<attributes>` in your `toHtml()` method.
- Complete the methods for handling filter events when selecting an option from a drop down menu via Authors and Categories so that only the selected articles are displayed on the screen.

*As a user, I want to be able to preview each article so that I can easily view the results and select the one I want to read further.*

- Add an event to reveal a complete article if the user would like to see more of it beyond the teaser.

*As a user, I want tab-based navigation so that I can easily visit other sections of my site.*

- Complete the method `articleView.handleMainNav()` for implementing tab-based event navigation on the page.

*As a developer, I want my code to be thoughtfully organized, easy to read, and executing efficiently.*

- Review and understand the new JS file, `articleView.js`
- Add any new script tags to your HTML.
- Refactor concatenation using template literals.
- Render the app upon page load.

### Stretch Goal

*As a user, I want to be able to collapse an expanded article to the teaser view so that I can more easily scan over a series of articles.*

- Build in functionality such that a user can click on "Show Less" to collapse a full article into a teaser.

## Documentation
_Your README.md must include:_

```md
# Project Lab 03

**Author**: Daniel / Vince
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
This application will show / hide all articles based on the author / category chosen. It will also truncate and show the paragraphs based on "read on"

## Getting Started
Download the source code, start up live server, and you're good to go.

## Architecture
Using extensive jquery, javascript and a smidgen of CSS this app could easily be attached to a database and allow use of (eessentially) a cms.

## Change Log
Author: Daniel Frey <dann.frey@me.com>
Date:   Thu Aug 16 13:38:43 2018 -0700 - added readme

Author: Daniel Frey <dann.frey@me.com>
Date:   Thu Aug 16 13:36:03 2018 -0700 - finished

Author: Daniel Frey <dann.frey@me.com>
Date:   Thu Aug 16 13:31:27 2018 -0700 - final TODO

Author: Vince Masten <vmasten@me.com>
Date:   Thu Aug 16 13:12:22 2018 -0700 - mostly done

Author: Vince Masten <vmasten@me.com>
Date:   Thu Aug 16 11:23:52 2018 -0700 - added category filter

Author: Daniel Frey <dann.frey@me.com>
Date:   Thu Aug 16 11:12:56 2018 -0700 - added hide/show views

Author: Daniel Frey <dann.frey@me.com>
Date:   Thu Aug 16 08:44:41 2018 -0700 - created branch and dir

## Credits and Collaborations
Thank you John, Koko, and Katy. Also a shout out to Jason and Hannah! -->
```
