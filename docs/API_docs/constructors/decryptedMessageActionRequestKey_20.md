---
title: decryptedMessageActionRequestKey
description: decryptedMessageActionRequestKey attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: decryptedMessageActionRequestKey\_20  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|exchange\_id|[long](../types/long.md) | Yes|
|g\_a|[bytes](../types/bytes.md) | Yes|



### Type: [DecryptedMessageAction](../types/DecryptedMessageAction.md)


### Example:

```php
$decryptedMessageActionRequestKey_20 = ['_' => 'decryptedMessageActionRequestKey', 'exchange_id' => long, 'g_a' => 'bytes'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "decryptedMessageActionRequestKey", "exchange_id": long, "g_a": {"_": "bytes", "bytes":"base64 encoded bytes"}}
```


Or, if you're into Lua:

```lua
decryptedMessageActionRequestKey_20={_='decryptedMessageActionRequestKey', exchange_id=long, g_a='bytes'}

```


