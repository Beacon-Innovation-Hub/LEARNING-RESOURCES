# Level 2 --- Layouts & Responsive Design

> Build modern interfaces that adapt correctly across phones, tablets
> and desktops.

**Stage:** Foundational → Intermediate\
**Prerequisite:** Level 1

## Flexbox

Study:

-   [ ] `display: flex`
-   [ ] Main and cross axes
-   [ ] `flex-direction`
-   [ ] `justify-content`
-   [ ] `align-items`
-   [ ] `gap`
-   [ ] `flex-wrap`
-   [ ] `flex-grow`
-   [ ] `flex-shrink`
-   [ ] `flex-basis`

**[🎮 Flexbox Froggy](https://flexboxfroggy.com/)**

## CSS Grid

Study:

-   [ ] `display: grid`
-   [ ] Grid tracks
-   [ ] `grid-template-columns`
-   [ ] `grid-template-rows`
-   [ ] `gap`
-   [ ] Grid placement
-   [ ] `repeat()`
-   [ ] `minmax()`
-   [ ] `fr`
-   [ ] `auto-fit`
-   [ ] `auto-fill`

**[🎮 Grid Garden](https://cssgridgarden.com/)**

## Responsive Web Design

Learn:

-   [ ] Mobile-first design
-   [ ] Media queries
-   [ ] Content-driven breakpoints
-   [ ] `%`, `rem`, `em`, `vw`, `vh`
-   [ ] `min()`, `max()`, `clamp()`
-   [ ] Responsive images
-   [ ] Flexible containers

``` css
.container {
    width: min(90%, 1200px);
    margin-inline: auto;
}

.title {
    font-size: clamp(2rem, 5vw, 4rem);
}
```

## Real-World Project Resource

**[▶ Real-World CSS Projects
Playlist](https://www.youtube.com/playlist?list=PLRjB3Wml-DM_VWMDomFed97f74dpCO7GE)**

Do not simply code along. Attempt each layout before watching the
implementation.

## BIH Lab --- Responsive Homepage

Build:

``` text
Header
Navigation
Hero
Programmes
Featured Projects
Latest Updates
Call to Action
Footer
```

Test around 320px, 375px, 768px, 1024px and 1440px while ensuring the
layout also works between those widths.

## Browser Developer Tools

Practice inspecting Flexbox/Grid, computed styles, Box Model, responsive
modes, overflow and overridden declarations.

## Level 2 Challenge

Build a responsive **BIH Technical Programme Page** using both Flexbox
and Grid. The same HTML must remain usable from small mobile screens to
large desktops.

## Assessment

 | Area                   | Weight   |
|------------------------|----------|
| Flexbox                | 20%      |
| Grid                   | 20%      |
| Responsive design      | 25%      |
| Units and typography   | 10%      |
| Layout quality         | 15%      |
| Debugging/code quality | 10%      |
| **Total**              | **100%** |

**Progression requirement: 70%**

[Continue to Level 3 →](CSS-Level-3-Interface-Engineering.md)
