---
title: "类 ImageCreatorsRegistry"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.ImageCreatorsRegistry 类。表示图像创建器注册表"
type: docs
weight: 5090
url: /zh/net/aspose.psd/imagecreatorsregistry/
---
{{< psd/tize >}}
## ImageCreatorsRegistry class

表示图像创建者注册表。

```csharp
public static class ImageCreatorsRegistry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imagecreatorsregistry/registereddescriptors/) { get; } | 获取已注册的描述符。 |
| static [RegisteredFormats](../../aspose.psd/imagecreatorsregistry/registeredformats/) { get; } | 获取已注册的图像创建格式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFirstSupportedCreator](../../aspose.psd/imagecreatorsregistry/createfirstsupportedcreator/)(ImageOptionsBase) | 创建第一个找到的适用于指定条件的创建器。 |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imagecreatorsregistry/getfirstsupporteddescriptor/)(ImageOptionsBase) | 获取第一个找到的适用于指定条件的受支持描述符。 |
| static [Register](../../aspose.psd/imagecreatorsregistry/register/)(IImageCreatorDescriptor) | 注册指定的图像创建器描述符。 |
| static [RegisterCreator](../../aspose.psd/imagecreatorsregistry/registercreator/)(IImageCreatorDescriptor) | 注册创建器。 |
| static [UnregisterCreator](../../aspose.psd/imagecreatorsregistry/unregistercreator/)(IImageCreatorDescriptor) | 注销创建器。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


