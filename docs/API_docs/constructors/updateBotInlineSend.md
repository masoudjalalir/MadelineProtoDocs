---
title: updateBotInlineSend
description: updateBotInlineSend attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateBotInlineSend  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|user\_id|[int](../types/int.md) | Yes|
|query|[string](../types/string.md) | Yes|
|geo|[GeoPoint](../types/GeoPoint.md) | Optional|
|id|[string](../types/string.md) | Yes|
|msg\_id|[InputBotInlineMessageID](../types/InputBotInlineMessageID.md) | Optional|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateBotInlineSend = ['_' => 'updateBotInlineSend', 'user_id' => int, 'query' => 'string', 'geo' => GeoPoint, 'id' => 'string', 'msg_id' => InputBotInlineMessageID];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateBotInlineSend", "user_id": int, "query": "string", "geo": GeoPoint, "id": "string", "msg_id": InputBotInlineMessageID}
```


Or, if you're into Lua:

```lua
updateBotInlineSend={_='updateBotInlineSend', user_id=int, query='string', geo=GeoPoint, id='string', msg_id=InputBotInlineMessageID}

```


