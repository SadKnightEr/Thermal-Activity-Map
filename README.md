# Thermal-Activity-Map
It is a pet project based on one technical exercise. This solution can help to build a graphical view of thermal data.
___
The solution forms a map of thermal activity for every country.

Country codes set in the file [js/country_code.json](https://github.com/sadknighter/sadknighter.github.io/blob/master/js/country_code.json).
Format of file:
```
{
	...
 	"EU":"EUROPEAN UNION",
	"SV":"EL SALVADOR",
	"GQ":"EQUATORIAL GUINEA",
	"ER":"ERITREA",
	"EE":"ESTONIA",
	...
}
```
___

The Values of thermal activity reads from a file [js/data.json](https://github.com/sadknighter/sadknighter.github.io/blob/master/js/data.json).

Format of file:
```
[
	...
	{ "count_dtime" : 1051, "country" : "US" },
	...
]
```

The 'count_dtime' value influences the color of the current country.

DEMO:  [sadknighter.github.io](https://sadknighter.github.io/)
