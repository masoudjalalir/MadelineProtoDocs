---
title: textUrl
description: textUrl attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: textUrl  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|text|[RichText](../types/RichText.md) | Yes|
|url|[string](../types/string.md) | Yes|
|webpage\_id|[long](../types/long.md) | Yes|



### Type: [RichText](../types/RichText.md)


### Example:

```php
$textUrl = ['_' => 'textUrl', 'text' => RichText, 'url' => 'string', 'webpage_id' => long];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "textUrl", "text": RichText, "url": "string", "webpage_id": long}
```


Or, if you're into Lua:

```lua
textUrl={_='textUrl', text=RichText, url='string', webpage_id=long}

```


