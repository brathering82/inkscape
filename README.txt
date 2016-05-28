- INSTALL

Put "render_scale.inx" and "render_scale.py" in your Inkscape extension directory.
On Linux:   "~/.config/inkscape/extensions/"
On Windows: "Inkscape\share\extensions\" (inside your programs folder)

- COMMENT
Tested on Inkscape 0.91
Author: Sascha Poczihoski
Contact me at s.pocz@posteo.de

- Known bugs
	ui float precision is limited to 1
	suffix doesn't support several special chars

- Changelog
05.03.2015
	Added Label offset. This will move the labels side to side and up/down.
	Added option to use the center of a bounding box as the drawing reference.
	Added ability to set line stroke width.
	Added option to add a perpendicular line.
	Added mathematical expression to the number format. For example, to divide the label number by 2, use "n/2".
	Added "Draw all labels" checkbox.
	Added option to flip the label orientation.
	Added support for "Draw every x lines" = 0 in order to remove lines.
	Last label is not drawn if the circular count is 360 to prevent the last label overwriting the first.
	Changed font size to Units instead of Pixels, so the scale looks the same if you change the units.
17.02.2015
	include changes made by Paul Rogalinski-Pinter
	indentation cleanup - it's all tabs now
	fixed line scale bug
10.07.2014
	updated the install packages with the changes made by Roger Jeurissen
27.06.2010
	fixed ° (degree char) in suffix
12.06.2010
	changed default circular label offset to -4.8 from 8
		- so the label will spawn above the scale
	changed INSTALL-section in README
		- added extension path for inkscape-0.47
01.12.2009
	added tabs for ui
	added circular scales

18.11.2009
	default values updated, so there is something visible after first install

17.11.2009
	initial release
