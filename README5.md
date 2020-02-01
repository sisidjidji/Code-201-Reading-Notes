# Class 5


## colors :

HTML colors are specified using predefined color names, or RGB, HEX, HSL, RGBA, HSLA values:

### RGB Value:

In HTML, a color can be specified as an RGB value, using this formula:

rgb(red, green, blue)

Each parameter (red, green, and blue) defines the intensity of the color between 0 and 255.

For example, rgb(255, 0, 0) is displayed as red, because red is set to its highest value (255) and the others are set to 0.

To display black, set all color parameters to 0, like this: rgb(0, 0, 0).

To display white, set all color parameters to 255, like this: rgb(255, 255, 255).

### HEX Value:

In HTML, a color can be specified using a hexadecimal value in the form:

#rrggbb

Where rr (red), gg (green) and bb (blue) are hexadecimal values between 00 and ff (same as decimal 0-255).

For example, #ff0000 is displayed as red, because red is set to its highest value (ff) and the others are set to the lowest value (00).

### HSL Value:

In HTML, a color can be specified using hue, saturation, and lightness (HSL) in the form:

hsl(hue, saturation, lightness)

Hue is a degree on the color wheel from 0 to 360. 0 is red, 120 is green, and 240 is blue.

Saturation is a percentage value, 0% means a shade of gray, and 100% is the full color.

Lightness is also a percentage, 0% is black, 50% is neither light or dark, 100% is white



## Images:

### Images syntax:

In HTML, images are defined with the <img> tag.

The <img> tag is empty, it contains attributes only, and does not have a closing tag.

The src attribute specifies the URL (web address) of the image:

< img src="url" >

we can specify its size by using the attributes : Height and width 



### Images Format:

there is 3 rules for creating images :

1. save images in the right format :

- JPEG : you should use it when you have many different colors
- GIF: une Gif Or PNG when saving images with fiew colors or large areas of the same color

2. save images at the right size .

3.  measure images in pixels .

### The alt Attribute:

The alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, 

an error in the src attribute, or if the user uses a screen reader).

The value of the alt attribute should describe the image:

Example:

< img src="img_chania.jpg" alt="Flowers in Chania">


# Texts:

Formatting elements were designed to display special types of text:

* < b> - Bold text
* < strong> - Important text
* < i> - Italic text
* < em> - Emphasized text
* < mark> - Marked text
* < small> - Small text
* < del> - Deleted text
* < ins> - Inserted text
* < sub> - Subscript text
* < sup> - Superscript text
