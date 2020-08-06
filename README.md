# pdb - NSFW!
Listing 129,258 individual pornstars with 290,856 aliases, based on 235,839 raw entries scraped from 9 different soruces.

## Purpose
This is an attempt to combine female pornstar identities that have different names according to different sources. By using heuristics on names and aliases used, there should be a way to find similarities and therefore link duplicates together.

Sources scraped and used as of Aug 06th, 2020:
- https://www.freeones.xxx/ : 50315 entries
- https://www.indexxx.com/ : 51355 entries (+ aliases)
- https://thenude.com : 39060 entries (+ aliases)
- https://www.eurobabeindex.com/: 5118 entries (+ aliases)
- https://www.pornpics.com/ : 18950 entries
- https://www.babepedia.com/ : 29950 entries
- http://www.boobpedia.com/ : 10828 entries (pornstars only)
- https://www.adultdvdempire.com/ : 11282 entries (female only)
- hhtps://metadataapi.net/ : 18981 entries (female only)

The challenge is to create a combined list, that does not include 235k+ entries but groups as many duplictes as possible. The current combined file provided as ziped json contains ~129k entries with references to the sources listed above. The sum of all aliases is around  

## Method of aggregation
...to be updated...

## Example of the combined data
In the example below, the performer is listed with the id 'abigaile' on eurobabeindex, but as 'abigaile-johnson' on indexxx and freeones. In a similar way all the names and aliases are stored with the mentioning source attached. 

- 'ids' lists the unique part of urls from scraped sources. For example an id of "Abigaile Johnson_16404" from thenude refers to the uinque page https://www.thenude.com/Abigaile%20Johnson_16404.htm
- 'names' collects names and aliases used according to the different sources

```
{
	"uuid": "1b8c5dba-a55d-430c-938e-aa22482c7759",
	"ids": {
		"Abigaile Johnson_16404": [
			"thenude"
		],
		"abigaile": [
			"eurobabeindex"
		],
		"abigaile-johnson": [
			"indexxx",
			"freeones"
		],
		"abigaile+johnson": [
			"pornpics"
		],
		"Abigaile_Johnson": [
			"babepedia"
		],
		"/629071/abigaile-johnson-pornstars": [
			"adultempire"
		],
		"abby-a": [
			"tpdb"
		]
	},
	"names": {
		"Abigaile Johnson": [
			"thenude",
			"eurobabeindex",
			"indexxx",
			"18videoz.com",
			"Babes",
			"Blacks On Blondes",
			"Brazzers",
			"DDF Prod Network",
			"DogFart Network",
			"Nubile Films",
			"Nubiles",
			"Porn Pros Network 2",
			"Passion-HD",
			"Porn Pros Network",
			"Porn World",
			"Teen Fidelity",
			"freeones",
			"pornpics",
			"babepedia",
			"adultempire"
		],
		"Abigaile": [
			"thenude",
			"eurobabeindex",
			"indexxx",
			"18videoz.com",
			"Babes",
			"Blacks On Blondes",
			"Brazzers",
			"DDF Prod Network",
			"DogFart Network",
			"Karups",
			"Nubile Films",
			"Nubiles",
			"Porn Pros Network 2",
			"Passion-HD",
			"Porn Pros Network",
			"Porn World",
			"Reality Kings",
			"Teen Fidelity",
			"freeones",
			"pornpics",
			"babepedia",
			"adultempire"
		],
		"Abagaile Johnson": [
			"thenude",
			"BangBros Network",
			"indexxx",
			"Monsters of Cock"
		],
		"Abagaile": [
			"thenude",
			"BangBros Network",
			"indexxx",
			"Monsters of Cock"
		],
		"Abby": [
			"thenude",
			"eurobabeindex",
			"Club Seventeen",
			"indexxx",
			"X-Art",
			"tpdb"
		],
		"Abby A": [
			"thenude",
			"tpdb"
		],
		"Abigail": [
			"thenude",
			"eurobabeindex",
			"Joy Mii"
		],
		"Abigail Johnson": [
			"thenude",
			"eurobabeindex"
		],
		"Abigale": [
			"thenude",
			"eurobabeindex",
			"indexxx",
			"Mofos Network"
		],
		"Abigale Johnson": [
			"thenude",
			"eurobabeindex",
			"indexxx",
			"Mofos Network"
		],
		"Petty": [
			"thenude",
			"eurobabeindex",
			"indexxx"
		],
		"Pinky June": [
			"thenude"
		],
		"Pinky": [
			"thenude"
		],
		"Spunky": [
			"thenude",
			"eurobabeindex",
			"teenburg.com"
		],
		"Spunky Bee": [
			"thenude",
			"eurobabeindex"
		],
		"Veronika": [
			"thenude",
			"eurobabeindex",
			"indexxx"
		],
		"Veronika A": [
			"thenude"
		],
		"Veronika W": [
			"thenude",
			"indexxx"
		],
		"Abi": [
			"eurobabeindex"
		],
		"Abigaile J": [
			"eurobabeindex"
		],
		"Abigalie": [
			"eurobabeindex"
		],
		"Barbara": [
			"eurobabeindex"
		],
		"Rose": [
			"eurobabeindex"
		],
		"Abigiale Johnson": [
			"indexxx"
		],
		"Abigiale": [
			"indexxx"
		]
	},
	"dataRef": {}
}
```

## Future use of the data
The data allows to search for names / aliases and get references to profile pages of numerous aggregators for identification purposes.

If individual data can be added, the grouping algorithm could be much more precise and allow for true uuids.
