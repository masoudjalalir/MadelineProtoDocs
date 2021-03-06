---
title: inputChatPhoto
description: inputChatPhoto attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: inputChatPhoto  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[MessageMedia, Message, Update or InputPhoto](../types/InputPhoto.md) | Optional|
|crop|[InputPhotoCrop](../types/InputPhotoCrop.md) | Yes|



### Type: [InputChatPhoto](../types/InputChatPhoto.md)


### Example:

```php
$inputChatPhoto = ['_' => 'inputChatPhoto', 'id' => InputPhoto, 'crop' => InputPhotoCrop];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "inputChatPhoto", "id": InputPhoto, "crop": InputPhotoCrop}
```


Or, if you're into Lua:

```lua
inputChatPhoto={_='inputChatPhoto', id=InputPhoto, crop=InputPhotoCrop}

```


