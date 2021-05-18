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
  <div class="black-3">
    <p class="cyan-4-text">This is a sentence with cyan-4 text color.</p>
  </div>
</code>
