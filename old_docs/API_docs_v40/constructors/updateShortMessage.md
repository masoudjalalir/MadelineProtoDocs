---
title: updateShortMessage
description: updateShortMessage attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateShortMessage  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[int](../types/int.md) | Yes|
|user\_id|[int](../types/int.md) | Yes|
|message|[string](../types/string.md) | Yes|
|pts|[int](../types/int.md) | Yes|
|pts\_count|[int](../types/int.md) | Yes|
|date|[int](../types/int.md) | Yes|
|fwd\_from\_id|[int](../types/int.md) | Optional|
|fwd\_date|[int](../types/int.md) | Optional|
|reply\_to\_msg\_id|[int](../types/int.md) | Optional|
|entities|Array of [MessageEntity](../types/MessageEntity.md) | Optional|



### Type: [Updates](../types/Updates.md)


### Example:

```php
$updateShortMessage = ['_' => 'updateShortMessage', 'id' => int, 'user_id' => int, 'message' => 'string', 'pts' => int, 'pts_count' => int, 'date' => int, 'fwd_from_id' => int, 'fwd_date' => int, 'reply_to_msg_id' => int, 'entities' => [MessageEntity, MessageEntity]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateShortMessage", "id": int, "user_id": int, "message": "string", "pts": int, "pts_count": int, "date": int, "fwd_from_id": int, "fwd_date": int, "reply_to_msg_id": int, "entities": [MessageEntity]}
```


Or, if you're into Lua:

```lua
updateShortMessage={_='updateShortMessage', id=int, user_id=int, message='string', pts=int, pts_count=int, date=int, fwd_from_id=int, fwd_date=int, reply_to_msg_id=int, entities={MessageEntity}}

```


