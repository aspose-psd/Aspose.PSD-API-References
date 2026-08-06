---
title: "IImageCreatorDescriptor"
second_title: "Aspose.PSD 的 Java API 参考"
description: "指定创建器属性的图像创建器描述符。"
type: docs
weight: 119
url: /zh/java/com.aspose.psd/iimagecreatordescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageCreatorDescriptor extends IImageDescriptor
```

图像创建器描述符指定创建器属性。使用创建器描述符可以避免在内存中保留每个图像创建器实例以及多线程问题的必要性。
## Methods

| Method | 描述 |
| --- | --- |
| [canCreate(ImageOptionsBase imageOptions)](#canCreate-com.aspose.psd.ImageOptionsBase-) | 确定图像创建器是否可以使用 imageOptions 创建新图像。 |
| [createInstance()](#createInstance--) | 创建一个新的创建器实例。 |
### canCreate(ImageOptionsBase imageOptions) {#canCreate-com.aspose.psd.ImageOptionsBase-}
```
public abstract boolean canCreate(ImageOptionsBase imageOptions)
```


确定图像创建器是否可以使用 imageOptions 创建新图像。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | 图像选项。 |

**Returns:**
布尔型 - 如果由此描述符创建的图像创建器能够使用指定的 imageOptions 创建图像数据，则为 true；否则为 false。
### createInstance() {#createInstance--}
```
public abstract IImageCreator createInstance()
```


创建一个新的创建器实例。

**Returns:**
[IImageCreator](../../com.aspose.psd/iimagecreator) - A new creator instance.
