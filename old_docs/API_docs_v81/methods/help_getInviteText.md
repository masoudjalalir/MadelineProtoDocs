---
title: help.getInviteText
description: Get invitation text
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: help.getInviteText  
[Back to methods index](index.md)


Get invitation text



### Return type: [help\_InviteText](../types/help_InviteText.md)

### Can bots use this method: **NO**


### MadelineProto Example:


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$help_InviteText = $MadelineProto->help->getInviteText();
```

### [PWRTelegram HTTP API](https://pwrtelegram.xyz) example (NOT FOR MadelineProto):



### As a user:

POST/GET to `https://api.pwrtelegram.xyz/userTOKEN/help.getInviteText`

Parameters:




Or, if you're into Lua:

```lua
help_InviteText = help.getInviteText({})
```

