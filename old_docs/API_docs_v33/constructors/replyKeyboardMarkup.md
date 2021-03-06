---
title: replyKeyboardMarkup
description: replyKeyboardMarkup attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: replyKeyboardMarkup  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|rows|Array of [KeyboardButtonRow](../types/KeyboardButtonRow.md) | Yes|



### Type: [ReplyMarkup](../types/ReplyMarkup.md)


### Example:

```php
$replyKeyboardMarkup = ['_' => 'replyKeyboardMarkup', 'rows' => [KeyboardButtonRow, KeyboardButtonRow]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "replyKeyboardMarkup", "rows": [KeyboardButtonRow]}
```


Or, if you're into Lua:

```lua
replyKeyboardMarkup={_='replyKeyboardMarkup', rows={KeyboardButtonRow}}

```


