# Intro

Every element in CSS has a box around it wether you see it or not.
Understanding these boxes is key to create layouts or to align items with other items.


# Content - Padding - Margin - Border

Making up a block box in CSS we have the:

  - Content box: The area where your content is displayed, which can be sized using properties like width and height.
  - Padding box: The padding sits around the content as white space; its size can be controlled using padding and related properties.
  - Border box: The border box wraps the content and any padding. Its size and style can be controlled using border and related properties.
  - Margin box: The margin is the outermost layer, wrapping the content, padding and border as whitespace between this box and other elements. Its size can be controlled using margin and related properties.


# Margin collapsing 

  - Elements' top and bottom margins are sometimes collapsed into a single margin that is equal to the larger of the two margins. 
  - Collapsing doesn't apply to floated elements


# Block & inline boxes

 - if a box is defined as block :
    * box will break into new line
    * box will extend in the inline direction to fill the space available in its container. In most cases this means that the box will become as wide as its container
    * you can set the height and the width
    * Padding, margin and border will cause other elements to be pushed away from the box

 - if a box is defined as inline : 
    * The box will not break onto a new line.
    * The width and height properties will not apply.
    * Vertical padding, margins, and borders will apply but will not cause other inline boxes to move away from the box.
  
 - if a box is defined as inline :
    * The box will still not break onto a new line.
    * The width and height properties will apply.
    * Padding, margin and border will cause other elements to be pushed away from the box.