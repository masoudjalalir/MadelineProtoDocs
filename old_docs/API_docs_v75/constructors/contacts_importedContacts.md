---
title: contacts.importedContacts
description: contacts_importedContacts attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: contacts.importedContacts  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|imported|Array of [ImportedContact](../types/ImportedContact.md) | Yes|
|popular\_invites|Array of [PopularContact](../types/PopularContact.md) | Yes|
|retry\_contacts|Array of [long](../types/long.md) | Yes|
|users|Array of [User](../types/User.md) | Yes|



### Type: [contacts\_ImportedContacts](../types/contacts_ImportedContacts.md)


### Example:

```php
$contacts_importedContacts = ['_' => 'contacts.importedContacts', 'imported' => [ImportedContact, ImportedContact], 'popular_invites' => [PopularContact, PopularContact], 'retry_contacts' => [long, long], 'users' => [User, User]];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "contacts.importedContacts", "imported": [ImportedContact], "popular_invites": [PopularContact], "retry_contacts": [long], "users": [User]}
```


Or, if you're into Lua:

```lua
contacts_importedContacts={_='contacts.importedContacts', imported={ImportedContact}, popular_invites={PopularContact}, retry_contacts={long}, users={User}}

```


