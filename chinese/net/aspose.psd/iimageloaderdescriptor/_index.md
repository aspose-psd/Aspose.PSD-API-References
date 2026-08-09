---
title: "接口 IImageLoaderDescriptor"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.IImageLoaderDescriptor 接口。指定加载器属性的图像加载器描述符。使用加载器描述符可以克服必须在内存中保留每个图像加载器实例以及多线程问题的需求。"
type: docs
weight: 4930
url: /zh/net/aspose.psd/iimageloaderdescriptor/
---
{{< psd/tize >}}
## IImageLoaderDescriptor interface

图像加载器描述符，指定加载器属性。加载器描述符用于克服在内存中保留每个图像加载器实例以及多线程问题的必要性。

```csharp
public interface IImageLoaderDescriptor : IImageDescriptor
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CanLoad](../../aspose.psd/iimageloaderdescriptor/canload/)(StreamContainer, LoadOptions) | 确定图像加载器是否可以从指定的流读取新图像，并可选择使用 *loadOptions*。 |
| [CreateInstance](../../aspose.psd/iimageloaderdescriptor/createinstance/)() | 创建一个新的加载器实例。 |

### 另请参阅

* interface [IImageDescriptor](../iimagedescriptor/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


