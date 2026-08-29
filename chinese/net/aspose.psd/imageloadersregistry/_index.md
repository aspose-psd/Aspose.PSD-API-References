---
title: "ImageLoadersRegistry 类"
second_title: "Aspose.PSD for .NET API 参考"
description: "Aspose.PSD.ImageLoadersRegistry 类。表示图像加载器注册表"
type: docs
weight: 5270
url: /zh/net/aspose.psd/imageloadersregistry/
---
{{< psd/tize >}}
## ImageLoadersRegistry class

表示图像加载器注册表。

```csharp
public static class ImageLoadersRegistry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [RegisteredDescriptors](../../aspose.psd/imageloadersregistry/registereddescriptors/) { get; } | 获取已注册的描述符。 |
| static [RegisteredFormats](../../aspose.psd/imageloadersregistry/registeredformats/) { get; } | 获取已注册的图像加载格式。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [CreateFirstSupportedLoader](../../aspose.psd/imageloadersregistry/createfirstsupportedloader/)(Stream, LoadOptions) | 创建第一个适用于指定 *stream* 且可选的 *loadOptions* 的加载器。 |
| static [GetFirstSupportedDescriptor](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/)(Stream, LoadOptions) | 获取第一个适用于指定 *stream* 且可选的 *loadOptions* 的受支持描述符。 |
| static [GetFirstSupportedDescriptorByFileFormat](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/)(FileFormat) | 通过类型名称获取第一个受支持的文件格式。 |
| static [GetFirstSupportedDescriptorByTypeName](../../aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/)(string) | 通过类型名称获取第一个受支持的描述符。 |
| static [Register](../../aspose.psd/imageloadersregistry/register/)(IImageLoaderDescriptor) | 注册指定的图像加载器描述符。 |
| static [RegisterLoader](../../aspose.psd/imageloadersregistry/registerloader/)(IImageLoaderDescriptor) | 注册加载器。 |
| static [UnregisterLoader](../../aspose.psd/imageloadersregistry/unregisterloader/)(IImageLoaderDescriptor) | 注销加载器。 |

### 另请参阅

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


