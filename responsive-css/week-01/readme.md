1] default width of any block level element is 100% of parent width.
2] HTML elements are responsive by default. the problem starts when we start defining fixed sized widths, heights to them.
3] if u add a fixed width(900px) to parent and reduce the screen width below 900px, you will start seeing the horizontal scrolls.
4] width defined in % works fine for responsiveness. dont use fixed sized widths.
5] instead of using height, use padding with rem or em units. most of the times height creates problems.
6] max-width limits the div from expanding on bigger screens. max-width to be used with media queries with fixed value px
7] only one outermost parent container div (having text) should have max-width. not all of them in dom tree.
