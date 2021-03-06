---
title: updateDeleteChannelMessages
description: updateDeleteChannelMessages attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateDeleteChannelMessages  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|peer|[Peer](../types/Peer.md) | Yes|
|messages|Array of [int](../types/int.md) | Yes|
|pts|[int](../types/int.md) | Yes|
|pts\_count|[int](../types/int.md) | Yes|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateDeleteChannelMessages = ['_' => 'updateDeleteChannelMessages', 'peer' => Peer, 'messages' => [int, int], 'pts' => int, 'pts_count' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateDeleteChannelMessages", "peer": Peer, "messages": [int], "pts": int, "pts_count": int}
```


Or, if you're into Lua:

```lua
updateDeleteChannelMessages={_='updateDeleteChannelMessages', peer=Peer, messages={int}, pts=int, pts_count=int}

```


