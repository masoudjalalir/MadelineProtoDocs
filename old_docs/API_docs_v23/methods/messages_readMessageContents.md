---
title: messages.readMessageContents
description: Mark message as read
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: messages.readMessageContents  
[Back to methods index](index.md)


Mark message as read

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|id|Array of [int](../types/int.md) | The messages to mark as read (only users and normal chats, not supergroups) | Yes|


### Return type: [Vector\_of\_int](../types/int.md)

### Can bots use this method: **NO**


### MadelineProto Example:


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$Vector_of_int = $MadelineProto->messages->readMessageContents(['id' => [int, int], ]);
```

### [PWRTelegram HTTP API](https://pwrtelegram.xyz) example (NOT FOR MadelineProto):



### As a user:

POST/GET to `https://api.pwrtelegram.xyz/userTOKEN/messages.readMessageContents`

Parameters:

id - Json encoded  array of int




Or, if you're into Lua:

```lua
Vector_of_int = messages.readMessageContents({id={int}, })
```

