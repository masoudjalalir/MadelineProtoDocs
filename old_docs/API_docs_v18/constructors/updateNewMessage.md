---
title: updateNewMessage
description: updateNewMessage attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateNewMessage  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|message|[Message](../types/Message.md) | Optional|
|pts|[int](../types/int.md) | Yes|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateNewMessage = ['_' => 'updateNewMessage', 'message' => Message, 'pts' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateNewMessage", "message": Message, "pts": int}
```


Or, if you're into Lua:

```lua
updateNewMessage={_='updateNewMessage', message=Message, pts=int}

```


