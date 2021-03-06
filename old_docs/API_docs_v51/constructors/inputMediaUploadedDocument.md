---
title: inputMediaUploadedDocument
description: inputMediaUploadedDocument attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputMediaUploadedDocument  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|file|[File path or InputFile](../types/InputFile.md) | Yes|
|mime\_type|[string](../types/string.md) | Optional|
|attributes|Array of [DocumentAttribute](../types/DocumentAttribute.md) | Yes|
|caption|[string](../types/string.md) | Yes|



### Type: [InputMedia](../types/InputMedia.md)


### Example:

```php
$inputMediaUploadedDocument = ['_' => 'inputMediaUploadedDocument', 'file' => InputFile, 'mime_type' => 'string', 'attributes' => [DocumentAttribute, DocumentAttribute], 'caption' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputMediaUploadedDocument", "file": InputFile, "mime_type": "string", "attributes": [DocumentAttribute], "caption": "string"}
```


Or, if you're into Lua:

```lua
inputMediaUploadedDocument={_='inputMediaUploadedDocument', file=InputFile, mime_type='string', attributes={DocumentAttribute}, caption='string'}

```


