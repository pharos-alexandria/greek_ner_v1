



# Place data

- About: https://pleiades.stoa.org/downloads
- Download URL: http://atlantides.org/downloads/pleiades/json/pleiades-places-latest.json.gz
- `curl -O http://atlantides.org/downloads/pleiades/json/pleiades-places-latest.json.gz`  # 25 MB
- `gzip -d pleiades-places-latest.json.gz`  # 441 MB


```
In [7]: with open("pleiades-places-latest.json", "rb") as fo:
   ...:     pleiades = json.load(fo)
   ...: 

>>> len(pleiades["@graph"])
37500


```