---
title: nearestDc
description: nearestDc attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: nearestDc  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|country|[string](../types/string.md) | Yes|
|this\_dc|[int](../types/int.md) | Yes|
|nearest\_dc|[int](../types/int.md) | Yes|



### Type: [NearestDc](../types/NearestDc.md)


### Example:

```php
$nearestDc = ['_' => 'nearestDc', 'country' => 'string', 'this_dc' => int, 'nearest_dc' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "nearestDc", "country": "string", "this_dc": int, "nearest_dc": int}
```


Or, if you're into Lua:

```lua
nearestDc={_='nearestDc', country='string', this_dc=int, nearest_dc=int}

```


