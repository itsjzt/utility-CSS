# Getting Started
## Easily integrate Utitility CSS in your project.

### Some philosphy behind this library
We made Utility CSS for making styles that can be composed eaasily to design components.

If you want to know more about utility CSS read [On Utility CSS](http://davidtheclark.com/on-utility-classes/)

We try to make CSS more re-usable by challenging the conventional way to Sepration of Concerns (SoC).

In our library we style the components with small CSS selectors that compose together and form great looking authentic design.

### how to get started
- Add this `<link type="stylesheet" href="https://gitcdn.xyz/repo/itsjzt/utility-CSS/master/build/utility.css">` to your html file
- now you cna style your components easily with Utility CSS.

### Some Common classes
- This library is really short and we don't even have specific tag for `buttons` but you can easily compose them with paddings, margin, colors and typography classes we provide.

- All class names start with `-` so that it don't clash with other library out there.

  ex: `-shadow`, `-txt-sans`

- We have `xs | sm | md | lg | xl` sizes for padding, margin and font size.

  ex: `-txt-sm`, `-px-lg`

- we have `info | danger | warning | success | black | white` color for background and text. (colors are inspired by [Bootstrap](https://getbootstrap.com)).

  ex: `-bg-info`, `-txt-white`

- 2 special classes for hover also exists.

  ex: `-h-opacity`, `-h-shadow`

- for all Classes view [Classes cheatsheet](classes-cheatsheet.md)
