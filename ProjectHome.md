Google Earth's KML format is oddly missing a `RegularPolygon` or `Circle` element.  Until they get added in a future version, this code will generate the appropriate `Polygon` xml snippet.  Regular polygons with more than 20 or 30 sides is a good approximation of a circle.

It's one file written in python, but i used a very "unexotic" coding style to aid in porting.  It would take 10 minutes to port to PHP, javascript or perl (or C++ for that matter). **Volunteers and requests welcome!**

The algorithm and details will be posted shortly.

## News ##

11-Sep-2013: Javascript port is at https://github.com/lehne/mapCircle thanks jeff l!

31-Mar-2013: New Ruby port is at  https://github.com/mbrookes/kml_polygon  thanks mbrookes!

04-Apr-2009: Version 3??? Original python code translated to VB.NET
> Adds code to use an oblate spheroid rather than a spherical model.
> Adds code to draw circular arcs as part of a polygon.

13-Sept-2007: Version 2 released!  This simplifies the XML and adds a command line interface.

10-Sept-2007: Version 1

## Circles ##

really you can make any type of regular polygon.  If the number of sides is > 20 then it looks like a circle.

![http://kmlcircle.googlecode.com/svn/trunk/images/circles.jpg](http://kmlcircle.googlecode.com/svn/trunk/images/circles.jpg)


## Stars ##

![http://kmlcircle.googlecode.com/svn/trunk/images/stars.jpg](http://kmlcircle.googlecode.com/svn/trunk/images/stars.jpg)

## Arcs ##
![http://kmlcircle.googlecode.com/svn/trunk/images/arcs.jpg](http://kmlcircle.googlecode.com/svn/trunk/images/arcs.jpg)