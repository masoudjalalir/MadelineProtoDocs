---
title: inputMediaDocumentExternal
description: inputMediaDocumentExternal attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputMediaDocumentExternal  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|url|[string](../types/string.md) | Yes|
|caption|[string](../types/string.md) | Yes|



### Type: [InputMedia](../types/InputMedia.md)


### Example:

```php
$inputMediaDocumentExternal = ['_' => 'inputMediaDocumentExternal', 'url' => 'string', 'caption' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputMediaDocumentExternal", "url": "string", "caption": "string"}
```


Or, if you're into Lua:

```lua
inputMediaDocumentExternal={_='inputMediaDocumentExternal', url='string', caption='string'}

```


