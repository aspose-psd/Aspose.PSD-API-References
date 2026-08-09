---
title: "ImageExportersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API 参考"
description: "ImageExportersRegistry 方法。获取首次找到的支持的描述符，适用于指定的保存选项和图像"
type: docs
weight: 40
url: /zh/net/aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageExportersRegistry.GetFirstSupportedDescriptor method

获取第一个符合指定保存选项和图像的受支持描述符。

```csharp
public static IImageExporterDescriptor GetFirstSupportedDescriptor(Image image, 
    ImageOptionsBase options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | Image | 要导出的图像。 |
| 选项 | ImageOptionsBase | 选项。 |

### 返回值

支持指定图像和保存选项的导出器描述符，如果未找到此类描述符则为 null。

## 备注

第一个导出器描述符实际上是最后注册的。

### 另请参阅

* interface [IImageExporterDescriptor](../../iimageexporterdescriptor/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


