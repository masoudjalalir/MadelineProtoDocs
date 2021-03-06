---
title: contacts.found
description: contacts_found attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: contacts.found  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|my\_results|Array of [Peer](../types/Peer.md) | Yes|
|results|Array of [Peer](../types/Peer.md) | Yes|
|chats|Array of [Chat](../types/Chat.md) | Yes|
|users|Array of [User](../types/User.md) | Yes|



### Type: [contacts\_Found](../types/contacts_Found.md)


### Example:

```php
$contacts_found = ['_' => 'contacts.found', 'my_results' => [Peer, Peer], 'results' => [Peer, Peer], 'chats' => [Chat, Chat], 'users' => [User, User]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "contacts.found", "my_results": [Peer], "results": [Peer], "chats": [Chat], "users": [User]}
```


Or, if you're into Lua:

```lua
contacts_found={_='contacts.found', my_results={Peer}, results={Peer}, chats={Chat}, users={User}}

```


