---
title: updateBotShippingQuery
description: updateBotShippingQuery attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateBotShippingQuery  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|query\_id|[long](../types/long.md) | Yes|
|user\_id|[int](../types/int.md) | Yes|
|payload|[bytes](../types/bytes.md) | Yes|
|shipping\_address|[PostAddress](../types/PostAddress.md) | Yes|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateBotShippingQuery = ['_' => 'updateBotShippingQuery', 'query_id' => long, 'user_id' => int, 'payload' => 'bytes', 'shipping_address' => PostAddress];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateBotShippingQuery", "query_id": long, "user_id": int, "payload": {"_": "bytes", "bytes":"base64 encoded bytes"}, "shipping_address": PostAddress}
```


Or, if you're into Lua:

```lua
updateBotShippingQuery={_='updateBotShippingQuery', query_id=long, user_id=int, payload='bytes', shipping_address=PostAddress}

```


