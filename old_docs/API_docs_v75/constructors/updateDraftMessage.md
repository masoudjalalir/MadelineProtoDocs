---
title: updateDraftMessage
description: updateDraftMessage attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateDraftMessage  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|peer|[Peer](../types/Peer.md) | Yes|
|draft|[DraftMessage](../types/DraftMessage.md) | Optional|



### Type: [Update](../types/Update.md)


### Example:

```php
$updateDraftMessage = ['_' => 'updateDraftMessage', 'peer' => Peer, 'draft' => DraftMessage];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updateDraftMessage", "peer": Peer, "draft": DraftMessage}
```


Or, if you're into Lua:

```lua
updateDraftMessage={_='updateDraftMessage', peer=Peer, draft=DraftMessage}

```


