flexbox
1] flex applies to only direct children of the flex container
2] flex container ==> the parent
3] flex items ==> the children
4] default size of div's is 100%, but in case of flex items by default they shrink down to their smallest possible size that can be. 
4.1] A flex item by default occupies the smallest possible width inside a flex container
5] if there are multiple flex items in a row and one of them has shorter content. then to make sure all of 
them have equal width, make width: 100% for all the flex items
<div flex-container direction-row>
<div flex-column width-100>small contet</div>
<div flex-column width-100>lfdfafdsfsdfdsfsdfdsfdsfasfdsffasdfdsfdsfdsfsfsfsdfsdf</div>
<div flex-column width-100>fsfsafdsafdfadfdfdsfdsfdsffadsfdsfdfdfdafdfdfdadfdfdsfasf</div>
</div> 
7] always have img width: 100% for all images in website.
   when an image is shown inside a flex item. if img size < item size, img will be stretched to fill in item content.To avoid this use align-self: start, in an item containing image.
8] flex container basics: https://flexbox.help/
9] flex items props
grow, shrink, basis, order
10] by default a flex item height gets stretched to cover full height of its flex container.
because on flex container, by default align-items is 'stretched'.
11] a flex item using 'align-self' can override 'align-items' set from the flex container.
12] a flex item using 'order' can order itself in items display.
13] 'flex-basis' = its like max-width for flex-items, flex item will not grow beyond this