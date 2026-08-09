---
title: "ImageLoadersRegistry.GetFirstSupportedDescriptor"
second_title: "Aspose.PSD for .NET API 参考"
description: "ImageLoadersRegistry 方法。获取适用于指定 *stream* 且可选 *loadOptions* 的第一个找到的受支持描述符"
type: docs
weight: 40
url: /zh/net/aspose.psd/imageloadersregistry/getfirstsupporteddescriptor/
---
{{< psd/tize >}}
## ImageLoadersRegistry.GetFirstSupportedDescriptor method

获取第一个适用于指定 *stream* 且可选的 *loadOptions* 的受支持描述符。

```csharp
public static IImageLoaderDescriptor GetFirstSupportedDescriptor(Stream stream, 
    LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

支持指定 *stream* 和 *loadOptions* 的加载器描述符，若未找到则返回 null。

## 备注

第一个加载器描述符实际上是最后注册的。

### 另请参阅

* interface [IImageLoaderDescriptor](../../iimageloaderdescriptor/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


