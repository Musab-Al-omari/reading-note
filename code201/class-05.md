# Chapter 5: “Images”

`<img>`To add an image into the page you need to use an `<img>` element. This is an empty
element (which means there is no closing tag). It must carry the
following two attributes:
1. `src`
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).
2. `alt`
This provides a text description
of the image which describes the
image if you cannot see it.
3. `title`
You can also use the title
attribute with the `<img>` element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a too tip when the
user hovers over the image.

### Summary
IMAGES
1.  The <img> element is used to add images to a
web page.
2. You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the
content of an image.
3.  You should save images at the size you will be using
them on the web page and in the appropriate format.
4. Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs


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


# Chapter 12: “Text”
Typeface Terminology
**Serif** fonts have extra details on the ends of the main strokes of the letters. These details are
known as serifs.
**Sans-serif** fonts have straight ends to letters, and therefore
have a much cleaner design.
**Monospace** Every letter in a monospace (or fixed-width) font is the same width. (Non-monospace fonts
have different widths.)

# Summary

1.  There are properties to control t XX he choice of font, size,
weight, style, and spacing.
2. There is a limited choice of fonts that you can assume
most people will have installed.
3. If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.
4. You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.
5. You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.
