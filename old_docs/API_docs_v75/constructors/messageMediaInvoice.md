---
title: messageMediaInvoice
description: messageMediaInvoice attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: messageMediaInvoice  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|shipping\_address\_requested|[Bool](../types/Bool.md) | Optional|
|test|[Bool](../types/Bool.md) | Optional|
|title|[string](../types/string.md) | Yes|
|description|[string](../types/string.md) | Yes|
|photo|[WebDocument](../types/WebDocument.md) | Optional|
|receipt\_msg\_id|[int](../types/int.md) | Optional|
|currency|[string](../types/string.md) | Yes|
|total\_amount|[long](../types/long.md) | Yes|
|start\_param|[string](../types/string.md) | Yes|



### Type: [MessageMedia](../types/MessageMedia.md)


### Example:

```php
$messageMediaInvoice = ['_' => 'messageMediaInvoice', 'shipping_address_requested' => Bool, 'test' => Bool, 'title' => 'string', 'description' => 'string', 'photo' => WebDocument, 'receipt_msg_id' => int, 'currency' => 'string', 'total_amount' => long, 'start_param' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "messageMediaInvoice", "shipping_address_requested": Bool, "test": Bool, "title": "string", "description": "string", "photo": WebDocument, "receipt_msg_id": int, "currency": "string", "total_amount": long, "start_param": "string"}
```


Or, if you're into Lua:

```lua
messageMediaInvoice={_='messageMediaInvoice', shipping_address_requested=Bool, test=Bool, title='string', description='string', photo=WebDocument, receipt_msg_id=int, currency='string', total_amount=long, start_param='string'}

```


