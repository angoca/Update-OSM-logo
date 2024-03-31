# Update-OSM-logo

In this repository, I show my updates to the OpenStreetMap logo.
It has no visual change but mostly internal changes that improve its usage when printing or creating other graphical elements.

I have performed several changes, and each step is presented here so anyone can see the difference in each step by doing a diff on the XML files.

This is the description of each step, starting from the original one taken from the wiki:

* 1: It starts with the original logo from the wiki: https://wiki.openstreetmap.org/wiki/File:Public-images-osm_logo.svg - 17:25, 23 November 2012
* 2: Converted to 96 dpi. The current version has a 90-dpi resolution, which is associated with the default resolution of the earlier version of Inkscape.
* 3: Removed unnecessary elements from the diagram (extra magnificent glass, another background).
* 4: Binary numbers changed to stand for OSM letters in binary. Current ones were meaningless.
  * Current
    * 01011001
    * 00110101
    * 10010011
  * New
    * 01001111 – Represents O in ASCII and Unicode.
    * 01010011 – Represents S in ASCII and Unicode.
    * 01001101 – Represents M in ASCII and Unicode.
* 5: Changed the export directory and the title.
* 6: Recreated from scratch and all elements copied from the current file and pasted into the new one. The resulting file is much smaller than the first one (From 174714 to 95993).
* 7: Fixed second binary layer to use "OSM" letters (As described in point 4). Fixed typo in "Magnifying Galss" to "Magnifying Glass"
* 8: Formatted using `prettier` and `@prettier/plugin-xml`

It also includes the differences between each step except for the 6, which was recreated.

New logo ![New logo](8-Public-images-osm_logo.svg)

Old logo ![Old logo](1-Public-images-osm_logo.svg)
