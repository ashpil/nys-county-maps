# nys-county-maps
Sample interactive maps containing the outlines of the 62 counties in New York State. These maps can be used in combination with data sources to display information about counties and other areas within New York State, such as population values or to pinpoint locations and click out to Google maps. 

Unlike PDF, JPG, or other graphic versions of the New York State map, these maps are dynamic and can be used and re-used for a variety of purposes and continuously updated with current data. And because they are web-based and responsive, they will size appropriately to all devices from smartphones to big-screen monitors.

These maps were created using the New York Counties SVG file from Wikimedia Commons at https://commons.wikimedia.org/wiki/File:New_York_Counties.svg. The svg file was then loaded into the jQuery Mapael "SVG to Mapael" converter at https://www.vincentbroute.fr/mapael/create-map.php which generates the jQuery Mapael map file from the SVG file that contains the paths of the areas to retrieve. From that basis, individual data sets can be loaded into the map to display specific information of interest.

The New York Counties SVG file is licensed under the GNU Free Documentation License, Version 1.2 or any later version published by the Free Software Foundation https://en.wikipedia.org/wiki/GNU_Free_Documentation_License. Copyright (C) André Koehne.
jQuery Mapael is licensed under the MIT license (http://www.opensource.org/licenses/mit-license.php). Copyright (C) 2013-2017 Vincent Brouté.
