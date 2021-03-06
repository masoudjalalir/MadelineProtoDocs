---
title: updateUserName
description: updateUserName attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateUserName  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|user\_id|[int](../types/int.md) | Yes|
|first\_name|[string](../types/string.md) | Yes|
|last\_name|[string](../types/string.md) | Yes|
|username|[string](../types/string.md) | Yes|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateUserName = ['_' => 'updateUserName', 'user_id' => int, 'first_name' => 'string', 'last_name' => 'string', 'username' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateUserName", "user_id": int, "first_name": "string", "last_name": "string", "username": "string"}
```


Or, if you're into Lua:

```lua
updateUserName={_='updateUserName', user_id=int, first_name='string', last_name='string', username='string'}

```


