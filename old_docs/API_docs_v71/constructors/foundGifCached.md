---
title: foundGifCached
description: foundGifCached attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: foundGifCached  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|url|[string](../types/string.md) | Yes|
|photo|[Photo](../types/Photo.md) | Optional|
|document|[Document](../types/Document.md) | Optional|



### Type: [FoundGif](../types/FoundGif.md)


### Example:

```php
$foundGifCached = ['_' => 'foundGifCached', 'url' => 'string', 'photo' => Photo, 'document' => Document];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "foundGifCached", "url": "string", "photo": Photo, "document": Document}
```


Or, if you're into Lua:

```lua
foundGifCached={_='foundGifCached', url='string', photo=Photo, document=Document}

```


