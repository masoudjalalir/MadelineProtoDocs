---
title: inputFile
description: inputFile attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputFile  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[long](../types/long.md) | Yes|
|parts|[int](../types/int.md) | Yes|
|name|[string](../types/string.md) | Yes|
|md5\_checksum|[string](../types/string.md) | Yes|



### Type: [InputFile](../types/InputFile.md)


### Example:

```php
$inputFile = ['_' => 'inputFile', 'id' => long, 'parts' => int, 'name' => 'string', 'md5_checksum' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputFile", "id": long, "parts": int, "name": "string", "md5_checksum": "string"}
```


Or, if you're into Lua:

```lua
inputFile={_='inputFile', id=long, parts=int, name='string', md5_checksum='string'}

```


