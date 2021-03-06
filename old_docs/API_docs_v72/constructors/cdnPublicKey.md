---
title: cdnPublicKey
description: cdnPublicKey attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: cdnPublicKey  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|dc\_id|[int](../types/int.md) | Yes|
|public\_key|[string](../types/string.md) | Yes|



### Type: [CdnPublicKey](../types/CdnPublicKey.md)


### Example:

```php
$cdnPublicKey = ['_' => 'cdnPublicKey', 'dc_id' => int, 'public_key' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "cdnPublicKey", "dc_id": int, "public_key": "string"}
```


Or, if you're into Lua:

```lua
cdnPublicKey={_='cdnPublicKey', dc_id=int, public_key='string'}

```


