# 05: Designing Web Pages with CSS

Cascading Style Sheets

Language that can make things look nice. add color, format some columns, position your containers, change sizes, establish margins, add little borders, change image shapes, border shapes, etc etc.

## CSS SYNTAX

- Define rules specifying groups of styles that should be applied to particular elements or groups of elements on your web page.

There are certain declarations in the form of property and value pairs. Each pair specifies a property of the element you're selecting, then a value to give it.

- name the element from the html.
- open curly bracket
- list whatever property you're addressing (what are you targeting).
- list corresponding value (what do you want it to do)
- semi-colon
- close your bracket on the next line
- refresh
- voila beauty

for example...

header {
    border: 40px solid limegreen;
    padding: 20 px;
    margin: 15 px;
    background-color: denim;
}

h1 {
    color: hotpink;
}

and so on.............

## 3 Ways to Insert CSS

- EXTERNAL

    -With an external style sheet, you can change the look of an entire website by changing just one file!
    -Each HTML page must include a reference to the external style sheet file inside the < link > element, inside the head section.

- INTERNAL

    -An internal style sheet may be used if one single HTML page has a unique style.
    -The internal style is defined inside the < style > element, inside the head section.

- INLILNE

    -An inline style may be used to apply a unique style for a single element.To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.
