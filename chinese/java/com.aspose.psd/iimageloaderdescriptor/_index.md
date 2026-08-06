---
title: "IImageLoaderDescriptor"
second_title: "Aspose.PSD 的 Java API 参考"
description: "指定加载器属性的图像加载器描述符。"
type: docs
weight: 124
url: /zh/java/com.aspose.psd/iimageloaderdescriptor/
---

**All Implemented Interfaces:**
[com.aspose.psd.IImageDescriptor](../../com.aspose.psd/iimagedescriptor)
```
public interface IImageLoaderDescriptor extends IImageDescriptor
```

图像加载器描述符，指定加载器属性。使用加载器描述符可以避免必须在内存中保留每个图像加载器实例以及多线程问题。
## Methods

| Method | 描述 |
| --- | --- |
| [canLoad(StreamContainer streamContainer, LoadOptions loadOptions)](#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-) | 确定图像加载器是否可以从指定的流读取新图像，并可选择使用 loadOptions。 |
| [createInstance()](#createInstance--) | 创建一个新的加载器实例。 |
### canLoad(StreamContainer streamContainer, LoadOptions loadOptions) {#canLoad-com.aspose.psd.StreamContainer-com.aspose.psd.LoadOptions-}
```
public abstract boolean canLoad(StreamContainer streamContainer, LoadOptions loadOptions)
```


确定图像加载器是否可以从指定的流读取新图像，并可选择使用 loadOptions。

**Parameters:**
| Parameter | Type | 描述 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 流容器。 |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | 由 loadOptions 指定的文件格式详细信息。loadOptions 可能为 null。 |

**Returns:**
布尔值 - 如果由此描述符创建的图像加载器可以从流读取图像，则为 true；否则为 false。
### createInstance() {#createInstance--}
```
public abstract IImageLoader createInstance()
```


创建一个新的加载器实例。

**Returns:**
[IImageLoader](../../com.aspose.psd/iimageloader) - A new loader instance.
