---
title: messages.botCallbackAnswer
description: messages_botCallbackAnswer attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: messages.botCallbackAnswer  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|alert|[Bool](../types/Bool.md) | Optional|
|has\_url|[Bool](../types/Bool.md) | Optional|
|message|[string](../types/string.md) | Optional|
|url|[string](../types/string.md) | Optional|



### Type: [messages\_BotCallbackAnswer](../types/messages_BotCallbackAnswer.md)


### Example:

```php
$messages_botCallbackAnswer = ['_' => 'messages.botCallbackAnswer', 'alert' => Bool, 'has_url' => Bool, 'message' => 'string', 'url' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "messages.botCallbackAnswer", "alert": Bool, "has_url": Bool, "message": "string", "url": "string"}
```


Or, if you're into Lua:

```lua
messages_botCallbackAnswer={_='messages.botCallbackAnswer', alert=Bool, has_url=Bool, message='string', url='string'}

```


