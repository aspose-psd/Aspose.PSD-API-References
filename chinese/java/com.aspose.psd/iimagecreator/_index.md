---
title: "IImageCreator"
second_title: "Aspose.PSD 的 Java API 参考"
description: "图像创建器。"
type: docs
weight: 118
url: /zh/java/com.aspose.psd/iimagecreator/
---
```
public interface IImageCreator
```

图像创建器。
## Methods

| Method | 描述 |
| --- | --- |
| [create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-) | 创建一个新的图像实例，使用  imageOptions 。 |
### create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.StreamContainer-com.aspose.psd.ImageOptionsBase-int-int-}
```
public abstract Image create(StreamContainer streamContainer, ImageOptionsBase imageOptions, int width, int height)
```


创建一个新的图像实例，使用  imageOptions 。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 用于创建图像数据的流容器。 |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 图像选项。 |
| 宽度 | int | 新图像的宽度 |
| 高度 | int | 新图像的高度 |

**Returns:**
[Image](../../com.aspose.psd/image) - A new image instance.
