---
title: payments.paymentResult
description: payments_paymentResult attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: payments.paymentResult  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|updates|[Updates](../types/Updates.md) | Yes|



### Type: [payments\_PaymentResult](../types/payments_PaymentResult.md)


### Example:

```php
$payments_paymentResult = ['_' => 'payments.paymentResult', 'updates' => Updates];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "payments.paymentResult", "updates": Updates}
```


Or, if you're into Lua:

```lua
payments_paymentResult={_='payments.paymentResult', updates=Updates}

```


