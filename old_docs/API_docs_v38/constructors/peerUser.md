---
title: peerUser
description: peerUser attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: peerUser  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|user\_id|[int](../types/int.md) | Yes|



### Type: [Peer](../types/Peer.md)


### Example:

```php
$peerUser = ['_' => 'peerUser', 'user_id' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "peerUser", "user_id": int}
```


Or, if you're into Lua:

```lua
peerUser={_='peerUser', user_id=int}

```


