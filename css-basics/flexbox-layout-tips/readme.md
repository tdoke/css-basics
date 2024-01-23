1] to have an equal width layout, irrespective of number of flex items.
eg. 3 flex items, total width gets divided among those 3.
    2 flex items, total widht gets divided among those 2.
    for this set flex-basis: 100%, on flex items. that means at max a flex-item can capture 100% of the available width for it.

    https://www.youtube.com/watch?v=qdf9Qa0xJe4


    width: auto; means content will dectate width

It originates from the exception in Flex Layout, that the 
automatic minimum size for flex items defaults to min-content instead of 0 as usual. 
In other words, the default min-width: auto computes to min-content instead of 0.

flex-basis = width of flex-item, before grow/shrink is applied to it. 
