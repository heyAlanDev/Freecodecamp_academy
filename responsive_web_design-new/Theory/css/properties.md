# Selectors
```css
/* code */ : use to comment
* {} : to all html
element {} : to select all element with this tag
element1, element2, elementn {} : to select all element with this tags
dadElement sonElement {} : to select sonElement that nest in dadElement
.classSelector {} : to select element this class attribute
element:pseudo-class {} : to select the pseudo class of a element 
[attr] {} : Represents elements with an attribute name of attr.
[attr=value] {} : Represents elements with an attribute name of attr whose value is exactly value.
[attr~=value] {} : Represents elements with an attribute name of attr whose value is a whitespace-separated list of words, one of which is exactly value.
[attr|=value] {} : Represents elements with an attribute name of attr whose value can be exactly value or can begin with value immediately followed by a hyphen, - (U+002D). It is often used for language subcode matches.
[attr^=value] {} : Represents elements with an attribute name of attr whose value is prefixed (preceded) by value.
[attr$=value] {} : Represents elements with an attribute name of attr whose value is suffixed (followed) by value.
[attr*=value] {} : Represents elements with an attribute name of attr whose value contains at least one occurrence of value within the string.
[attr operator value i] {} : Adding an i (or I) before the closing bracket causes the value to be compared case-insensitively (for characters within the ASCII range).
[attr operator value s] {} : Adding an s (or S) before the closing bracket causes the value to be compared case-sensitively (for characters within the ASCII range).  /*(Experimental)*/
```
# Properties for style
```css
{
    color : to change the text color;
    font-family : to change the element font;
    font-size : to change the element font size;
    font-weight : to change the element font weight;
    font-style : to change the element font style;
    font-variant : to change the element font variant;
    font-stretch : to change the element font stretch;
    letter-spacing : to change the element letter spacing;
    text-align: to align the text;
    background-color : to paint the element background;
    background-image : to add a img element background;
    border : lets you to set the border width, style, and color at the same time;
    border-left : lets you to set the left border width, style, and color at the same time;
    border-right : lets you to set the right border width, style, and color at the same time;
    border-bottom : lets you to set the bottom border width, style, and color at the same time;
    border-top : lets you to set the top border width, style, and color at the same time;
    border-color : to change the element border color;
    border-style : to change the element border style;
    border-width : to change the element border width;
    border-left-width : to change the left border width of a element;
    border-left-style : to change the left border style of a element;
    border-left-color: to change the left border color of a element;
    border-right-width : to change the right border width of a element;
    border-right-style : to change the right border style of a element;
    border-right-color: to change the right border color of a element;
    border-bottom-width : to change the bottom border width of a element;
    border-bottom-style : to change the bottom border style of a element;
    border-bottom-color: to change the bottom border color of a element;
    border-top-width : to change the top border width of a element;
    border-top-style : to change the top border style of a element;
    box-sizing : defines the sizing behavior of an element;
    display : defines the display type of an element;
    border-top-color: to change the top border color of a element;
    box-shadow : to add a shadow to a element;
    border-radius : to add a border radius to a element;
    height : to change the element height;
    width : to change the element width;
    max-height : defines the maximum height of an element;
    min-height : defines the minimum height of an element;
    max-width : defines the maximum width of an element;
    min-width : defines the minimum width of an element;
    margin : to change the element margin (If have one value changes all element margin, if have two values the first is for top and bottom margin and the second value change the right and left margin if have three values the first change the top, the second change the left and right paddings, and the last change the bottom and if have four values the change will be clockwise);
    padding : to change the element padding (If have one value changes all element padding, if have two values the first is for top and bottom padding and the second value change the right and left padding if have three values the first change the top, the second change the left and right paddings, and the last change the bottom and if have four values the change will be clockwise);
    margin-left : to change the element margin left;
    margin-right : to change the element margin right;
    margin-top : to change the element margin top;
    margin-bottom : to change the element margin bottom;
    padding-left : to change the element padding left;
    padding-right : to change the element padding right;
    padding-top : to change the element padding top;
    padding-bottom : to change the element padding bottom;
    opacity : you can control how opaque or transparent an element is. With the value 0, or 0%, the element will be completely transparent, and at 1.0, or 100%, the element will be completely opaque like it is by default.;
    filter : defines visual effects (like blur and saturation) to an element;
    transform : defines a transformation to an element;
    clear : defines the clear property of an element;
    overflow : defines the overflow property of an element;
    float : defines the float property of an element;
}
```
## Flexbox
```css
{
display: flex; : to use flexbox;
flex-direction : to define the direction of the flexbox;
flex-wrap : to define the wrapping behavior of the flexbox;
justify-content : to define the alignment of the flexbox items on the main axis;
align-items : to define the alignment of the flexbox items on the cross axis;
object-fit : to define how the content of a replaced element is fitted to the box;
}
```
