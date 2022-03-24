# creation-day

A day in the life of a canvas.

[VIEW](https://gwest7.github.io/creation-day/)

An attempt to recreate the basic elements of sunset/sunrise landscape photos using canvas. This was a one day project done on Saturday, 26 Feb 2022. I pushed a few days later and made some teaks since. No code was copied, except for examples documented in MDN Web Docs.

### Features
* A canvas day is 60 seconds and all animations are time based (using `Date.now()`).
* The page is responsive in that a second after a viewport dimension change a new canvas (with a 1:1 pixel ratio) will be drawn too.
* Birds' wing movements are simply bezier curves with moving start and end control points.
* All other animation is simply Cos and Sin coordinates based on the angle of the day. (A day == Pi * 2)
* All colour adjustments are simply two colours mixed to a ratio calculated using the day-angle. Eg. at 0 be red and at Pi be blue so at half-Pi it will be dark purple.

### TODO:
* Add a landscape object (perhaps a tree) with moving shadow
* Give the earth a radial fill affected by die sun

