---
title: updateBotInlineQuery
description: updateBotInlineQuery attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateBotInlineQuery  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|query\_id|[long](../types/long.md) | Yes|
|user\_id|[int](../types/int.md) | Yes|
|query|[string](../types/string.md) | Yes|
|geo|[GeoPoint](../types/GeoPoint.md) | Optional|
|offset|[string](../types/string.md) | Yes|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateBotInlineQuery = ['_' => 'updateBotInlineQuery', 'query_id' => long, 'user_id' => int, 'query' => 'string', 'geo' => GeoPoint, 'offset' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateBotInlineQuery", "query_id": long, "user_id": int, "query": "string", "geo": GeoPoint, "offset": "string"}
```


Or, if you're into Lua:

```lua
updateBotInlineQuery={_='updateBotInlineQuery', query_id=long, user_id=int, query='string', geo=GeoPoint, offset='string'}

```


