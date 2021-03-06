---
title: exportedMessageLink
description: exportedMessageLink attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: exportedMessageLink  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|link|[string](../types/string.md) | Yes|
|html|[string](../types/string.md) | Yes|



### Type: [ExportedMessageLink](../types/ExportedMessageLink.md)


### Example:

```php
$exportedMessageLink = ['_' => 'exportedMessageLink', 'link' => 'string', 'html' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "exportedMessageLink", "link": "string", "html": "string"}
```


Or, if you're into Lua:

```lua
exportedMessageLink={_='exportedMessageLink', link='string', html='string'}

```


