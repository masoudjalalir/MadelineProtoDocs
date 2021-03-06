---
title: decryptedMessageActionCommitKey
description: decryptedMessageActionCommitKey attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: decryptedMessageActionCommitKey\_20  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|exchange\_id|[long](../types/long.md) | Yes|
|key\_fingerprint|[long](../types/long.md) | Yes|



### Type: [DecryptedMessageAction](../types/DecryptedMessageAction.md)


### Example:

```php
$decryptedMessageActionCommitKey_20 = ['_' => 'decryptedMessageActionCommitKey', 'exchange_id' => long, 'key_fingerprint' => long];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "decryptedMessageActionCommitKey", "exchange_id": long, "key_fingerprint": long}
```


Or, if you're into Lua:

```lua
decryptedMessageActionCommitKey_20={_='decryptedMessageActionCommitKey', exchange_id=long, key_fingerprint=long}

```


