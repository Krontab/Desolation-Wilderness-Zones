
# Desolation Wilderness
"*Welcome to Desolation Wilderness, 63,960 acres of subalpine and alpine forest, granitic peaks, and glacially-formed valleys and lakes. It is located west of Lake Tahoe and north of Highway 50 in El Dorado County. Desolation Wilderness is jointly administered by both the Eldorado National Forest and Lake Tahoe Basin Management Unit.*" - El Dorado National Forest / Lake Tahoe Basin Mgt Unit


## GPX / KML Mapping Data
[The content in this repository][l9] are mapping data files in [GPX][l10] and
[KML][l11] format that contain useful references for trip planning to Desolation
Wilderness. Waypoints such as significant trailheads and parking lots, as well
as Polygon objects that match the official Desolation Wilderness permit zone
boundaries have been added will be refined over time. Please notify me of any
errors or room for improvement! THIS IS WORK IN PROGRESS!

I used [CalTopo][l8] as the primary interface to create the
waypoints and shape data. [View my CalTopo Map here!](https://caltopo.com/m/RBH3)

1. Using the [zone map][l6] from the Desolation Wilderness Volunteers
[website][l4], I created a geospatial layer and aligned it as best I could and
tediously created each zone as a polygon object by hand. I will update many more
times in the future to improve accuracy and aesthetics.

2. I exported the CalTopo map to a KML, and then performed some light edits with
[Google Earth][l7] to produce a clean export:
  * Changed the name of the document
  * Added back the folder structure that is lost on CalTopo KML export.
  * Changed the sort-order of the waypoints (A-Z)
  * Added the reference zone map as a KML layer and aligned it by hand as best
  as I could (omg, PITA).


3. I exported the CalTopo map to a GPX, and basically left it as-is.

## How to Use These Files
Simply open the files using an application like Google Earth, Garmin Basecamp,
or any other mapping software that can interpret GPX and KML files.

Or better yet, [view my CalTopo Map here for FREE!](https://caltopo.com/m/RBH3)

CalTopo offers free access to certain features, but if you are regularly hiking
and need access to quality trail data and printed maps, their
[paid-subscriptions][l12] are well worth your investment. Highly recommended!

## Desolation Wilderness Permit Zones
When visiting Desolation Wilderness for the purpose of backpacking and staying
overnight, you are required to [obtain a permit][l3]. The permit application
requires that you to specify the starting trailhead and wilderness zone that
you will be spending your first night at. There are 45 wilderness zones to
choose from, and the rule is that you stay at the specified zone on the first
night, but you may travel to any other zone on subsequent days.

The zone map you are directed to use is located [here][l6] on the [Desolation
Wilderness Volunteers][l4] site. The map isn't intended for navigation purposes,
just figuring out which zones you plan on visiting. The exercise of going
back and forth between navigational maps and this zone map is a bit of a chore.

That's why I decided to build these GPX and KML files!

## Official Desolation Wilderness Links
* [El Dorado National Forest - Desolation Wilderness][l1]
* [Lake Tahoe Basin Mgt Unit - Desolation Wilderness][l2]
* Wilderness Permits: [Recreation.gov][l3]
* [Desolation Wilderness Volunteers (DWV)][l4]

## DISCLAIMER
**By using this data, you agree that you are assuming _all risks_ associated with
navigation and planning your travel to a wilderness area and that it is your
responsibility to understand and comply with the laws and regulations from the
proper authorities.**

**Basically, if you use this information and you nearly die, get arrested or
fined for being in the wrong place at the wrong time, or you are half-eaten by a
bear and/or mountain lion and stashed away for a midnight snack near Lower Velma
Lake (beautiful area, btw)... it's not my fault.**

**Also I am NOT affiliated in any way with El Dorado National Forest, Lake Tahoe
Basin Mgt Unit, Desolation Wilderness Volunteers, or any other government or
commercial entity. This is a personal project that I work on in my spare time as
a private outdoor enthusiast to help me with my own planning efforts for trips
to one my favorite places to visit. You are welcome to use it, modify it, laugh
at it, or contact me to contribute to it's accuracy or value. I do not claim
ownership of any of the data or systems that I used to create the content, nor
do I offer any warranty or guarantee of it's accuracy. I'm just a dude that
loves the outdoors and helping others, so if you appreciate it... awesome!**

**If you have any doubt about trusting this information, _don't use it._**



[l1]: https://www.fs.usda.gov/detail/eldorado/specialplaces/?cid=fsbdev7_019062 "El Dorado National Forest"
[l2]: https://www.fs.usda.gov/recarea/ltbmu/recarea/?recid=11786 "Lake Tahoe Basin Mgt Unit"
[l3]: https://www.recreation.gov/permits/233261 "Wilderness Permits"
[l4]: http://www.desowv.org "Desolation Wilderness Volunteers (DWV)"
[l5]: http://www.desowv.org/files/DWTPG.pdf "Trip Planning Guide"
[l6]: http://desowv.org/images/stories/DesoZoneMap2.jpg "Zone Map"
[l7]: https://www.google.com/earth/ "Google Earth"
[l8]: https://caltopo.com
[l9]: https://github.com/Krontab/Desolation-Wilderness-Zones "Desolation Wilderness Zone GitHub Repository"
[l10]: https://github.com/Krontab/Desolation-Wilderness-Zones/blob/master/Desolation%20Wilderness%20Zones.gpx "GPX File"
[l11]: https://github.com/Krontab/Desolation-Wilderness-Zones/blob/master/Desolation%20Wilderness%20Zones.kml "KML File"
[l12]: https://caltopo.com/about/pricing/individual-accounts "CalTopo Paid Subscriptions"
