This has all the JSON files for my GeoGuessr maps, or at least all of them that I remember to put here. Much easier to keep track of, I just feel like the locations shouldn't be a secret, enables me to ramble more than GeoGuessr's description field for maps would allow…

TODO: Should separate this into source and output (from MapCheckr or what have you (or ideally geoguessr-map-maker))

TODO: Whoops I forgot to list all the maps

# Australia
Maps all located in Australia, mostly converted from things.

### [Prohibited Areas](https://www.geoguessr.com/maps/63fbc3e27317941effaf5d91)
Polygon map converted from the Prohibited_Areas layer of [NM_Reserves from Geoscience Australia](https://services.ga.gov.au/gis/rest/services/NM_Reserves/MapServer). Mostly just because it sounds ominous and therefore funny. It's mostly just military bases I think, but not many of those have Street View coverage, funnily enough.

## GTFS conversions
Results of me loading a GTFS feed and getting locations for all the stops.

### [Melbourne Metropolitan PTV Stops](https://www.geoguessr.com/maps/6411aa750061ca14feaa0abf)
Train, tram and bus stops from http://data.ptv.vic.gov.au/downloads/gtfs.zip, from folders 2, 3 and 4.

## Other converted points
Other things where I converted existing data to locations.

### [Australia Post Locations](https://www.geoguessr.com/maps/63a670ce587ddd13f67a38c6)
All the Australia Post offices in Australia from https://tiles.terria.io/static/auspost-locations.csv, which is just available on the National Map, and doesn't elaborate on where the data is from, and probably doesn't have the Christmas Island post office and things like that so maybe I should add in external territories manually.

### [Maccas of Australia](https://www.geoguessr.com/maps/63fbbe61291e7ca01142f07f)
Converted from the store finder. *Note:* this has a lot of third party panoramas, a lot of which are a bit shite.

## ACT/Canberra
Maps entirely within my glorious hometown.

### [Australian Capital Territory Feature Names](https://www.geoguessr.com/maps/63a662ba587ddd13f67a3634)
[Without parks/unit complexes](https://www.geoguessr.com/maps/63a6d8c2607e3e4aa659226e)

Imported straight from https://actmapi-actgov.opendata.arcgis.com/datasets/ACTGOV::act-feature-names/about (which appears to no longer exist), data last updated 4 November 2022 and I guess it won't be again if it no longer exists. These are locations in the ACT that the government apparently thinks are interesting enough to deserve a name.

### [Canberra Centenary Trail](https://www.geoguessr.com/maps/666021fc7a64c94aed9996be)
Generated points from the converted [official GPX file for the Canberra Centenary Trail](https://www.parks.act.gov.au/find-a-park/canberra-centenary-trail) (made into a polygon by buffering it by 20 metres).

Only official coverage, which isn't quite the whole trail.

Accidentally ends up being quite difficult, given it's rural trekker pain and suffering, and with a relatively small map scale so the scoring is quite harsh. You might get a few urban rounds here and there, though.


# Other

### [Gallipoli Peninsula](https://www.geoguessr.com/maps/6446e2a8a35ad1a02eec171d)
A polygon map containing one region of the peninsula of Gallipoli/Gelibolu, Türkiye. Contains a lot of trekkers of memorials and cemeteries and things, naturally. This sounded like a funny bit at the time the last Anzac Day. 