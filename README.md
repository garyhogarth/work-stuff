# AmiGo Deep Link Test

## Home Screen
  [amigo://](amigo://)

## Land people to a bounding box

`Parameters - action=focus, latitude, longitude, desitnationName, destinationAddress`

### From lat/lon only

[amigo://map?action=focus&latitude=51.5014&longitude=-0.1419](amigo://map?action=focus&latitude=51.5014&longitude=-0.1419)

### From addressString only

*This will follow same format check as Calendar and fall back to search if not a valid address*

[amigo://map?action=focus&destinationAddress=Buckingham Palace, London, UK](amigo://map?action=focus&destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK)

### From addressString only with custom display name

[amigo://map?action=focus&destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](amigo://map?action=focus&destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)

### From lat/lon with addressString and/or custom display

[amigo://map?action=focus&latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](amigo://map?action=focus&latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)

## Location Panel

`Parameters - action=details, latitude, longitude, desitnationName, destinationAddress`

### From lat/lon only

[amigo://map?action=focus&latitude=51.5014&longitude=-0.1419](amigo://map?action=focus&latitude=51.5014&longitude=-0.1419)

### From addressString only

*This will follow same format check as Calendar and fall back to search if not a valid address*

[amigo://map?action=focus&destinationAddress=Buckingham Palace, London, UK](amigo://map?action=focus&destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK)

### From addressString only (with custom display name)

[amigo://map?action=focus&destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](amigo://map?action=focus&destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)

### From lat/lon with addressString and/or custom display

[amigo://map?action=focus&latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham Palace, London, UK&destinationName=Queen's House](amigo://map?action=focus&latitude=51.5014&longitude=-0.1419&destinationAddress=Buckingham%20Palace%2C%20London%2C%20UK&destinationName=Queen%27s%20House)

## Search Results page

`Parameters - action=search, searchText`

[amigo://map?action=search&searchText=Supermarkets](amigo://map?action=search&searchText=Supermarkets)

[amigo://map?action=search&searchText=TomTom London](amigo://map?action=search&searchText=TomTom%20London)

## Menu → My Places

[amigo://my-places](amigo://my-places)

## Menu → Settings

[amigo://settings](amigo://settings)

## Menu → Support

[amigo://support](amigo://support)

## Menu → Share

[amigo://share](amigo://share)

## Menu → Rate (Not working yet)

[amigo://rate](amigo://rate)

## Menu → Support → About

[amigo://about](amigo://about)

## Menu → Privacy

[amigo://privacy](amigo://privacy)
