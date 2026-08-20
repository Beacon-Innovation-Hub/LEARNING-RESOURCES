# Level 3 --- Interface Engineering

> Build reusable, consistent and maintainable CSS for larger interfaces.

**Stage:** Intermediate\
**Prerequisite:** Level 2

## CSS Custom Properties

``` css
:root {
    --space-sm: 0.5rem;
    --space-md: 1rem;
    --radius: 0.75rem;
    --content-width: 75rem;
}
```

Learn variable declaration, `var()`, scope, fallback values and design
tokens.

## Positioning

Study:

``` text
static
relative
absolute
fixed
sticky
```

Also learn `z-index`, stacking contexts, containing blocks and overflow.

## Pseudo-classes & Pseudo-elements

``` css
:hover
:focus
:focus-visible
:checked
:disabled
:nth-child()

::before
::after
::placeholder
```

## Forms

Build and style text inputs, selects, checkboxes, radio buttons,
textareas and buttons.

Support:

``` text
Default
Hover
Focus
Disabled
Error
Success
```

## CSS Organization

Explore:

``` text
Base
Layout
Components
Utilities
Pages
```

Understand component naming approaches such as BEM:

``` css
.card {}
.card__title {}
.card__content {}
.card--featured {}
```

## BIH Scenario --- Shared Interface System

Different BIH developers have created inconsistent cards, buttons,
headings, forms and spacing. Build a shared CSS system.

``` text
styles/
├── reset.css
├── variables.css
├── base.css
├── layout.css
├── components.css
└── utilities.css
```

Create reusable buttons, cards, alerts, badges, navigation and form
fields.

## Level 3 Challenge --- BIH Registration Interface

Create a responsive participant-registration interface with programme
information, personal details, pathway selection, consent, validation
states and confirmation panel.

## Assessment

  Area                   Weight
  -------------------- --------
  Reusable CSS              20%
  Forms and states          20%
  Custom properties         15%
  CSS organization          15%
  Accessibility             15%
  Responsive quality        15%

**Progression requirement: 70%**

[Continue to Level 4 →](CSS-Level-4-Advanced-Professional-CSS.md)
