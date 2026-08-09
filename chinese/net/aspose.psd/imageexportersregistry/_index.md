---
title: "类 ImageExportersRegistry"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.ImageExportersRegistry 类。表示图像导出器注册表"
type: docs
weight: 5100
url: /zh/net/aspose.psd/imageexportersregistry/
---
{{< psd/tize >}}
## ImageExportersRegistry class

表示图像导出器注册表。

```csharp
public static class ImageExportersRegistry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [RegisteredExporterDescriptors](../../aspose.psd/imageexportersregistry/registeredexporterdescriptors/) { get; } | 获取已注册的导出器描述符。 |
| static [RegisteredFormats](../../aspose.psd/imageexportersregistry/registeredformats/) { get; } | 获取已注册的导出格式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFirstSupportedExporter](../../aspose.psd/imageexportersregistry/createfirstsupportedexporter/)(Image, ImageOptionsBase) | 创建第一个符合指定保存选项和图像的导出器。 |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageexportersregistry/getfirstsupporteddescriptor/)(Image, ImageOptionsBase) | 获取第一个符合指定保存选项和图像的受支持描述符。 |
| static [Register](../../aspose.psd/imageexportersregistry/register/)(IImageExporterDescriptor) | 注册指定的图像导出器描述符。 |
| static [RegisterExporter](../../aspose.psd/imageexportersregistry/registerexporter/)(IImageExporterDescriptor) | 注册导出器。 |
| static [UnregisterExporter](../../aspose.psd/imageexportersregistry/unregisterexporter/)(IImageExporterDescriptor) | 注销导出器。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


