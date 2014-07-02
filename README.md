Scales
=====

What is Scales?
-----

Scales is a less boilerplate covering almost every conceivable HTML element, with a quick way to style all form elements consistently with preset colors.

Scales is based in part on [Pattern Lab's atomic design methodology](http://patternlab.io/). A few things at the "molecule" level are included, but this is intended to be a starting point, not a complete website stylesheet, so the "organisms" and "templates" files are intentionally blank for you to fill with your own code.

How to use Scales
-----

To use Scales, you'll need a Less compiler. There are compilers available for [Windows](http://winless.org/) and [Mac](http://incident57.com/less/), as well as server-based solutions.

Include the scales.less file in your project. It will call all the other files in the correct order.

There's also an styleguide.html file included in the the folder with the Scales less files, which is a useful list of all the included HTML elements, and a good place to try out your own layout elements.

Designing from the bottom up
-----

__Too often as developers, we get design files that look great on paper, but have subtle inconsistencies and gaps in planning that only make themselves known once building begins.__ 

So how do you deal with that? By designing and building the same way that css and html work. Scales is designed to style all the most basic elements FIRST, and later group those elements into objects and templates. If someone puts a list or a table where it wasn't planned for, it's still styled correctly.

__Designing__ from the bottom up ensures that gaps are visible early, and can be dealt with quickly.

__Building__ from the bottom up ensures that your code stays readable, solid and free from hacks and overrides.
