# Classes Cheatsheet

> when we write [xs | sm | md | lg | xl] it means use any of them.

**Typography**

> xs - Extra small, sm - small, md - medium, lg - large, xl - Extra large.

- `-txt-italic` for italic font variant.

- `-txt-bold` for bold font variant.

- `-txt-[left | center | right]` for align text left, center, right.

- `-txt-[uppercase | capitalize | lowercase]` for uppercase, capitalize or lowercase text.

- `-txt-ht-[xs | sm | md | lg | xl]` for line height to given size.

- `-txt-serif` for serif font.

- `-txt-sans` for sans serif font.

- `-txt-[xs | sm | md | lg | xl]` for text sizes.

**Layout**

> X and Y axis don't change according to flexbox.

- `-px-[xs | sm | md | lg | xl]` for padding on X axis.

- `-py-[xs | sm | md | lg | xl]` for padding on Y axis.

- `-mx-[xs | sm | md | lg | xl]` for margin on X-axis.

- `-my-[xs | sm | md | lg | xl]` for margin on Y axis.

- `-m-auto` for margin auto.

**Color**

> info:  #0275d8, success:  #5cb85c, warning: #f0ad4e, danger: #d9534f, black: #000000, white: #ffffff;

- `-bg-[info | warning | danger | success | black | white]` for specific background color.

- `-bd-[info | warning | danger | success | black | white]` for specific border color.

- `-txt-[info | warning | danger | success | black | white]` for specific text color.

**Others**

- `-h-opacity` give 0.7 opacity on hover.

- `-h-shadow` give small shadow on hover.

- `-shadow` small shadow on element.

- `-round` give some broder radius to element look round.

- `-circle` give 50% broder radius.

- `-bd` for giving border.

- `-no-bd` remove borders from element, like in buttons.

- `-inline` make the element inline block.

- `-block` make the element block level.

- `-fill` for making element width 100 percent.

- `-hide` hide the element.

**Grid System**
> Use it to make a grid system in your website.

- `-flex` for start using flexbox same as `row` of Bootstrap.
- `-in-flex` for inline flex.
- `-jc-center` for making it center on Main axis.
- `-ai-center` for making it center on Cross axis.
- `-center` for making it center from both axis (perfect center).
- `-resp` It wraps the box if width felt short. (responsive)
- `-pin` It pins the item on top of parent even if it is last in HTML code.

**Positioning**
> Position elements to specific place of the page (class -abs is needed for positioning)
- `-abs` first position the element absolute.
- `-rel` position the element relative.
- `-top` float the element to top.
- `-left` float the element to left.
- `-right` float the element to right.
- `-bottom` float the element to bottom.
