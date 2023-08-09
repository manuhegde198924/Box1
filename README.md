# Box1
hosted link:https://github.com/manuhegde198924/Box1/tree/master
learnt about:

- background-color
- height / width
- color
- text-decoration
- margin/padding
- and
- flex
- The flex CSS shorthand property is the combination of flex-grow, flex-shrink, and flex-basis properties. It is used to set the length of flexible items. The flex property is much more responsive and mobile-friendly. It is easy to position child elements and the main container. The margin doesn’t collapse with the content margins. The order of any element can be easily changed without editing the HTML section.

Syntax:

flex: flex-grow flex-shrink flex-basis|auto|initial|inherit;

Property Values:

    flex-grow Property: A number that specifies, how much items will grow relative to the rest of the flexible items.
    flex-shrink Property: A number that specifies, how much items will shrink relative to the rest of the flexible items.
    flex-basis Property: It sets the length of items. Legal values of flex-basis are: auto, inherit, or a number followed by %, em, px, or any other length unit.
        flex-wrap Property: The CSS flex-wrap property is used to specify whether flex items are forced into a single line or wrapped onto multiple lines.

The flex property can be specified with the help of 1, 2 or 3 values:

    One-value syntax: the value should contain one of following:
        number: If it is represented as flex: <number> 1 0; then the value of flex-shrink, flex-basis will supposed to be 1 & 0 respectively.
        It can be specified by one of the keyword as auto, none or initial.
    Two-value syntax: It must contains the following values:
        The first value should be the number that will represent the flex-grow.
        The second value should contain one of the following:
            number: If it is number then it will represented as flex-shrink.
            a width with the valid value will represents the flex-basis.
    Three-value syntax: The values should be in the same order:
        first number represents the flex-grow.
        second number represents the flex-shrink.
        a width with the valid value will represents the flex-basis.
