# AmiGo Deep Link Test
> [amigo://survey/web/surveymonkey/RJ9XKZM](amigo://survey/web/surveymonkey/RJ9XKZM)
> [amigo://survey/app/surveymonkey/RJ9XKZM](amigo://survey/app/surveymonkey/RJ9XKZM)

[< Back](README.md)

## Home Screen

> [amigo://](amigo://)

> [https://amigo.tomtom.com/](https://amigo.tomtom.com/)

## Location Panel

`Parameters - action=details, latitude, longitude, desitnationName, destinationAddress`

### From lat/lon only

> [amigo://map/detail?latitude=51.5014&longitude=-0.1419](amigo://map/detail?latitude=51.5014&longitude=-0.1419)

> [https://amigo.tomtom.com/map/detail?latitude=51.5014&longitude=-0.1419](https://amigo.tomtom.com/map/detail?latitude=51.5014&longitude=-0.1419)

### From addressString only

*This will follow same format check as Calendar and fall back to search if not a valid address*

> [amigo://map/detail?destinationAddress=Buckingham Palace, London, UK](amigo://map/detail?destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK)

> [https://amigo.tomtom.com/map/detail?destinationAddress=Buckingham Palace, London, UK]([amigo://](https://amigo.tomtom.com/)map/detail?destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK)

### From addressString only (with custom display name)

[amigo://map/detail?destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](amigo://map/detail?destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)

[https://amigo.tomtom.com/map/detail?destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](https://amigo.tomtom.com/map/detail?destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)

### From lat/lon with addressString and/or custom display

> [amigo://map/detail?latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](amigo://map/detail?latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)

> [https://amigo.tomtom.com/map/detail?latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](https://amigo.tomtom.com/map/detail?latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)

## Search Results page

`Parameters - action=search, searchText`

### Search for "Supermarket"
>[amigo://map/search?searchText=Supermarkets](amigo://map/search?searchText=Supermarkets)

>[https://amigo.tomtom.com/map/search?searchText=Supermarkets](https://amigo.tomtom.com/map/search?searchText=Supermarkets)

### Search for "TomTom London"
>[amigo://map/search?searchText=TomTom London](amigo://map/search?searchText=TomTom%20London)

> [https://amigo.tomtom.com/map/search?searchText=TomTom London](https://amigo.tomtom.com/map/search?searchText=TomTom%20London)

### Search for "Parking"
>[amigo://map/search/?poiCategoryGroup=poi_parking](amigo://map/search/?poiCategoryGroup=poi_parking)

> [https://amigo.tomtom.com/map/search?poiCategoryGroup=poi_parking](https://amigo.tomtom.com/map/search?poiCategoryGroup=poi_parking)

## Menu → My Places

> [amigo://my-places](amigo://my-places)

>[https://amigo.tomtom.com/my-places](https://amigo.tomtom.com/my-places)

## Menu → Settings

> [amigo://settings](amigo://settings)

> [https://amigo.tomtom.com/settings](https://amigo.tomtom.com/settings)

## Menu → Support

> [amigo://support](amigo://support)

> [https://amigo.tomtom.com/support](https://amigo.tomtom.com/support)

## Menu → Share

> [amigo://share](amigo://share)

> [https://amigo.tomtom.com/share](https://amigo.tomtom.com/share)

## Menu → Support → About

> [amigo://about](amigo://about)

> [https://amigo.tomtom.com/about](https://amigo.tomtom.com/about)

## Menu → Privacy

> [amigo://privacy](amigo://privacy)

> [https://amigo.tomtom.com/privacy](https://amigo.tomtom.com/privacy)

## Menu → Rate (Does not work on emulators)

> [amigo://rate](amigo://rate)

> [https://amigo.tomtom.com/rate](https://amigo.tomtom.com/rate)

# @todo
<del>

## Land people to a bounding box

`Parameters - action=focus, latitude, longitude, desitnationName, destinationAddress`

### From lat/lon only

[amigo://map/focus?latitude=51.5014&longitude=-0.1419](amigo://map/focus?latitude=51.5014&longitude=-0.1419)

### From addressString only

*This will follow same format check as Calendar and fall back to search if not a valid address*

[amigo://map/focus?destinationAddress=Buckingham Palace, London, UK](amigo://map/focus?destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK)

### From addressString only with custom display name

[amigo://map/focus?destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](amigo://map/focus?destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)

### From lat/lon with addressString and/or custom display

[amigo://map/focus?latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](amigo://map/focus?latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)
<del>
