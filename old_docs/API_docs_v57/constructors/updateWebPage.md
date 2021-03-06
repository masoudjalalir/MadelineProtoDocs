---
title: updateWebPage
description: updateWebPage attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateWebPage  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|webpage|[WebPage](../types/WebPage.md) | Optional|
|pts|[int](../types/int.md) | Yes|
|pts\_count|[int](../types/int.md) | Yes|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateWebPage = ['_' => 'updateWebPage', 'webpage' => WebPage, 'pts' => int, 'pts_count' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateWebPage", "webpage": WebPage, "pts": int, "pts_count": int}
```


Or, if you're into Lua:

```lua
updateWebPage={_='updateWebPage', webpage=WebPage, pts=int, pts_count=int}

```


