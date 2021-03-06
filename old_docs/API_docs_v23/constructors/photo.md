---
title: photo
description: photo attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: photo  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[long](../types/long.md) | Yes|
|access\_hash|[long](../types/long.md) | Yes|
|user\_id|[int](../types/int.md) | Yes|
|date|[int](../types/int.md) | Yes|
|caption|[string](../types/string.md) | Yes|
|geo|[GeoPoint](../types/GeoPoint.md) | Optional|
|sizes|Array of [PhotoSize](../types/PhotoSize.md) | Yes|



### Type: [Photo](../types/Photo.md)


### Example:

```php
$photo = ['_' => 'photo', 'id' => long, 'access_hash' => long, 'user_id' => int, 'date' => int, 'caption' => 'string', 'geo' => GeoPoint, 'sizes' => [PhotoSize, PhotoSize]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "photo", "id": long, "access_hash": long, "user_id": int, "date": int, "caption": "string", "geo": GeoPoint, "sizes": [PhotoSize]}
```


Or, if you're into Lua:

```lua
photo={_='photo', id=long, access_hash=long, user_id=int, date=int, caption='string', geo=GeoPoint, sizes={PhotoSize}}

```


