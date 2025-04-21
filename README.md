This has all the JSON files for my GeoGuessr maps, or at least all of them that I remember to put here. Much easier to keep track of, I just feel like the locations shouldn't be a secret, enables me to ramble more than GeoGuessr's description field for maps would allow…

I hope that this is a good way to list them all, if not, well, that sucks. I won't be morally opposed to using issues to report locations that are broken or are in maps where they don't belong, but with the reminder that I might not ever get around to dealing with them because I'm the queen of procrastination.

[Distribution stats](https://docs.google.com/spreadsheets/d/1y5rDjgt1mHDUifivFd9mWOJ63U9kNy7SzLOUUtgwVj4/edit?usp=sharing): Spreadsheet with the percentages of how often countries or Australian statistical areas appear in each map, if you're into that sort of thing. (Needs updating!)

# Australia

Maps all located in Australia, mostly converted from things.

## - 

### [Prohibited Areas](https://www.geoguessr.com/maps/63fbc3e27317941effaf5d91)

Polygon map converted from the Prohibited_Areas layer of [NM_Reserves from Geoscience Australia](https://services.ga.gov.au/gis/rest/services/NM_Reserves/MapServer). Mostly just because it sounds ominous and therefore funny. It's mostly just military bases I think, but not many of those have Street View coverage, funnily enough.

### [Super Smash Bros. Tournament Venues of Australia](https://www.geoguessr.com/maps/6408d151f551fe4625684d39)
An attempt to get indoor (where possible) and outdoor views of everywhere in Australia that SSB4/SSBU tournaments are held, including unofficial coverage if I have to, starting off with locations imported from start.gg, but I neglected it. Whoops.

### [ABS Bounded Localities](https://www.geoguessr.com/maps/6769ca831058622ffe7c96b9)

20 locations each from every individual polygon in the ABS's Urban Centres and Localities data where SOS_NAME_2021 (Section of State) = "Bounded Locality". In other words, all the random small towns in Australia.

[Polygon map](https://www.geoguessr.com/maps/6769568e801d2d75f4c1365f) that was just plainly converted from the data, if you really want that, but it really shows how much the distribution for polygon maps sucks. It really likes to choose West Island/Bantam/Rottnest Island at least once per game and they become freebies.  
[Buildings only](https://www.geoguessr.com/maps/67889707634fb14924577f10) This only has panoramas featuring buildings of some sort according to the places metadata, in an attempt to avoid rural roads that the ABS counts as part of the town.

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

Converted from the store finder. Now without third party coverage, though maybe I should make a version that does include it, so you sometimes get silly photospheres on the inside of them… but eh.

### [Where's that Zambrero?](https://www.geoguessr.com/maps/63fc80e8163859d3a41ff66f)

Converted from the locations from the store finder (whenever it is I did that). Removed some locations that are "coming soon" because for our purposes, that just means there is not actually a Zambrero there. Hopefully no other locations are misplaced.

### [Public Toilet Locations of Australia](https://www.geoguessr.com/maps/63f782263345d08e8984c221)
Converted from the government's [National Public Toilet Map](https://data.gov.au/dataset/ds-dga-553b3049-2b8b-46a2-95e6-640d7986a8c1/details). Probably does not have trekkers inside the actual toilet.

### [Polling Places of the 2022 Australian Election](https://www.geoguessr.com/maps/63fbc199ee7c24975fa7360a)
Converted from the AEC Tally Room archive (TODO: probably nice to link to that). This includes any old random building that was used as a polling place, so might include random town halls in tiny towns in the middle of nowhere or whatever.

### [Polling Places of the 2023 Australian Referendum](https://www.geoguessr.com/maps/67334c37e70455635919be46)
Converted from AEC Tally Room data: https://results.aec.gov.au/29581/Website/Downloads/GeneralPollingPlacesDownload-29581.csv  

TODO: Add the mobile polling places that aren't actually mobile (e.g. where Cocos/Christmas Islanders voted, which I am fairly sure is a fixed location, but isn't in the data normally)

### [The Good Guys](https://www.geoguessr.com/maps/67d65991f53112cd532223aa)
This came to me in a dream. As soon as I woke up I knew I had to delve into their website to find the list of stores, and convert it into a map. I guess corporations are putting ads inside my subconscious now, but eh. Features official coverage of most stores where the front of the store (or similar) is visible.

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

### [Australian Capital Territory w/o residential zones](https://www.geoguessr.com/maps/63fb171be94499a1da3d3d2c)

Polygonal map where I attempted to make a Canberra map that avoids just being suburban areas. Used the zoning data from ACTmapi to find areas that are not in residential zones, or have something that is not a residential zone surrounding them. If you think that means it's just the middle of town centres and therefore should be trivial, think again…

The file ended up being like 200MB so I can't upload it to this repository. TODO: Post the script that generates this map, once I clean it up a bit (a lot)

[Without national parks](https://www.geoguessr.com/maps/65d0dec8db7bd9b93b28270a): A variant that uses the "ACT DIVISIONS" data to exclude anywhere that is not assigned to a division/suburb, which means no endless Namadgi hell, for example.

### [Australian War Memorial](https://www.geoguessr.com/maps/6447a0f19f7accd3e0a945c0)
One of the smallest maps I will ever make. Just the trekkers inside/around the War Memorial and the road directly outside it.

### [artsACT Public Art](https://www.geoguessr.com/maps/67e789dad42b1145278d9182)
All the public art listed on the [artsACT website](https://www.arts.act.gov.au/public-art). Potentially contains unofficial coverage! Also I need to make it consistent whether I'm snapping the pinpoint to the art's POI or the road the street view is on. Whoops. And some older coverage means that sometimes the art isn't even there. Yeah, it didn't work out too well as a map.

# Other

## Conversions

### [MusicBrainz Places](https://www.geoguessr.com/maps/6411b65ecf2a0544ea0d704f)
Converted from the API, all the venues, recording studios, whatever else is added as a place (and has coordinates) to MusicBrainz. Dunno when I last updated the data, from the file modification date it would seem to be March 2023-ish.

### [Tourist Attractions (Wikidata)](https://www.geoguessr.com/maps/674234923437d0ed23a18f13)

Converted points from the Wikidata query:
```
SELECT DISTINCT ?item ?geo ?itemLabel WHERE {
  ?item (wdt:P31/(wdt:P279*)) wd:Q570116;
    wdt:P625 ?geo SERVICE wikibase:label { bd:serviceParam wikibase:language "[AUTO_LANGUAGE],mul,en". }
}
```
This returns all the tourist attractions in the world (that Wikidata knows about) (and has official coverage nearby).

Ends up being quite Italy-heavy. Do I make a version without Italy? Or do I figure out what it is about Italy that causes it to have so many tourist attractions, and do something else to rebalance it…

### [Burger Restaurants](https://www.geoguessr.com/maps/67431b8d02138d6ea654559e)

Explaining GeoGuessr to an American: So, imagine guessing a location that serves burgers…

Converted points from querying Overpass Turbo for `cuisine=burger`. Expectedly very USA-heavy.

[No USA](https://www.geoguessr.com/maps/674409afa919c46bb1fa67f6) This still has some US territories, because I was too lazy to remove those too, but those weren't the problem in terms of balance so it's fine.
[No chains](https://www.geoguessr.com/maps/674427903437d0ed23ac97eb) Removed everything with brand=\*, operator=\*, and a few things manually; so it's not just Maccas of the World And Some Other Stuff

### [Travel Pics Game Submissions](https://www.geoguessr.com/maps/67eab019c9422fa373d1e895)

Locations that people have submitted to the Travel Pics Game in [Chicago Geographer's Discord server](discord.gg/chicagogeographer). Uses data from [tastyCheese's map](https://tpg.tastedcheese.site/).

## Polygon maps

### [Gallipoli Peninsula](https://www.geoguessr.com/maps/6446e2a8a35ad1a02eec171d)

A polygon map containing one region of the peninsula of Gallipoli/Gelibolu, Türkiye. Contains a lot of trekkers of memorials and cemeteries and things, naturally. This sounded like a funny bit at the time the last Anzac Day.

### [Lesbos (Lesvos)](https://www.geoguessr.com/maps/644fe7f7a917719b5a62da9c)
Polygon map of the island of Lesbos in Greece, where lesbians were invented. GeoGuessr censors the title. Since when is lesbos a swear word or slur or any of that? I'm always calling myself a lesbo. Oh well.

### [Disputed Territories](https://www.geoguessr.com/maps/63e65287a029e9b998de764b)

Polygon map converted from Natural Earth's disputed areas data.

TODO: Version which takes out Israel/Taiwan/Sabah purely for the reason that they end up being selected too often.

### [Minor Islands](https://www.geoguessr.com/maps/6741eec96d68a18b54a71f74)

Polygon map converted from [Natural Earth](https://www.naturalearthdata.com/downloads/10m-physical-vectors/10m-minor-islands/)'s Minor Islands data, which includes all the islands that are <= 2 km² in size, which is probably a great hint for people who have an actual sense of scale unlike me and can intuitively figure out how big that is. Unfortunately the borders are not exact enough so some water trekkers show up. Boooo!!!
