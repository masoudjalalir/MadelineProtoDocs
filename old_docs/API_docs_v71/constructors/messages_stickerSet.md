---
title: messages.stickerSet
description: messages_stickerSet attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: messages.stickerSet  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|set|[StickerSet](../types/StickerSet.md) | Yes|
|packs|Array of [StickerPack](../types/StickerPack.md) | Yes|
|documents|Array of [Document](../types/Document.md) | Yes|



### Type: [messages\_StickerSet](../types/messages_StickerSet.md)


### Example:

```php
$messages_stickerSet = ['_' => 'messages.stickerSet', 'set' => StickerSet, 'packs' => [StickerPack, StickerPack], 'documents' => [Document, Document]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "messages.stickerSet", "set": StickerSet, "packs": [StickerPack], "documents": [Document]}
```


Or, if you're into Lua:

```lua
messages_stickerSet={_='messages.stickerSet', set=StickerSet, packs={StickerPack}, documents={Document}}

```


