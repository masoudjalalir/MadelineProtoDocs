---
title: document
description: document attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: document  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[long](../types/long.md) | Yes|
|access\_hash|[long](../types/long.md) | Yes|
|date|[int](../types/int.md) | Yes|
|mime\_type|[string](../types/string.md) | Yes|
|size|[int](../types/int.md) | Yes|
|thumb|[PhotoSize](../types/PhotoSize.md) | Optional|
|dc\_id|[int](../types/int.md) | Yes|
|attributes|Array of [DocumentAttribute](../types/DocumentAttribute.md) | Yes|



### Type: [Document](../types/Document.md)


### Example:

```php
$document = ['_' => 'document', 'id' => long, 'access_hash' => long, 'date' => int, 'mime_type' => 'string', 'size' => int, 'thumb' => PhotoSize, 'dc_id' => int, 'attributes' => [DocumentAttribute, DocumentAttribute]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "document", "id": long, "access_hash": long, "date": int, "mime_type": "string", "size": int, "thumb": PhotoSize, "dc_id": int, "attributes": [DocumentAttribute]}
```


Or, if you're into Lua:

```lua
document={_='document', id=long, access_hash=long, date=int, mime_type='string', size=int, thumb=PhotoSize, dc_id=int, attributes={DocumentAttribute}}

```


