---
title: updateChatTopMessage
description: Top message of the chat has changed. If top_message is null then top message in the chat became unknown. Some new unknown messages might be added to the chat in that case
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Constructor: updateChatTopMessage  
[Back to constructors index](index.md)



Top message of the chat has changed. If top_message is null then top message in the chat became unknown. Some new unknown messages might be added to the chat in that case

### Attributes:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|chat\_id|[int53](../types/int53.md) | Yes|Chat identifier|
|top\_message|[message](../constructors/message.md) | Yes|New top message of the chat, nullable|
|order|[int64](../constructors/int64.md) | Yes|New value of the chat order|



### Type: [Update](../types/Update.md)

