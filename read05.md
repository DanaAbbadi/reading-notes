# Images
Adding Images can improve the design and the appearance of a web page. In HTML, images are defined with the < img> tag. The < img> tag is empty, it contains attributes only, and does not have a closing tag. The src attribute specifies the URL (web address) of the image.

* The alt Attribute:
The alt attribute provides an alternate text for an image, if the user for some reason cannot view it (because of slow connection, an error in the src attribute, or if the user uses a screen reader). The value of the alt attribute should describe the image, If a browser cannot find an image, it will display the value of the alt attribute.

* Image Size - Width and Height
You can use the style attribute to specify the width and height of an image. For example:
                 < img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">

Alternatively, you can use the width and height attributes. Example
< img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">

* Images in Another Folder
If not specified, the browser expects to find the image in the same folder as the web page. However, it is common to store images in a sub-folder. You must then include the folder name in the src attribute.

* Images on Another Server
Some web sites store their images on image servers. Actually, you can access images from any web address in the world

# Colors in CSS :
Color can really bring your pages to life. The color property allows you to specify the color of text inside an element. You can specify any color in CSS in one of three ways:

* RGB values : These express colors in terms of how much red, green and blue are used to make it up. For example: rgb(100,100,90)
* hex codes : These are six-digit codes that represent the amount of red, green and blue in a color, preceded by # sign. For example: #ee3e80
* color names : you can type the color you want.
* HSL : (hue, saturation, lightness) 

# CSS Text

* Text Color
The color property is used to set the color of the text. The color is specified by:
  1. a color name - like "red"
  2. a HEX value - like "#ff0000"
  3. an RGB value - like "rgb(255,0,0)"

* CSS Text Alignment
The text-align property is used to set the horizontal alignment of a text. A text can be left or right aligned, centered, or justified.

* Text Direction
The direction and unicode-bidi properties can be used to change the text direction of an element

* Vertical Alignment
The vertical-align property sets the vertical alignment of an element.

* Text Indentation
The text-indent property is used to specify the indentation of the first line of a text
* Letter Spacing
The letter-spacing property is used to specify the space between the characters in a text.

* Line Height
The line-height property is used to specify the space between lines

* Word Spacing
The word-spacing property is used to specify the space between the words in a text.

* White Space
The white-space property specifies how white-space inside an element is handled.

* Text Shadow
The text-shadow property adds shadow to text, for example:
        h1 {
  text-shadow: 2px 2px red;
}


