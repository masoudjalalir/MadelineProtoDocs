---
title: messages.stickerSetInstallResultArchive
description: messages_stickerSetInstallResultArchive attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: messages.stickerSetInstallResultArchive  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|sets|Array of [StickerSetCovered](../types/StickerSetCovered.md) | Yes|



### Type: [messages\_StickerSetInstallResult](../types/messages_StickerSetInstallResult.md)


### Example:

```php
$messages_stickerSetInstallResultArchive = ['_' => 'messages.stickerSetInstallResultArchive', 'sets' => [StickerSetCovered, StickerSetCovered]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "messages.stickerSetInstallResultArchive", "sets": [StickerSetCovered]}
```


Or, if you're into Lua:

```lua
messages_stickerSetInstallResultArchive={_='messages.stickerSetInstallResultArchive', sets={StickerSetCovered}}

```


