## HTML Chapter 2: “Text” 
### Headings
* we use the heading tag for the importance the text 
* it divided for six tags based on the importance of the text `<h1><h2><h3><h4><h5><h6>`
* when the number increse the importance of the text will be less
### Paragraphs 

To create a paragraph, surround the words that make up the paragraph with an opening `<p>`    tag and closing `</p>` tag.

### Bold & Italic
By enclosing words in the tags `<b>` and `</b>` we can make characters appear bold.

By enclosing words in the tags `<i>` and `</i>` we can make characters appear italic.

### Superscript & Subscript
The `<sup>` element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such as 22.

The `<sub> `element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical formulas such as H20.
## summary
* HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
* They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).




## HTML Chapter 10:Introducing CSS
## CSS Associates Style rules with HTML elements
These rules control how the content of specified elements should be displayed.
 A CSS rule contains two parts: a **selector** and a **declaration**:-
 this rule `p { font-family: Arial; }` indicates that all `<p>`elements should be shown in the Arial typeface. 
**selector**in this case its `<p>` and its  indicat  which element the rule applies to.
**declaration**`font-family: Arial;`indicate how the elements referred to in the selector should be styled.
## CSS Properties Affect How Elements Are Displayed
CSS declarations sit inside curly brackets and each is made up of two parts:
* property:-indicate the aspects of the element you want to change.
* value:- specify the settings you want to use for the chosen properties
`h1, h2, h3 { font-family: Arial;color: yellow;}`

font-family and color; represent property
 Arial and yellow ; represent the value 
### Summary
* CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.
* Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).

* Different types of selectors allow you to target your rules at different elements.
* Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. 
* CSS rules usually appear in a separate document, although they may appear within an HTML page.


