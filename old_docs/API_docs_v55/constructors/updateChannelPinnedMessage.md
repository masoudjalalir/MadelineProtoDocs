---
title: updateChannelPinnedMessage
description: updateChannelPinnedMessage attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateChannelPinnedMessage  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|channel\_id|[int](../types/int.md) | Yes|
|id|[int](../types/int.md) | Yes|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateChannelPinnedMessage = ['_' => 'updateChannelPinnedMessage', 'channel_id' => int, 'id' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateChannelPinnedMessage", "channel_id": int, "id": int}
```


Or, if you're into Lua:

```lua
updateChannelPinnedMessage={_='updateChannelPinnedMessage', channel_id=int, id=int}

```


