# Here's a test of some math


The new version of Atlas supports Markdown as a source format as well as HTML. So, if you like, you have the option of authoring .md files in Atlas, and then when you add them to the build list, we convert to proper HTMLBook behind the scenes (we take care of generating the necessary <section> tags, so you don’t need to worry about that)

Regarding math, you can indeed use the Latex equation editor that Nellie mentioned. Or if you’re adding them manually, please just wrap them in a <span> with the attribute data-type=“tex”, like the following:

<span class="math-tex" data-type="tex">
   \(x = {-b \pm \sqrt{b^2-4ac} \over 2a}\)
</span>

Here's a formula:

<span class="math-tex" data-type="tex">
   \lim_{x \to \infty} \exp(-x) = 0
</span>



