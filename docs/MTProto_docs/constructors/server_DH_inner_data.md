---
title: server_DH_inner_data
description: server_DH_inner_data attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: server\_DH\_inner\_data  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|nonce|[int128](../types/int128.md) | Yes|
|server\_nonce|[int128](../types/int128.md) | Yes|
|g|[int](../types/int.md) | Yes|
|dh\_prime|[bytes](../types/bytes.md) | Yes|
|g\_a|[bytes](../types/bytes.md) | Yes|
|server\_time|[int](../types/int.md) | Yes|



### Type: [Server\_DH\_inner\_data](../types/Server_DH_inner_data.md)


### Example:

```php
$server_DH_inner_data = ['_' => 'server_DH_inner_data', 'nonce' => int128, 'server_nonce' => int128, 'g' => int, 'dh_prime' => 'bytes', 'g_a' => 'bytes', 'server_time' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "server_DH_inner_data", "nonce": int128, "server_nonce": int128, "g": int, "dh_prime": {"_": "bytes", "bytes":"base64 encoded bytes"}, "g_a": {"_": "bytes", "bytes":"base64 encoded bytes"}, "server_time": int}
```


Or, if you're into Lua:

```lua
server_DH_inner_data={_='server_DH_inner_data', nonce=int128, server_nonce=int128, g=int, dh_prime='bytes', g_a='bytes', server_time=int}

```


