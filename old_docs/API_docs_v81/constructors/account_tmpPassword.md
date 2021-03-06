---
title: account.tmpPassword
description: account_tmpPassword attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: account.tmpPassword  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|tmp\_password|[bytes](../types/bytes.md) | Yes|
|valid\_until|[int](../types/int.md) | Yes|



### Type: [account\_TmpPassword](../types/account_TmpPassword.md)


### Example:

```php
$account_tmpPassword = ['_' => 'account.tmpPassword', 'tmp_password' => 'bytes', 'valid_until' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "account.tmpPassword", "tmp_password": {"_": "bytes", "bytes":"base64 encoded bytes"}, "valid_until": int}
```


Or, if you're into Lua:

```lua
account_tmpPassword={_='account.tmpPassword', tmp_password='bytes', valid_until=int}

```


