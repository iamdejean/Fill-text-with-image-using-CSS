Adding text on images can make your website look amazing. It is great for gaining the attention of readers. This is a popular technique and a classic effect in Adobe Photoshop/Illustrator, thanks to the power of clipping masks. It clips the image to the text, meaning that only the area of the image that sits directly above the actual text remains visible, creating the illusion that the image is inside the text. The rest of the image is now hidden from view which create a solid  Fill layer. This same effect can be make using CSS. And here's how I created it.
First, I created an index.html file, markup have a h1 tag with an ID "title".
 Secondly, I created a style.css file which I linked it to my index.html.  The CSS has tags, classes and id's from my index.html giving them some basic properties. 
 Since the ID "#title" is where my h1 is, I add a background-clip properties to it.
The background-clip CSS property sets whether an element's background extends underneath its border box, padding box, or content box.

background-clip: text;

-webkit-background-clip: text;

-webkit-text-fill-color: transparent;

If the element has no background-image or background-color, this property will only have a visual effect when the border has transparent regions or partially opaque regions (due to border-style or border-image).
