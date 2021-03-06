---
title: dialog
description: dialog attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: dialog  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|pinned|[Bool](../types/Bool.md) | Optional|
|peer|[Peer](../types/Peer.md) | Yes|
|top\_message|[int](../types/int.md) | Yes|
|read\_inbox\_max\_id|[int](../types/int.md) | Yes|
|read\_outbox\_max\_id|[int](../types/int.md) | Yes|
|unread\_count|[int](../types/int.md) | Yes|
|unread\_mentions\_count|[int](../types/int.md) | Yes|
|notify\_settings|[PeerNotifySettings](../types/PeerNotifySettings.md) | Optional|
|pts|[int](../types/int.md) | Optional|
|draft|[DraftMessage](../types/DraftMessage.md) | Optional|



### Type: [Dialog](../types/Dialog.md)


### Example:

```php
$dialog = ['_' => 'dialog', 'pinned' => Bool, 'peer' => Peer, 'top_message' => int, 'read_inbox_max_id' => int, 'read_outbox_max_id' => int, 'unread_count' => int, 'unread_mentions_count' => int, 'notify_settings' => PeerNotifySettings, 'pts' => int, 'draft' => DraftMessage];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "dialog", "pinned": Bool, "peer": Peer, "top_message": int, "read_inbox_max_id": int, "read_outbox_max_id": int, "unread_count": int, "unread_mentions_count": int, "notify_settings": PeerNotifySettings, "pts": int, "draft": DraftMessage}
```


Or, if you're into Lua:

```lua
dialog={_='dialog', pinned=Bool, peer=Peer, top_message=int, read_inbox_max_id=int, read_outbox_max_id=int, unread_count=int, unread_mentions_count=int, notify_settings=PeerNotifySettings, pts=int, draft=DraftMessage}

```


