---
title: inputEncryptedChat
description: inputEncryptedChat attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputEncryptedChat  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|chat\_id|[int](../types/int.md) | Yes|
|access\_hash|[long](../types/long.md) | Yes|



### Type: [InputEncryptedChat](../types/InputEncryptedChat.md)


### Example:

```php
$inputEncryptedChat = ['_' => 'inputEncryptedChat', 'chat_id' => int, 'access_hash' => long];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputEncryptedChat", "chat_id": int, "access_hash": long}
```


Or, if you're into Lua:

```lua
inputEncryptedChat={_='inputEncryptedChat', chat_id=int, access_hash=long}

```


