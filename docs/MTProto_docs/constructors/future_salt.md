---
title: future_salt
description: future_salt attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: future\_salt  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|valid\_since|[int](../types/int.md) | Yes|
|valid\_until|[int](../types/int.md) | Yes|
|salt|[long](../types/long.md) | Yes|



### Type: [FutureSalt](../types/FutureSalt.md)


### Example:

```php
$future_salt = ['_' => 'future_salt', 'valid_since' => int, 'valid_until' => int, 'salt' => long];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "future_salt", "valid_since": int, "valid_until": int, "salt": long}
```


Or, if you're into Lua:

```lua
future_salt={_='future_salt', valid_since=int, valid_until=int, salt=long}

```


