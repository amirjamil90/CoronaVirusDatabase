# Matno Contest - Back-End Programming

# Corona Virus Database

A repository for analyzing references and database of `gisanddata.maps.arcgis.com` website for Corona Virus.

# Corona Virus

Website: https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6

Downloadable database: GitHub: [Here](https://github.com/CSSEGISandData/COVID-19/tree/master/archived_data).


There is a `csv` files for every days. e.g: https://github.com/CSSEGISandData/COVID-19/blob/master/archived_data/test/02-26-2020.csv


But main site has not get data from that.

By checking main website, i did check all requests and links:

Finaly i found this:

https://services1.arcgis.com/0MSEUqKaxRlEPj5g/arcgis/rest/services/ncov_cases/FeatureServer/2/query?f=json&where=Confirmed%20%3E%200&returnGeometry=false&spatialRel=esriSpatialRelIntersects&outFields=*&orderByFields=Confirmed%20desc&resultOffset=0&resultRecordCount=1000&cacheHint=true

But you can see all requests as HAR format at [here](requests.har).
