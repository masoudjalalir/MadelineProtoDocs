---
title: payments.paymentVerficationNeeded
description: payments_paymentVerficationNeeded attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: payments.paymentVerficationNeeded  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|url|[string](../types/string.md) | Yes|



### Type: [payments\_PaymentResult](../types/payments_PaymentResult.md)


### Example:

```php
$payments_paymentVerficationNeeded = ['_' => 'payments.paymentVerficationNeeded', 'url' => 'string'];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "payments.paymentVerficationNeeded", "url": "string"}
```


Or, if you're into Lua:

```lua
payments_paymentVerficationNeeded={_='payments.paymentVerficationNeeded', url='string'}

```


