---
title: messageActionGameScore
description: messageActionGameScore attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: messageActionGameScore  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|game\_id|[long](../types/long.md) | Yes|
|score|[int](../types/int.md) | Yes|



### Type: [MessageAction](../types/MessageAction.md)


### Example:

```php
$messageActionGameScore = ['_' => 'messageActionGameScore', 'game_id' => long, 'score' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "messageActionGameScore", "game_id": long, "score": int}
```


Or, if you're into Lua:

```lua
messageActionGameScore={_='messageActionGameScore', game_id=long, score=int}

```


