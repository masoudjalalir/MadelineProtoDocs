---
title: privacyValueAllowUsers
description: privacyValueAllowUsers attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: privacyValueAllowUsers  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|users|Array of [int](../types/int.md) | Yes|



### Type: [PrivacyRule](../types/PrivacyRule.md)


### Example:

```php
$privacyValueAllowUsers = ['_' => 'privacyValueAllowUsers', 'users' => [int, int]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "privacyValueAllowUsers", "users": [int]}
```


Or, if you're into Lua:

```lua
privacyValueAllowUsers={_='privacyValueAllowUsers', users={int}}

```


