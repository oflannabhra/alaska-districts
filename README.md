# alaska-districts
[Kartograph](http://kartograph.org/) project to create an SVG of Alaska with school district boundaries with shapefiles from the US Census Bureau.

To build an svg (after installing kartograph), run the following command from the root directory:
```
kartograph alaska.json -o html/alaska.svg
```

The `html/alaska.html` loads the SVG from the master branch of this repository, so you might want to reference your local one while testing.