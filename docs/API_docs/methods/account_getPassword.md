---
title: account.getPassword
description: Get the current password
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: account.getPassword  
[Back to methods index](index.md)


Get the current password



### Return type: [account\_Password](../types/account_Password.md)

### Can bots use this method: **NO**


### MadelineProto Example:


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$account_Password = $MadelineProto->account->getPassword();
```

### [PWRTelegram HTTP API](https://pwrtelegram.xyz) example (NOT FOR MadelineProto):



### As a user:

POST/GET to `https://api.pwrtelegram.xyz/userTOKEN/account.getPassword`

Parameters:




Or, if you're into Lua:

```lua
account_Password = account.getPassword({})
```

