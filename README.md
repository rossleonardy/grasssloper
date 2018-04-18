# grasssloper
grasssloper is a grasshopper script that draws a sloper pattern for you from human body measurements.
A sloper is a 2D drawing-a pattern-that provides the basis for a 3 dimensional garment that fits accurately. Currently grasssloper contains a torso block and a skirt block; sleeve and pant blocks are to be added.

## installation
Script requires Rhino and Grasshopper 0.9.76 or higher. The script currently requires centimeters & the metric system.

## using grasssloper
### Bodice
  * Measure and input bust, waist, and center back in CM
    * Center back is a vertical line from C7 vertebra to waist
    * ease is added
  * Bake the TORSO SLOPER collection immediately below the inputs.
### Skirt
  * Measure and input bust, waist, hip depth, hip, and skirt length
  	* Hip depth is a vertical line from waist to hip over the side.
  * Bake the SKIRT SLOPER collection
### Exporting
  * Select the desired geometry in Rhino and use File > Export Selected
  * Export to adobe illustrator or other desired format-make sure your rhino file's units are in centimeters
  * Print using a plotter printer or with a print tiling tool, such as Adobe Illustrator.