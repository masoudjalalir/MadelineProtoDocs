---
title: help.support
description: help_support attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: help.support  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|phone\_number|[string](../types/string.md) | Yes|
|user|[User](../types/User.md) | Optional|



### Type: [help\_Support](../types/help_Support.md)


### Example:

```php
$help_support = ['_' => 'help.support', 'phone_number' => 'string', 'user' => User];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "help.support", "phone_number": "string", "user": User}
```


Or, if you're into Lua:

```lua
help_support={_='help.support', phone_number='string', user=User}

```


