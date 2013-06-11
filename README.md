Active Tectonics of the Andes map
==============================

Active Tectonics of the Andes map (ATA) is a GIS database representing a digital compilation of active faults in the (northern) Andes.  It was created by Gabriel Veloza, Richard Styron, Mike Taylor and Andres Mora.  Gabriel Veloza is the primary maintainer of the ATA map, though Richard Styron is largely responsible for GitHub development.
The database is currently available in .shp (for ArcGIS, Quantum GIS, etc.), .kml (Google Earth), and .gmt (text, for plotting in Generic Mapping Tools).  The .shp format contains the most metadata.

For questions or concerns, please contact Richard Styron (richard.h.styron@gmail.com)


Installation
----------------

These files are not executable and do not need to be installed.  Simply download them.


Plotting Data
----------

ArcMap
-------

The .shp file may be opened in ArcMap through the Add Data tool, and the symbology may be adjusted with the fault type field.


Google Earth
-------------

In order to import the KML version into Google Earth, open the file(s) using the program.  The files will be opened under the 'Temporary Places' folder and may be permanently stored by moving them into the 'My Places' folder.

Generic Mapping Tools
----------------------

The GMT version may be plotted using psxy with the -M flag.  Kinematics may be plotted using the -Sf flag with appropriate options.



References
--------------
The ATA database is a compilation of both structures taken from the literature, and our interpretations of field, remote sensing, and geophysical data.  Sources used are listed in the database itself.  The ATA map may be cited as:

Veloza, G., Styron, R., Taylor, M., Mora, A., 2012, Active Tectonics of the Andes: An open-source archive for active faults in northwestern South America, GSA Today, vol. 22, no. 10, p. 4-10, doi: 10.1130/GSAT-G156A.1.