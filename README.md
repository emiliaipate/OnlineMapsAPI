# OnlineMapsAPI

1. To use the TomTom example, you must first obtain a key from developer.tomtom.com for TomTom OnlineMaps API and enter it where it says "ENTER-API-KEY"
2. To use the OpenStreet example, you must obtain a key from mapbox https://www.mapbox.com/account/apps/
3. The Nokia HERE example uses their demo appID and appCode available on the HERE API Explorer

Notes:
- the tomtom maps contain a better road network than HERE and OpenStreetMaps
- OpenStreetMaps contain better terrain (eg: river Cracau is missing from TomTom and HERE)
- Nokia HERE gives access to their Customer Integration Testing environment which might have lower quality maps
- OpenStreetMaps provides access to their production environment
- attribution can be provided through leafletjs library directly
