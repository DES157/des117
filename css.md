# CSS

cascade and specificity

Comments in CSS begin with `/*` and end with `*/`.

A CSS *declaration* consists of a *property* and *value* pair. Multiple *declarations* may be combined into a *declaration block*. A complete CSS *ruleset* consists of a *declaration block* preceded by a *selector*.

## CSS Selectors

A CSS ruleset consists of selector followed by a declaration block.

CSS Selectors can be grouped using a comma-separated `,` list of selectors.

### Simple Selectors

type (element) selector
:

id selector
:

class selector
:

universal selector
:

Attribute selectors and Pseudo-classes are also considered simple selectors.

#### Attribute Selectors

[att]

[att=val]

[att~=val]

[att|=val]

#### Pseudo-classes

### Pseudo-elements

### Combinators

descendant combinator
: space

child combinator
: >

adjacent sibling combinator
: +

general sibling combinator
: ~

### Semantics

Formally, CSS3 [defines](https://www.w3.org/TR/css3-selectors/#selector-syntax) a *selector* as a chain of one or more sequences of *simple selectors* separated by *combinators*.

## Links

* [Codrops CSS Reference](https://tympanus.net/codrops/css_reference/)
* [Taming Advanced CSS Selectors](https://www.smashingmagazine.com/2009/08/taming-advanced-css-selectors/)

### CSS Specifications

* [CSS Snapshot](https://www.w3.org/TR/CSS/)
* [CSS Syntax Module Level 3](https://www.w3.org/TR/css-syntax-3/)
* [CSS Selectors Level 3](https://www.w3.org/TR/css3-selectors/)

