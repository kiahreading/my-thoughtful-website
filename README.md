# My Thoughtful Website
Welcome to the workshop. Settle in, pour some tea. Let's hand write a website.

## Example HTML Elements

Headings.\
H1 is the largest all the way through to the smallest, H6.
```
<h1>Main heading or title of the page</h1>
.
.
<h2>Secondary heading</h2>
.
.
<h3>Third level heading</h3>
...
....
```
\
Paragraph. \
*Use this for each paragraph of text.*
```
<p>To aid with navigation and sensation, cats have dozens of movable whiskers (vibrissae) over their body, especially their faces. These provide information on the width of gaps and on the location of objects in the dark, both by touching objects directly and by sensing air currents; they also trigger protective blink reflexes to protect the eyes from damage.</p>
```
\
Line break. \
*If you have a poem you would like to include for example, breaks may be useful.*
```
<p> 
O’er all the hilltops<br>
Is quiet now,<br>
In all the treetops<br>
Hearest thou<br>
Hardly a breath;<br>
The birds are asleep in the trees:<br>
Wait, soon like these<br>
Thou too shalt rest.
</p>
```
\
Image.
```
<img src="leopard.jpg" alt="An intimidating leopard.">
```
\
Anchor (link). \
*Create links to other pages of your website, PDFs or other websites.*
```
<a href="second-page.html">Click here to earn more about sunflowers</a>
```
\
Horizontal line.
```
<hr>
```
\
Unordered list (list of items with 'dot-points').
```
<ul>
  <li>Red cars</li>
  <li>Blue cars</li>
  <li>Yellow cars</li>
  <li>Pink cars</li>
</ul>
```
\
Ordered list (list of numbered items).
```
<ol>
  <li>Cats</li>
  <li>Dogs</li>
  <li>Rabbits</li>
  <li>Fish</li>
</ol>
```
\
Audio player.
```
<audio
  controls
  src="t-rex-roar.mp3">
</audio>
```
\
Video player.
```
<video controls>
  <source src="flower.mp4"
          type="video/mp4">
</video>
```
\
Drop down accordion.
```
<details>
  <summary>Details</summary>
  Something small enough to escape casual notice.
</details>
```
\
Divider. \
*Note: this element will not directly change its contents, however can be useful when we want to begin changing how things look.*
```
<div>
  <img src="emu.jpg" alt="Emu running across red desert sand.">
  <p>Would you rather the ability to run fast or fly?</p?
</div>
```

## Example CSS Properties
Background colour. \
*There are many different ways to declare a colour, here are two.*
```
/* You can use one of the 140+ color names.*/
body {
  background-color: red;
}

/* You can use hexadecimal color codes.*/
body {
  background-color: #05ffb0;
}
```
\
Text colour.
```
p {
  color: darkmagenta;
}
```
\
Font type. \
*You can have 1 or more fonts on the same page.*
```
body {
  font-family: sans-serif;
}
p {
  font-family: fantasy;
}
```
\
Font size.
```
p {
  font-size: 72px;
}
```
\
Font style.
```
h1 {
  font-style: italic;
}
```
\
Border.
```
div {
  border: 4px dotted red;
}

/* You may have guessed that you can change the border-width, border-style & border-color eg:*/
div {
  border: 2px dashed black;
}

/* Other border-styles include: solid, double & groove*/

```
\
Width.
```
body {
  width: 50%;
}

/* or.. */

body {
  max-width: 500px;
}

/* Center content with.. */

body {
  max-width: 500px;
  margin: 0 auto;
}
```
\
Transform an element.
*This can include rotating, skewing etc. More info about this [here](https://cssreference.io/property/transform/)*
```
img {
  transform: rotate(45deg);
}
```
\
__NOTE__ \
*You can add multiple selectors to the same element.*
```
h1 {
  color: red;
  font-family: cursive;
  font-style: italic;
}
```


## References

### HTML
* [MDN list of HTML empty elements](https://developer.mozilla.org/en-US/docs/Glossary/Empty_element)
* [MDN list of HTML elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

### CSS
* [Dev Docs CSS Index](https://devdocs.io/css/)
* [CSS Reference](https://cssreference.io/)
* [Web colours](https://developer.mozilla.org/en-US/docs/Web/CSS/color_value)
* [Text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals)
* [Reset CSS](https://meyerweb.com/eric/tools/css/reset/)

### Hosting
* [GitHub Pages]()

## Downloads
* [Workshop files](url)
* [Text editor (for MAC)](url)
* [Text editor (for PC)](url)

## Uploads
To upload your website at the end of the class [click here](https://app.ezfiledrop.com/535797/outer-space-file-upload). *Please make sure to compress the files (this will produce a .zip file which is exactly what we want).*

## Examples
<details>
	<summary>List of examples active as of 4th June 2021</summary>
	<ul>
	<li>https://sites.artistsspace.org/tiffany-sia-slippery-when-wet/</li>
     	<li>https://alt-text-as-poetry.net/</li>
     	<li>https://headgear.pw/</li>
     	<li>https://madelinesnotes.cloud/</li>
     	<li>https://nyanseong.neocities.org/</li>
     	<li>https://screenshot.garden/</li>
     	<li>https://emptyday.today/</li>
     	<li>https://mayaontheinter.net/</li>
     	<li>http://html.energy/</li>
     	<li>http://ticks.bisagra.org/2/index.html</li>
	<ul>
</details>
