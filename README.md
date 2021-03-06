Jenn's Color Conversion Library
=============================

tweet: @jennschiffer
email: jenn@fogcreek.com

## What's this supposed to do

This is a collection of functions for converting color values:

1. rgb to hex
2. hex to rgb
3. rgb to color names
4. color names to rgb

### I want to learn

1. how to write unit tests (qunit test framework)
2. create a simple library to publish to npm
3. how to convert rgb/hex to color names
4. hsl stuff

### Live coding 

I'm live coding this on my [youtube channel](https://youtube.com/user/forcedtodrive) - please [take my survey](https://goo.gl/forms/oSkQH1pJBxJzNuj03)

**in [part 1](https://www.youtube.com/watch?v=WfOI2CXcpW0) i wrote some qunit tests.**

some questions included:

1. "why does qunit cli require the -c flag" it doesn't - i installed qunit when i should have installed qunitjs because who knows honestly ugh
2. "it has got to be easier to compare arrays with regards to their values, c a n i l i v e" nope i'd have to compare values recursively as i feared (or add something like underscore as a dependency), good thing i'm using an object for rgb

i also recommended that you check out my pal [alex sexton's talk on color names](https://www.youtube.com/watch?v=HmStJQzclHc)

**in [part 2](https://www.youtube.com/watch?v=-tSymGoDnRA) i will start writing the functions and teaching about color values**

what in the heck is rgb and hex???????

binary system - base 2 -> 0, 1
hexadecimal system - base 16 -> 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, A, B, C, D, E, F

red, green, blue - 0 to 255, 0 to 255, 0 to 255
hex - 00 to FF, 00 to FF, 00 to FF -> #xxxxxx


**in [part 3](https://www.youtube.com/watch?v=Ahut2jeh0WQ) i fixed some bugs, wrote some tests, DRY'd up some codes**

DONE:
* better handle single digit rgb property values when converting to hex !important
* type checking of rgb object properties
* fix bugs in rgb:
  - single digits don't work
  - 0 as a value doesn't work
* explore better error handling
* DRY up the code

**in [part 4](https://www.youtube.com/watch?v=8nN5dfvKwVg) i wrote the color name functions, added an object of colornames mapped to hex values, wrote some tests, and learned about qunit's assert throws function!**

to do: write more nifty assert throws tests and publish this to npm maybe :D

** in [part 5](https://www.youtube.com/watch?v=ICSDSlEPEyk) i wrote many tests and passed them all! **

in the next livestream, we're gonna publish this to npm!