# CSS Properties and Values

This document provides a comprehensive list of all CSS properties and their possible values. Use it as a reference for styling your web applications.

---

## Table of Contents

1. [Box Model](#box-model)
2. [Flexbox](#flexbox)
3. [Grid](#grid)
4. [Positioning](#positioning)
5. [Typography](#typography)
6. [Color and Background](#color-and-background)
7. [Borders and Outlines](#borders-and-outlines)
8. [Animations and Transitions](#animations-and-transitions)
9. [Filters and Effects](#filters-and-effects)
10. [Other Properties](#other-properties)

---

## Box Model

- **`width`**: `auto | <length> | <percentage>`
- **`height`**: `auto | <length> | <percentage>`
- **`margin`**: `auto | <length> | <percentage>`
- **`padding`**: `<length> | <percentage>`
- **`border`**: `<border-width> <border-style> <color>`
- **`box-sizing`**: `content-box | border-box`

---

## Flexbox

- **`display`**: `flex | inline-flex`
- **`flex-direction`**: `row | row-reverse | column | column-reverse`
- **`justify-content`**: `flex-start | flex-end | center | space-between | space-around | space-evenly`
- **`align-items`**: `flex-start | flex-end | center | stretch | baseline`
- **`align-self`**: `auto | flex-start | flex-end | center | stretch | baseline`
- **`flex-wrap`**: `nowrap | wrap | wrap-reverse`
- **`flex`**: `none | <flex-grow> <flex-shrink> <flex-basis>`

---

## Grid

- **`display`**: `grid | inline-grid`
- **`grid-template-columns`**: `none | <track-list>`
- **`grid-template-rows`**: `none | <track-list>`
- **`grid-gap`**: `<length>`
- **`align-items`**: `start | end | center | stretch`
- **`justify-items`**: `start | end | center | stretch`

---

## Positioning

- **`position`**: `static | relative | absolute | fixed | sticky`
- **`top`**: `<length> | <percentage> | auto`
- **`right`**: `<length> | <percentage> | auto`
- **`bottom`**: `<length> | <percentage> | auto`
- **`left`**: `<length> | <percentage> | auto`
- **`z-index`**: `<integer> | auto`

---

## Typography

- **`font-family`**: `<family-name> | <generic-family>`
- **`font-size`**: `<absolute-size> | <relative-size> | <length> | <percentage>`
- **`font-weight`**: `normal | bold | bolder | lighter | <number>`
- **`font-style`**: `normal | italic | oblique`
- **`line-height`**: `normal | <number> | <length> | <percentage>`
- **`text-align`**: `left | right | center | justify | start | end`
- **`text-transform`**: `none | capitalize | uppercase | lowercase`
- **`letter-spacing`**: `normal | <length>`

---

## Color and Background

- **`color`**: `<color>`
- **`background-color`**: `<color>`
- **`background-image`**: `none | <url>`
- **`background-size`**: `auto | cover | contain | <length> | <percentage>`
- **`background-position`**: `<position>`
- **`background-repeat`**: `repeat | no-repeat | repeat-x | repeat-y | space | round`

---

## Borders and Outlines

- **`border-width`**: `thin | medium | thick | <length>`
- **`border-style`**: `none | solid | dotted | dashed | double | groove | ridge | inset | outset`
- **`border-color`**: `<color>`
- **`outline`**: `<outline-width> <outline-style> <outline-color>`

---

## Animations and Transitions

- **`animation`**: `<name> <duration> <timing-function> <delay> <iteration-count> <direction>`
- **`animation-name`**: `none | <custom-name>`
- **`animation-duration`**: `<time>`
- **`transition`**: `<property> <duration> <timing-function> <delay>`
- **`transition-delay`**: `<time>`

---

## Filters and Effects

- **`filter`**: `none | blur() | brightness() | contrast() | grayscale() | hue-rotate() | invert() | opacity() | saturate() | sepia()`
- **`box-shadow`**: `none | <shadow>`
- **`text-shadow`**: `none | <shadow>`

---

## Other Properties

- **`cursor`**: `auto | default | pointer | wait | text | move | not-allowed | crosshair | url()`
- **`overflow`**: `visible | hidden | scroll | auto`
- **`visibility`**: `visible | hidden | collapse`
- **`clip-path`**: `none | <path>`

---

For more details, refer to the [CSS specification](https://www.w3.org/Style/CSS/).

