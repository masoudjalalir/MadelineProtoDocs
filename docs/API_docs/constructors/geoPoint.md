---
title: geoPoint
description: geoPoint attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: geoPoint  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|long|[double](../types/double.md) | Yes|
|lat|[double](../types/double.md) | Yes|
|access\_hash|[long](../types/long.md) | Yes|



### Type: [GeoPoint](../types/GeoPoint.md)


### Example:

```php
$geoPoint = ['_' => 'geoPoint', 'long' => double, 'lat' => double, 'access_hash' => long];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "geoPoint", "long": double, "lat": double, "access_hash": long}
```


Or, if you're into Lua:

```lua
geoPoint={_='geoPoint', long=double, lat=double, access_hash=long}

```


