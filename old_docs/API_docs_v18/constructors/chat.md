---
title: chat
description: chat attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: chat  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[int](../types/int.md) | Yes|
|title|[string](../types/string.md) | Yes|
|photo|[ChatPhoto](../types/ChatPhoto.md) | Optional|
|participants\_count|[int](../types/int.md) | Yes|
|date|[int](../types/int.md) | Yes|
|left|[Bool](../types/Bool.md) | Yes|
|version|[int](../types/int.md) | Yes|



### Type: [Chat](../types/Chat.md)


### Example:

```php
$chat = ['_' => 'chat', 'id' => int, 'title' => 'string', 'photo' => ChatPhoto, 'participants_count' => int, 'date' => int, 'left' => Bool, 'version' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "chat", "id": int, "title": "string", "photo": ChatPhoto, "participants_count": int, "date": int, "left": Bool, "version": int}
```


Or, if you're into Lua:

```lua
chat={_='chat', id=int, title='string', photo=ChatPhoto, participants_count=int, date=int, left=Bool, version=int}

```


