---
title: "接口 IImageCreatorDescriptor"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.IImageCreatorDescriptor 接口。指定创建者属性的图像创建器描述符。使用创建者描述符可以避免在内存中保留每个图像创建器实例以及多线程问题。"
type: docs
weight: 4880
url: /zh/net/aspose.psd/iimagecreatordescriptor/
---
{{< psd/tize >}}
## IImageCreatorDescriptor interface

图像创建器描述符，指定创建器属性。创建器描述符用于克服在内存中保留每个图像创建器实例以及多线程问题的必要性。

```csharp
public interface IImageCreatorDescriptor : IImageDescriptor
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [CanCreate](../../aspose.psd/iimagecreatordescriptor/cancreate/)(ImageOptionsBase) | 确定图像创建器是否可以使用 *imageOptions* 创建新图像。 |
| [CreateInstance](../../aspose.psd/iimagecreatordescriptor/createinstance/)() | 创建一个新的创建器实例。 |

### 另请参阅

* interface [IImageDescriptor](../iimagedescriptor/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


