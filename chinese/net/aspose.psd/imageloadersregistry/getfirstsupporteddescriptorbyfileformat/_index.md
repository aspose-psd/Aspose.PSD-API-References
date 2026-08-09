---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat"
second_title: "Aspose.PSD for .NET API 参考"
description: "ImageLoadersRegistry 方法。根据其类型名称获取第一个受支持的文件格式"
type: docs
weight: 50
url: /zh/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbyfileformat/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptorByFileFormat method

通过类型名称获取第一个受支持的文件格式。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByFileFormat(FileFormat fileFormat)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileFormat | FileFormat | 受支持的描述符文件格式。 |

### 返回值

如果未找到此类描述符，则返回第一个找到的加载器描述符或 null。

## 备注

第一个加载器描述符实际上是最后注册的。

### 另请参阅

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* enum [FileFormat](../../fileformat/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


