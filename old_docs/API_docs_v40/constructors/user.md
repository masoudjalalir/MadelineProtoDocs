---
title: user
description: user attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: user  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[int](../types/int.md) | Yes|
|access\_hash|[long](../types/long.md) | Optional|
|first\_name|[string](../types/string.md) | Optional|
|last\_name|[string](../types/string.md) | Optional|
|username|[string](../types/string.md) | Optional|
|phone|[string](../types/string.md) | Optional|
|photo|[UserProfilePhoto](../types/UserProfilePhoto.md) | Optional|
|status|[UserStatus](../types/UserStatus.md) | Optional|
|bot\_info\_version|[int](../types/int.md) | Optional|



### Type: [User](../types/User.md)


### Example:

```php
$user = ['_' => 'user', 'id' => int, 'access_hash' => long, 'first_name' => 'string', 'last_name' => 'string', 'username' => 'string', 'phone' => 'string', 'photo' => UserProfilePhoto, 'status' => UserStatus, 'bot_info_version' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "user", "id": int, "access_hash": long, "first_name": "string", "last_name": "string", "username": "string", "phone": "string", "photo": UserProfilePhoto, "status": UserStatus, "bot_info_version": int}
```


Or, if you're into Lua:

```lua
user={_='user', id=int, access_hash=long, first_name='string', last_name='string', username='string', phone='string', photo=UserProfilePhoto, status=UserStatus, bot_info_version=int}

```


