---
title: phoneCallWaiting
description: phoneCallWaiting attributes, type and example
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: phoneCallWaiting  
[Back to constructors index](index.md)



### Attributes:

| Name     |    Type       | Required |
|----------|---------------|----------|
|id|[long](../types/long.md) | Yes|
|access\_hash|[long](../types/long.md) | Yes|
|date|[int](../types/int.md) | Yes|
|admin\_id|[int](../types/int.md) | Yes|
|participant\_id|[int](../types/int.md) | Yes|
|protocol|[PhoneCallProtocol](../types/PhoneCallProtocol.md) | Yes|
|receive\_date|[int](../types/int.md) | Optional|



### Type: [PhoneCall](../types/PhoneCall.md)


### Example:

```php
$phoneCallWaiting = ['_' => 'phoneCallWaiting', 'id' => long, 'access_hash' => long, 'date' => int, 'admin_id' => int, 'participant_id' => int, 'protocol' => PhoneCallProtocol, 'receive_date' => int];
```  

[PWRTelegram](https://pwrtelegram.xyz) json-encoded version:

```
{"_": "phoneCallWaiting", "id": long, "access_hash": long, "date": int, "admin_id": int, "participant_id": int, "protocol": PhoneCallProtocol, "receive_date": int}
```


Or, if you're into Lua:

```lua
phoneCallWaiting={_='phoneCallWaiting', id=long, access_hash=long, date=int, admin_id=int, participant_id=int, protocol=PhoneCallProtocol, receive_date=int}

```


