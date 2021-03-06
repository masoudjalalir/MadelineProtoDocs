---
title: pageBlockEmbedPost
description: pageBlockEmbedPost attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: pageBlockEmbedPost  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|url|[string](../types/string.md) | Yes|
|webpage\_id|[long](../types/long.md) | Yes|
|author\_photo\_id|[long](../types/long.md) | Yes|
|author|[string](../types/string.md) | Yes|
|date|[int](../types/int.md) | Yes|
|blocks|Array of [PageBlock](../types/PageBlock.md) | Yes|
|caption|[RichText](../types/RichText.md) | Yes|



### Type: [PageBlock](../types/PageBlock.md)


### Example:

```php
$pageBlockEmbedPost = ['_' => 'pageBlockEmbedPost', 'url' => 'string', 'webpage_id' => long, 'author_photo_id' => long, 'author' => 'string', 'date' => int, 'blocks' => [PageBlock, PageBlock], 'caption' => RichText];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "pageBlockEmbedPost", "url": "string", "webpage_id": long, "author_photo_id": long, "author": "string", "date": int, "blocks": [PageBlock], "caption": RichText}
```


Or, if you're into Lua:

```lua
pageBlockEmbedPost={_='pageBlockEmbedPost', url='string', webpage_id=long, author_photo_id=long, author='string', date=int, blocks={PageBlock}, caption=RichText}

```


