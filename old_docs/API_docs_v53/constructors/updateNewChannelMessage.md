---
title: updateNewChannelMessage
description: updateNewChannelMessage attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateNewChannelMessage  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|message|[Message](../types/Message.md) | Optional|
|pts|[int](../types/int.md) | Yes|
|pts\_count|[int](../types/int.md) | Yes|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateNewChannelMessage = ['_' => 'updateNewChannelMessage', 'message' => Message, 'pts' => int, 'pts_count' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateNewChannelMessage", "message": Message, "pts": int, "pts_count": int}
```


Or, if you're into Lua:

```lua
updateNewChannelMessage={_='updateNewChannelMessage', message=Message, pts=int, pts_count=int}

```


