---
layout: post
title:  "Using Ogr2Ogr to import Shapefile into Sql database"
date:   2017-05-01 15:27:57 +0200
categories: GIS
---

[ogr2ogr](http://www.gdal.org/ogr2ogr.html) is a binary that comes with Qgis that can be used to convert simple features data between file formats.  OGR stands for OpenGIS Simple Features Reference Implementation.

I had a downloaded some open geodata as a shapefile.  I wanted to be able to use the data in a webmap but didn't have a arcgis server.   I decided to import the shapefile data into sql and create a .Net webapi to query the database. ogr2ogr made it extremely easy to import a shapefile into sql.

After creating a empty database in MsSql server, I used the ogr2ogr conversion command from [Coderwall- Importing a shapefile into sql server](https://coderwall.com/p/v_nrig/importing-a-shapefile-into-sql-server-2012)


{% highlight ruby %}
"C:\<location of ogr2ogr>\ogr2ogr.exe" -overwrite -f MSSQLSpatial "MSSQL:server=<database server name>;database=<database name>;trusted_connection=yes" "C:\<path to shapefile>\<Shapefile>.shp"  -lco UPLOAD_GEOM_FORMAT=wkt
{% endhighlight %}


