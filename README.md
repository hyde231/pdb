# pdb

This is an attempt to combine pornstar identities that have different names according to different sources. By using heuristics on names and aliases used, there should be a way to find similarities and therefore link duplicates.

Sources scraped and used as if Aug 05th, 2020:
- https://www.freeones.xxx/ : 50315 entries
- https://www.indexxx.com/ : 51355 entries + aliases
- https://thenude.com : 39060 entries + aliases
- https://www.eurobabeindex.com/: 5118 entries + aliases
- https://www.pornpics.com/ : 18950 entries
- https://www.babepedia.com/ : 29950 entries
- http://www.boobpedia.com/ : 10828 entries (pornstarts only)
- https://www.adultdvdempire.com/ : 11282 entries (female only)

The challenge is to create a combined list, that does not include 220k+ entries but groups as many duplictes as possible.

## Example of the combined data
'ids' are the unique part of urls from scraped sources
'names' are names and aliases used according to the different dources

In the example below, the performer is listed as 'abigaile' on eurobabeindex, but as 'abigaile-johnson' on indexxx and freeones. In a similar way all the names and aliases are stored with the mentioning source attached.
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
			"pornpics"
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
			"pornpics"
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
			"X-Art"
		],
		"Abby A": [
			"thenude"
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
