---
title: inputPeerNotifySettings
description: inputPeerNotifySettings attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputPeerNotifySettings  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|show\_previews|[Bool](../types/Bool.md) | Optional|
|silent|[Bool](../types/Bool.md) | Optional|
|mute\_until|[int](../types/int.md) | Optional|
|sound|[string](../types/string.md) | Optional|



### Type: [InputPeerNotifySettings](../types/InputPeerNotifySettings.md)


### Example:

```php
$inputPeerNotifySettings = ['_' => 'inputPeerNotifySettings', 'show_previews' => Bool, 'silent' => Bool, 'mute_until' => int, 'sound' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputPeerNotifySettings", "show_previews": Bool, "silent": Bool, "mute_until": int, "sound": "string"}
```


Or, if you're into Lua:

```lua
inputPeerNotifySettings={_='inputPeerNotifySettings', show_previews=Bool, silent=Bool, mute_until=int, sound='string'}

```


