---
title: updateReadChannelOutbox
description: updateReadChannelOutbox attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateReadChannelOutbox  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|channel\_id|[int](../types/int.md) | Yes|
|max\_id|[int](../types/int.md) | Yes|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateReadChannelOutbox = ['_' => 'updateReadChannelOutbox', 'channel_id' => int, 'max_id' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateReadChannelOutbox", "channel_id": int, "max_id": int}
```


Or, if you're into Lua:

```lua
updateReadChannelOutbox={_='updateReadChannelOutbox', channel_id=int, max_id=int}

```


