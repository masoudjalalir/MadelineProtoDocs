---
title: contacts.importContacts
description: Add phone number as contact
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: contacts.importContacts  
[Back to methods index](index.md)


Add phone number as contact

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|contacts|Array of [InputContact](../types/InputContact.md) | The numbers to import | Yes|


### Return type: [contacts\_ImportedContacts](../types/contacts_ImportedContacts.md)

### Can bots use this method: **NO**


### MadelineProto Example:


```php
if (!file_exists('madeline.php')) {
    copy('https://phar.madelineproto.xyz/madeline.php', 'madeline.php');
}
include 'madeline.php';

$MadelineProto = new \danog\MadelineProto\API('session.madeline');
$MadelineProto->start();

$contacts_ImportedContacts = $MadelineProto->contacts->importContacts(['contacts' => [InputContact, InputContact], ]);
```

### [PWRTelegram HTTP API](https://pwrtelegram.xyz) example (NOT FOR MadelineProto):



### As a user:

POST/GET to `https://api.pwrtelegram.xyz/userTOKEN/contacts.importContacts`

Parameters:

contacts - Json encoded  array of InputContact




Or, if you're into Lua:

```lua
contacts_ImportedContacts = contacts.importContacts({contacts={InputContact}, })
```

