## Introduction
### Motivation
Elypia wanted to create a simple, abstract, and unique text based 
logo that could be used by third-parties to reference us, while 
providing something users could read and search on their own. 
To achieve this we wanted to create a font that looked good, 
but was easily distinguishable from what other brands use.

The specification and guidelines have been optimized to accommodate the glyphs
in the brand name, "Elypia", and then applied to all other glyphs.

This font is completely free open-source so anyone can use it for any
purpose, including for their own logo, titles or subheadings, or even
content for a document or website... though we definitely _wouldn't_ recommend the latter!

#### Elypia Logo with Text
![elypia_logo_text]

### Inception
This font imagines that all glyphs are made from strips of paper
which may be folded like origami to create shapes forming abstract glyphs.
The glyphs didn't have to look perfect, but complete the character enough 
that any reasonable person would be able to read a large title or heading.

### Grid
The font is based on a grid backing it which is 12 grid-cells high. There
is no minimum or maximum width any character has to be. 
The bottom 3 cells are below the writing line, for characters like `y`, or `p`, while the 9 cells above are starting at the writing line working up.

All cells in the grid must be squares with a height equal to width; these squares
will only ever be filled completely, or half-filled from opposite corners. 

**The specifications will use grid-cells to refer to sizes.**

![grid]

## Specification
### Shape
* Each strip must be a square of one grid cell or rectangle that is one cell wide.
* All slants must be at a 45 degree angle.
* Strips may start with a slant by cutting one or both sides.
* Only the shorter side may be slanted.

![shapes]
> Their shouldn't be any curves, points in between two grid cells, or slants that are anything other than 45 degrees.

### Folds
* All folds that occur must result in the folded side being slanted.

![folds]
> When folding a strip, the folded angle will always result in a slant regardless of what may appear behind the letter after the fold. Behind the fold, it can be straight or slanted because we allow strips to begin with a slant on one or both sides as well. 

### Spacing
* Parallel slants should not be within one grid cell of each other.
* All apertures must be 2 grid cells wide.
* All characters are a fixed 2 grid cells away from each other.

![parallel_slants]
> The font needs to look good when flattened to a single color, unfortunately
> when this rule is not followed the E looks malformed and out of place
> so there must be at least one grid-cell of space between parallel slants.

![apertures]
> There is no requirement of the height of apertures, however, the width of all aperatures must be consistently 2 grid-cells wide.

### Connecting Strips
* If a slant occurs between two strips that represent the same character,
the angle should face upwards or downwards _towards_ the corresponding strip. 

![connect]

[elypia_logo_text]: ./assets/elypia_logo_text.png "Elypia Logo with Text"
[grid]: ./assets/grid.png "Elypia Logo Grid"
[shapes]: ./assets/shapes.png "Good and Bad Examples of Shapes"
[folds]: ./assets/folds.png "Good and Bad Examples of Folds"
[parallel_slants]: ./assets/parallel_slants.png "Good and Bad Examples of Slants"
[apertures]: ./assets/apertures.png "Good and Bad Examples of Apertures"
[connect]: ./assets/connecting_strips.png "Good and Bad Examples of Connecting Strips"