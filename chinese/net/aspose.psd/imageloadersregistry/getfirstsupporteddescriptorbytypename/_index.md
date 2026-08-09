---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName"
second_title: "Aspose.PSD for .NET API 参考"
description: "ImageLoadersRegistry 方法。根据其类型名称获取第一个受支持的描述符"
type: docs
weight: 60
url: /zh/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptorbytypename/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptorByTypeName method

通过类型名称获取第一个受支持的描述符。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptorByTypeName(
    string descriptorTypeName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| descriptorTypeName | String | 描述符类型名称。 |

### 返回值

如果未找到此类描述符，则返回第一个找到的加载器描述符或 null。

## 备注

第一个加载器描述符实际上是最后注册的。

### 另请参阅

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


