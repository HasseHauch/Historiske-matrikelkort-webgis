Leaflet.js l�sning til at vise historiske matrikelkort
=======================
###Beskrivelse af de data som indg�r i denne l�sning###

Alle planer er scannet om jpg filer, derefter georeferet i QGIS og exporteret som geotiff.
Derefter er alle kort tilet i tilemill og exproteret som MBTiles.

MBTiles filerne er derefter uploadet til en Amazon server hvor der er installeret tilestreem (webtile servise fra MapBox) og udstillet som en TMS service.

###Leaflet.js til visning af historiske matrikelplaner###
Denne Leaflet.js l�sning viser s� alle kortene i en samlet l�sning.

Da der er ca. 100 kort er denne l�sning lavet til at filtrere lagkontrollen se den kun viser de kort der d�kker det aktuelle kortudsnit. Sagt med andre ord, lagkontrollen �ndre sig n�r man zoomer eller panorer i kortet. 
