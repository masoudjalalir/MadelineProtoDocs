---
title: messages.chatsSlice
description: messages_chatsSlice attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: messages.chatsSlice  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|count|[int](../types/int.md) | Yes|
|chats|Array of [Chat](../types/Chat.md) | Yes|



### Type: [messages\_Chats](../types/messages_Chats.md)


### Example:

```php
$messages_chatsSlice = ['_' => 'messages.chatsSlice', 'count' => int, 'chats' => [Chat, Chat]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "messages.chatsSlice", "count": int, "chats": [Chat]}
```


Or, if you're into Lua:

```lua
messages_chatsSlice={_='messages.chatsSlice', count=int, chats={Chat}}

```


