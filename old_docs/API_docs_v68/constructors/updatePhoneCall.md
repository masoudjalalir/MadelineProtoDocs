---
title: updatePhoneCall
description: updatePhoneCall attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updatePhoneCall  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|phone\_call|[PhoneCall](../types/PhoneCall.md) | Optional|



### Type: [Update](../types/Update.md)


### Example:

```php
$updatePhoneCall = ['_' => 'updatePhoneCall', 'phone_call' => PhoneCall];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "updatePhoneCall", "phone_call": PhoneCall}
```


Or, if you're into Lua:

```lua
updatePhoneCall={_='updatePhoneCall', phone_call=PhoneCall}

```


