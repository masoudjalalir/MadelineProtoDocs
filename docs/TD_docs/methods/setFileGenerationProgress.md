---
title: setFileGenerationProgress
description: Next part of a file was generated
image: https://docs.madelineproto.xyz/favicons/android-chrome-256x256.png
---
# Method: setFileGenerationProgress  
[Back to methods index](index.md)


YOU CANNOT USE THIS METHOD IN MADELINEPROTO


Next part of a file was generated

### Parameters:

| Name     |    Type       | Description | Required |
|----------|---------------|-------------|----------|
|generation\_id|[int64](../constructors/int64.md) | Identifier of the generation process | Yes|
|size|[int](../types/int.md) | Full size of file in bytes, 0 if unknown. | Yes|
|local\_size|[int](../types/int.md) | Number of bytes already generated. Negative number means that generation has failed and should be terminated | Yes|


### Return type: [Ok](../types/Ok.md)

