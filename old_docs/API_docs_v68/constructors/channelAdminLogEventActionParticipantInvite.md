---
title: channelAdminLogEventActionParticipantInvite
description: channelAdminLogEventActionParticipantInvite attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: channelAdminLogEventActionParticipantInvite  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|participant|[ChannelParticipant](../types/ChannelParticipant.md) | Yes|



### Type: [ChannelAdminLogEventAction](../types/ChannelAdminLogEventAction.md)


### Example:

```php
$channelAdminLogEventActionParticipantInvite = ['_' => 'channelAdminLogEventActionParticipantInvite', 'participant' => ChannelParticipant];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "channelAdminLogEventActionParticipantInvite", "participant": ChannelParticipant}
```


Or, if you're into Lua:

```lua
channelAdminLogEventActionParticipantInvite={_='channelAdminLogEventActionParticipantInvite', participant=ChannelParticipant}

```


