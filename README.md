## Colors

In UnkertCSS the following colors can be used:

* blue
* green
* red
* pink
* purple
* yellow
* cyan
* white
* black
* orange

There are 8 variants for each color in both background colors and text colors. The base variant for each color has no number with the class. For example a base white color's class is:

.white (for background)
.white-text (for text color)

The other 7 variants contain numbers:

.white-1 through white.7 (for the 7 other background colors)

.white-1-text through .white-7-text (for the 7 other text colors)

This naming convention holds true for each of the other colors. For instance let's say you had a div with a black-3 background and a cyan-4 text in a paragraph. The code would be:

<code>
  &lt;div class="black-3"&gt;
    &lt;p class="cyan-4-text"&gt;This is a sentence with cyan-4 text color.&lt;/p&gt;
  &lt;/div&gt;
</code>

## font-weights and styles

font weights can be accessed in 300, 400, 500, 600, 700, and 800 with regular or italic text.

To access a font-weight of 300 you would type the following class:

fw-300

If you wanted italic you would have the class:

fw-300-italic

Example code using font-weights and styling is:

<code>
  &lt;p class="fw-500-italic"&gt;This is 500 weight font that is italicized.&lt;/p&gt;
</code>

## Containers

container classes are available with a max-width, centered via margin: 0 auto; from 200px to 1200px.

If you wanted to have a 900px container the code would be:

<code>
  &lt;div class="container-900"&gt;This is a 900 px container that is centered&lt;/div&gt;
</code>
