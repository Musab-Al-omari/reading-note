# chapter 10
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
# chapter 11
## Color
Every color on a computer screen is created by mixing amounts of red,
green, and blue. To find the color you want, you can use a color picker.
### they are 3 ways to pick color in css 
1. RGB Values :- Values for red, green, and blue are expressed as numbers between 0 and 255. `rgb(102,205,170)`

2. Hex Codes:-Hex values represent values for red, green, and blue in hexadecimal code. `#66cdaa`

3. Color Names:- Colors are represented by predefined names. However they are very limited in number.`MediumAquaMarine`
 
 its depend on :-
1. Hue:Hue is near to the colloquial idea of color. Technically speaking however, a color can also have saturation and brightness as
well as hue.
2. Saturation :- Saturation refers to the amount of gray in a color. At maximum saturation, there would be no gray in the color. At minimum saturation, the color would be mostly gray.
3. Brightness:- Brightness (or "value") refers to how much black is in a color. At maximum brightness, there would be no black in the color.At minimum brightness, the color would be very dark.

### HSL Colors
CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.
1. Hue is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the color, although it may also be shown as a slider with values from 0 to 360.
2. Saturation is the amount of gray in a color. Saturation is
represented as a percentage. 100% is full saturation and 0% is a shade of gray.
3. Lightness is the amount ofwhite (lightness) or black
(darkness) in a color. Lightness is represented as a percentage.
0% lightness is black, 100% lightness is white, and 50%
lightness is normal. Lightness is sometimes referred to as luminosity.




 