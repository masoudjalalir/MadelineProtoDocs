---
title: channelForbidden
description: channelForbidden attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: channelForbidden  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|broadcast|[Bool](../types/Bool.md) | Optional|
|megagroup|[Bool](../types/Bool.md) | Optional|
|id|[int](../types/int.md) | Yes|
|access\_hash|[long](../types/long.md) | Yes|
|title|[string](../types/string.md) | Yes|
|until\_date|[int](../types/int.md) | Optional|



### Type: [Chat](../types/Chat.md)


### Example:

```php
$channelForbidden = ['_' => 'channelForbidden', 'broadcast' => Bool, 'megagroup' => Bool, 'id' => int, 'access_hash' => long, 'title' => 'string', 'until_date' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "channelForbidden", "broadcast": Bool, "megagroup": Bool, "id": int, "access_hash": long, "title": "string", "until_date": int}
```


Or, if you're into Lua:

```lua
channelForbidden={_='channelForbidden', broadcast=Bool, megagroup=Bool, id=int, access_hash=long, title='string', until_date=int}

```


