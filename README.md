This has all the JSON files for my GeoGuessr maps, or at least all of them that I remember to put here. Much easier to keep track of, I just feel like the locations shouldn't be a secret, enables me to ramble more than GeoGuessr's description field for maps would allow…

TODO: Whoops I forgot to list all the maps

# Australia

Maps all located in Australia, mostly converted from things.

### [Prohibited Areas](https://www.geoguessr.com/maps/63fbc3e27317941effaf5d91)

Polygon map converted from the Prohibited_Areas layer of [NM_Reserves from Geoscience Australia](https://services.ga.gov.au/gis/rest/services/NM_Reserves/MapServer). Mostly just because it sounds ominous and therefore funny. It's mostly just military bases I think, but not many of those have Street View coverage, funnily enough.

## GTFS conversions

Results of me loading a GTFS feed and getting locations for all the stops.

### [Melbourne Metropolitan PTV Stops](https://www.geoguessr.com/maps/6411aa750061ca14feaa0abf)

Train, tram and bus stops from http://data.ptv.vic.gov.au/downloads/gtfs.zip, from folders 2, 3 and 4.

### [NSW Transport Stops](https://www.geoguessr.com/maps/672864588a593cd5d6bd9bca)

All the stops from https://opendata.transport.nsw.gov.au/data/dataset/timetables-complete-gtfs, minus "stops" that only have school bus services, which are for the most part random roads in the middle of nowhere and are not bus stops in the slightest.

### [Transport Stops of Australia](https://www.geoguessr.com/maps/6728f9c9d123b52b5c1cec23)
ALL the stops from:
- Transport Canberra, Canberra Metro Operations (ACT): https://www.transport.act.gov.au/contact-us/information-for-developers
- Every org in NSW: https://opendata.transport.nsw.gov.au/data/dataset/timetables-complete-gtfs, except for the school bus only stops as before
- Armidale autonomous buses (NSW): https://opendata.transport.nsw.gov.au/data/dataset/autonomous-vehicles-gtfs-timetables/resource/5cc9f80a-df38-43b1-bd57-798c8927aed0 Is that even still a thing? Is it already in the NSW Complete feed anyway? Who knows
- MetroTAS (TAS): https://www.metrotas.com.au/community/gtfs/
- TransLink (QLD): https://www.data.qld.gov.au/dataset/general-transit-feed-specification-gtfs-translink
- TransPerth (WA): https://www.transperth.wa.gov.au/About/Spatial-Data-Access
- Adelaide metro buses but I forgot where from
- Darwin and Alice Springs buses (NT) but I forgot where from
- Port Philip ferries (VIC) but I forgot where from
- PTV (VIC): http://data.ptv.vic.gov.au/downloads/gtfs.zip

Generated and panned to the stop automatically, so if you don't see a bus stop in front of you, blame the transport agency for misplacing the stop in the GTFS data compared to where it actually is (I am looking at you PTV), or blame the state government/LGA/whoever for being too lazy to put a sign there (I am looking at you, NSW and Tasmania).

This pushes the limits of how many locations GeoGuessr will let you put in a handpicked map, so it was annoying to upload.

## Other converted points

Other things where I converted existing data to locations.

### [Australia Post Locations](https://www.geoguessr.com/maps/63a670ce587ddd13f67a38c6)

All the Australia Post offices in Australia from https://tiles.terria.io/static/auspost-locations.csv, which is just available on the National Map, and doesn't elaborate on where the data is from, and doesn't have external territories (I added two of them that have official coverage manually).

TODO: Version that does include third party coverage, since there's a few of those, but I would want to make sure it doesn't include panoramas inside random shops which happen to be the closest thing to the post office…
TODO: Version without gen 1 coverage might also be nice

### [Maccas of Australia](https://www.geoguessr.com/maps/63fbbe61291e7ca01142f07f)

Converted from the store finder. _Note:_ this has a lot of third party panoramas, a lot of which are a bit shite.

## ACT/Canberra

Maps entirely within my glorious hometown.

### [Australian Capital Territory Feature Names](https://www.geoguessr.com/maps/63a662ba587ddd13f67a3634)

[Without parks/unit complexes](https://www.geoguessr.com/maps/63a6d8c2607e3e4aa659226e)

Imported straight from https://actmapi-actgov.opendata.arcgis.com/datasets/ACTGOV::act-feature-names/about (which appears to no longer exist), data last updated 4 November 2022 and I guess it won't be again if it no longer exists. These are locations in the ACT that the government apparently thinks are interesting enough to deserve a name.

### [Canberra Centenary Trail](https://www.geoguessr.com/maps/666021fc7a64c94aed9996be)

Generated points from the converted [official GPX file for the Canberra Centenary Trail](https://www.parks.act.gov.au/find-a-park/canberra-centenary-trail) (made into a polygon by buffering it by 20 metres).

Only official coverage, which isn't quite the whole trail.

Accidentally ends up being quite difficult, given it's rural trekker pain and suffering, and with a relatively small map scale so the scoring is quite harsh. You might get a few urban rounds here and there, though.

### [Transport Canberra Bus Stops](https://www.geoguessr.com/maps/63a664ca6f3bc80e05e51f26)

Generated from the Transport Canberra GTFS feed, this takes you through all of Canberra's bus stops… well, all of them that are operated by Transport Canberra, and that have official coverage within 20 metres (I think that excludes maybe the Tuggers bus interchange?).

The locations are on the bus stop and not the road in front of it, which with this scale of map, could be the difference between a 5K and not if you click the road instead.

# Other

### [Gallipoli Peninsula](https://www.geoguessr.com/maps/6446e2a8a35ad1a02eec171d)

A polygon map containing one region of the peninsula of Gallipoli/Gelibolu, Türkiye. Contains a lot of trekkers of memorials and cemeteries and things, naturally. This sounded like a funny bit at the time the last Anzac Day.

### [Disputed Territories](https://www.geoguessr.com/maps/63e65287a029e9b998de764b)

Polygon map converted from Natural Earth's disputed areas data.

TODO: Version which takes out Israel/Taiwan/Sabah purely for the reason that they end up being selected too often.