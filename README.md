# Flex Panels

Flex Panels is a image gallery website built with Vanilla JavaScript.

## Table of contents

- [Overview](#overview)
  - [Screenshots](#screenshots)
  - [Demo Link](#demo-link)
- [About the Project](#about-the-project)
  - [Status](#status)
  - [Built with](#built-with)
  - [Reflection](#reflection)
- [Author](#author)

## Overview

### Screenshots

![Flex Panels](./flex-panels.png)

### Demo Link

**[💻 Live Site URL](https://soojeong-park-ca.github.io/flex-panels-gallery/)**

## About the Project

### Status

✅ Completed & Deployed

### Built with

- HTML
- CSS
- Vanilla JS

### Reflection

This was another Vanilla JS project from JavaScript 30 course by Wes Bos.

Some features to highlight in this project are:

- using `flexbox` and nested flexbox to position panels and its child elements.

- using the `flex-grow` CSS property to adjust the ratio of the sizes of the panels.

- toggling the `.open` and `.open-active` classes from the panel elements to give animation-like effect with the `transform` properties.

  ```css
  .panel > *:first-child {
    transform: translateY(-100%);
  }
  .panel.open-active > *:first-child {
    transform: translateY(0);
  }

  .panel > *:last-child {
    transform: translateY(100%);
  }
  .panel.open-active > *:last-child {
    transform: translateY(0);
  }
  ```

Some new CSS tricks that I learned from this project are:

- understanding `flex-grow`, `flex-shrink`, and `flex-basis`:
  - `flex-basis`: base size
  - `flex-grow`: how to share extra space
  - `flex-shrink`: how much to shrink when there isn't enough space

## Author

Soojeong Park [@codingsooj](https://twitter.com/codingsooj)
