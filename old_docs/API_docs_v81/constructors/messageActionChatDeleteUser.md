---
title: messageActionChatDeleteUser
description: messageActionChatDeleteUser attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: messageActionChatDeleteUser  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|user\_id|[int](../types/int.md) | Yes|



### Type: [MessageAction](../types/MessageAction.md)


### Example:

```php
$messageActionChatDeleteUser = ['_' => 'messageActionChatDeleteUser', 'user_id' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "messageActionChatDeleteUser", "user_id": int}
```


Or, if you're into Lua:

```lua
messageActionChatDeleteUser={_='messageActionChatDeleteUser', user_id=int}

```


