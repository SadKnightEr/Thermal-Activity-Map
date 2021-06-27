# Thermal-Activity-Map
Pet-проект оставшийся после одного из технических заданий.
___
Формирует карту термической активности в каждой стране мира.

Коды стран задаются в файле [js/country_code.json](https://github.com/sadknighter/sadknighter.github.io/blob/master/js/country_code.json).
Формат файла:
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

Значения термической активности задаются в файле [js/data.json](https://github.com/sadknighter/sadknighter.github.io/blob/master/js/data.json).

Пример:
```
[
	...
	{ "count_dtime" : 1051, "country" : "US" },
	...
]
```

Величина count_dtime влияет на цветовую раскраску страны.

DEMO:  [sadknighter.github.io](https://sadknighter.github.io/)