---
title: editMessageText
description: Edits text of text or game message. Non-bots can edit message in a limited period of time. Returns edited message after edit is complete server side
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: editMessageText  
[Back to methods index](index.md)


YOU CANNOT USE THIS METHOD IN MADELINEPROTO


Edits text of text or game message. Non-bots can edit message in a limited period of time. Returns edited message after edit is complete server side

### Parameters:

| Name     |    Type       | Required | Description |
|----------|---------------|----------|-------------|
|chat\_id|[int53](../types/int53.md) | Yes|Chat the message belongs to|
|message\_id|[int53](../types/int53.md) | Yes|Identifier of the message|
|reply\_markup|[ReplyMarkup](../types/ReplyMarkup.md) | Yes|Bots only. New message reply markup|
|input\_message\_content|[InputMessageContent](../types/InputMessageContent.md) | Yes|New text content of the message. Should be of type InputMessageText|


### Return type: [Message](../types/Message.md)
