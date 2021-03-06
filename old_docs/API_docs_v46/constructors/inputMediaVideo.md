---
title: inputMediaVideo
description: inputMediaVideo attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputMediaVideo  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|video|[InputVideo](../types/InputVideo.md) | Optional|
|caption|[string](../types/string.md) | Yes|



### Type: [InputMedia](../types/InputMedia.md)


### Example:

```php
$inputMediaVideo = ['_' => 'inputMediaVideo', 'video' => InputVideo, 'caption' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputMediaVideo", "video": InputVideo, "caption": "string"}
```


Or, if you're into Lua:

```lua
inputMediaVideo={_='inputMediaVideo', video=InputVideo, caption='string'}

```


