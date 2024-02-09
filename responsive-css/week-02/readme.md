flexbox
1] flex applies to only direct children of the flex container
2] flex container ==> the parent
3] flex items ==> the children
4] default size of div's is 100%, but in case of flex items by default they shrink down to their smallest possible size that can be. 
i.e flex-items width is smallest possible width occupied by its content.
4.1] A flex item by default occupies the smallest possible width inside a flex container
5] if there are multiple flex items in a row and one of them has shorter content. then to make sure all of 
them have equal width, make width: 100% for all the flex items
<div flex-container direction-row>
<div flex-column width-100>small contet</div>
<div flex-column width-100>lfdfafdsfsdfdsfsdfdsfdsfasfdsffasdfdsfdsfdsfsfsfsdfsdf</div>
<div flex-column width-100>fsfsafdsafdfadfdfdsfdsfdsffadsfdsfdfdfdafdfdfdadfdfdsfasf</div>
</div> 
7] always have img max-width: 100% for all images in website.
   when an image is shown inside a flex item. if img size < item size, img will be stretched to fill in item content.To avoid this use 
   max-width: 100%  for image.
8] flex container basics: https://flexbox.help/
9] flex items props
grow, shrink, basis, order
10] by default a flex item height gets stretched to cover full height of its flex container.
because on flex container, by default align-items is 'stretched'.
11] a flex item using 'align-self' can override 'align-items' set from the flex container.
12] a flex item using 'order' can order itself in items display.
13]     width: auto; means content will dectate width

It originates from the exception in Flex Layout, that the 
automatic minimum size for flex items defaults to min-content instead of 0 as usual. 
In other words, the default min-width: auto computes to min-content instead of 0.
14]
flex-basis = width of flex-item, before grow/shrink is applied to it. 

default
flex: [grow] [shrink] [flex-basis]
flex: 0 1 auto;

use flex-basis, if you are going to play with grow and shrink.
15] flex-basis:

