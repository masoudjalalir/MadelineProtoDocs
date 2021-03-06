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
|mute\_until|[int](../types/int.md) | Yes|
|sound|[string](../types/string.md) | Yes|
|show\_previews|[Bool](../types/Bool.md) | Yes|
|events\_mask|[int](../types/int.md) | Yes|



### Type: [InputPeerNotifySettings](../types/InputPeerNotifySettings.md)


### Example:

```php
$inputPeerNotifySettings = ['_' => 'inputPeerNotifySettings', 'mute_until' => int, 'sound' => 'string', 'show_previews' => Bool, 'events_mask' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputPeerNotifySettings", "mute_until": int, "sound": "string", "show_previews": Bool, "events_mask": int}
```


Or, if you're into Lua:

```lua
inputPeerNotifySettings={_='inputPeerNotifySettings', mute_until=int, sound='string', show_previews=Bool, events_mask=int}

```


