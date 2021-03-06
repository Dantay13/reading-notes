# What is CSS

CSS (Cascading Style Sheets) is a language for specifying how documents (HTML, SVG OR XML) are presented to users. Mainly how they are styled and laid out.
<br> Some exmple of basic styling that can be done on CSS are, changing the size and color of headings and links. turning a single column of text into a layout. it can be used fo effects such as animation.

## CSS Syntax

CSS is a rule-based language — you define the rules by specifying groups of styles that should be applied to particular elements or groups of elements on your web page.
<br> For example, you can decide to have the main heading on your page to be shown as large red text. The following code shows a very simple CSS rule that would achieve the styling described above:

![CSS syntax image](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/pic2.png)

In the above example, the CSS rule opens with a selector . This selects the HTML element that we are going to style. In this case, we are styling level one headings `(<h1>)`.
<br>We then have a set of curly braces `{ }`.
<br>Inside the braces will be one or more declarations, which take the form of property and value pairs. We specify the property (color in the above example) before the colon, and we specify the value of the property after the colon (red in this example).
<br>This example contains two declarations, one for color and the other for font-size. Each pair specifies a property of the element(s) we are selecting (<h1> in this case), then a value that we'd like to give the property.

![CSS stylesheet](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/pic1.png)

[Source](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

## How to add CSS

### They Are three Ways to add CSS

They are three ways of inserting a style sheet:

- External CSS
- Internal CSS
- Inline CSS

### External CSS

With an external style sheet, you can change the look of an entire website by changing just one file!
<br> Each HTML page must include a reference to the external style sheet file inside the <link> element, inside the head section.

![External CSS Example](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/pic3.png)

An external style sheet can be written in any text editor, and must be saved with a .css extension.
<br>An external style sheet can be written in any text editor, and must be saved with a .css extension.
<br>Here is how the "mystyle.css" file looks:

#### "mystyle.css"

![mystyle.cc Example](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/pic4.png)

### Internal

An internal style sheet may be used if one single HTML page has a unique style.

<br> The internal style is defined inside the "<style>" element, inside the head section.

Example
<br> The internal style is defined inside the "<style>" element, inside the head section.

![Internal CSS Example](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/pic5.png)

### Inline CSS

An inline style may be used to apply a unique style for a single element.
<br> To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

![Inline CSS Example](https://raw.githubusercontent.com/Dantay13/reading-notes/main/pics/pic6.png)

### Multiple Style Sheets

If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.

[Source](https://www.w3schools.com/css/css_howto.asp)

To understanding CSS color property visit the below link
[CSS color property](https://www.w3schools.com/cssref/pr_text_color.asp)

[CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

[Myers Web Reset Stylesheet](https://meyerweb.com/eric/tools/css/reset/)

[<==BACK](README.md)
