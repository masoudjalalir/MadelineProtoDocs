---
title: importedContacts
description: Represent result for ImportContacts request
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: importedContacts  
[Back to constructors index](index.md)



Represent result for ImportContacts request

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|user\_ids|Array of [int](../types/int.md) | Yes|User identifiers of imported contacts in the same order as they was specified in the request. 0 if contact is not yet registered|
|importer\_count|Array of [int](../types/int.md) | Yes|Number of users which imported corresponding contact. 0 for already registered users or if unavailable|



### Type: [ImportedContacts](../types/ImportedContacts.md)


