---
title: userProfilePhoto
description: userProfilePhoto attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: userProfilePhoto  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|photo\_id|[long](../types/long.md) | Yes|
|photo\_small|[FileLocation](../types/FileLocation.md) | Yes|
|photo\_big|[FileLocation](../types/FileLocation.md) | Yes|



### Type: [UserProfilePhoto](../types/UserProfilePhoto.md)


### Example:

```php
$userProfilePhoto = ['_' => 'userProfilePhoto', 'photo_id' => long, 'photo_small' => FileLocation, 'photo_big' => FileLocation];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "userProfilePhoto", "photo_id": long, "photo_small": FileLocation, "photo_big": FileLocation}
```


Or, if you're into Lua:

```lua
userProfilePhoto={_='userProfilePhoto', photo_id=long, photo_small=FileLocation, photo_big=FileLocation}

```


