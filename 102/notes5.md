# Notes on CSS

## Day 3 Class 1 notes

# Chapter 10 Notes

#### The key to doing well with CSS is to imagine an invisible box around every element on a page. You can edit and change the appearance of these boxes to create design.

Example of a CSS edit:
`p {
    font-family: Arial;}`
`p` is the selector in this case, which tells CSS what element of the HTML document it is changing the style of.
`{font-family: Ariel;}` is the declaration, or the actual change being made.

`* {}` The asterisk is the universal selector which applies to all elements in a document.

`h1, h2, h3 {}` The type selector matches specific element names.

`.note {}` or `p.note {}` The class selector matches elements whose class attributes have been identified.

`#introduction` The ID selector targets elements with the matching id 'introduction'.

There are many more, however these are the most common ones that will end up being used most likely.

If two selectors are identical, the latter will take precedence. 

The more specific identifier will take precedence, for example:
* `h1` is more specific than `*`
* `p b` is more specific than `p`
* `p#intro` is more specific than `p`

# Chapter 11 notes

#### Things you can change with CSS include:
* Color
    1. RGB values can be used
    1. HEX codes (6 digit codes EX: #ee3e80;)
    1. Color names (EX: DarkCyan)
* Background-color
    * Same rules apply as `Color`
* Opacity
    * EX: opacity: 0.5;
* hsl
    * Hue, Saturation, and Lightness (EX: background-color: hsl(0,0%,78%);)
* hsla
    * Hue, Saturation, Lightness, and Alpha (Alpha refers to transparency)

#### Color brings life to your website as well as the mood and reaction you want people to get from your site.

You can use an external color picker to find the color you want.



[<-- Back](README.md)