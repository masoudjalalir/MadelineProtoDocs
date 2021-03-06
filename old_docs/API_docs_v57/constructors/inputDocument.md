---
title: inputDocument
description: inputDocument attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputDocument  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[long](../types/long.md) | Yes|
|access\_hash|[long](../types/long.md) | Yes|



### Type: [InputDocument](../types/InputDocument.md)


### Example:

```php
$inputDocument = ['_' => 'inputDocument', 'id' => long, 'access_hash' => long];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputDocument", "id": long, "access_hash": long}
```


Or, if you're into Lua:

```lua
inputDocument={_='inputDocument', id=long, access_hash=long}

```


