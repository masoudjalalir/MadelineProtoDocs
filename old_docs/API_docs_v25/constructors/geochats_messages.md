---
title: geochats.messages
description: geochats_messages attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: geochats.messages  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|messages|Array of [GeoChatMessage](../types/GeoChatMessage.md) | Yes|
|chats|Array of [Chat](../types/Chat.md) | Yes|
|users|Array of [User](../types/User.md) | Yes|



### Type: [geochats\_Messages](../types/geochats_Messages.md)


### Example:

```php
$geochats_messages = ['_' => 'geochats.messages', 'messages' => [GeoChatMessage, GeoChatMessage], 'chats' => [Chat, Chat], 'users' => [User, User]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "geochats.messages", "messages": [GeoChatMessage], "chats": [Chat], "users": [User]}
```


Or, if you're into Lua:

```lua
geochats_messages={_='geochats.messages', messages={GeoChatMessage}, chats={Chat}, users={User}}

```


