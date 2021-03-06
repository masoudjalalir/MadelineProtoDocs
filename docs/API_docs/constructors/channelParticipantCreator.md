---
title: channelParticipantCreator
description: channelParticipantCreator attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: channelParticipantCreator  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|user\_id|[int](../types/int.md) | Yes|



### Type: [ChannelParticipant](../types/ChannelParticipant.md)


### Example:

```php
$channelParticipantCreator = ['_' => 'channelParticipantCreator', 'user_id' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "channelParticipantCreator", "user_id": int}
```


Or, if you're into Lua:

```lua
channelParticipantCreator={_='channelParticipantCreator', user_id=int}

```


