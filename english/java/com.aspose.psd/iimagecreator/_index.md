---
title: IImageCreator
second_title: Aspose.PSD for Java API Reference
description: The image creator.
type: docs
weight: 118
url: /java/com.aspose.psd/iimagecreator/
---
```
public interface IImageCreator
```

The image creator.
## Methods

| Method | Description |
| --- | --- |
| [create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-) | Creates a new image instance with  imageOptions . |
### create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-}
```
public abstract Image create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)
```


Creates a new image instance with  imageOptions .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | The stream container to create image data in. |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | The image options. |
| width | int | width of new image |
| height | int | height of new image |

**Returns:**
[Image](../../com.aspose.psd/image) - A new image instance.
