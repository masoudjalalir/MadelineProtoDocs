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
|longitude|[double](../types/double.md) | Yes|
|latitude|[double](../types/double.md) | Yes|



### Type: [GeoPoint](../types/GeoPoint.md)


### Example:

```php
$geoPoint = ['_' => 'geoPoint', 'longitude' => double, 'latitude' => double];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "geoPoint", "longitude": double, "latitude": double}
```


Or, if you're into Lua:

```lua
geoPoint={_='geoPoint', longitude=double, latitude=double}

```


