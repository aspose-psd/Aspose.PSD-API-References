---
title: ImageExportersRegistry.CreateFirstSupportedExporter
second_title: Aspose.PSD for .NET API 参考
description: ImageExportersRegistry 方法. 创建适合指定保存选项和图像的第一个找到的导出器
type: docs
weight: 30
url: /zh/net/aspose.psd/imageexportersregistry/createfirstsupportedexporter/
---
## ImageExportersRegistry.CreateFirstSupportedExporter method

创建适合指定保存选项和图像的第一个找到的导出器。

```csharp
public static IImageExporter CreateFirstSupportedExporter(Image image, ImageOptionsBase options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| image | Image | 要导出的图像。 |
| options | ImageOptionsBase | 用于导出的保存选项。 |

### 返回值

支持指定图像和保存选项的导出器，如果未找到此类导出器，则返回 null。

### 评论

第一个出口商实际上是最后一个注册的。

### 也可以看看

* interface [IImageExporter](../../iimageexporter/)
* class [Image](../../image/)
* class [ImageOptionsBase](../../imageoptionsbase/)
* class [ImageExportersRegistry](../)
* 命名空间 [Aspose.PSD](../../imageexportersregistry/)
* 部件 [Aspose.PSD](../../../)


