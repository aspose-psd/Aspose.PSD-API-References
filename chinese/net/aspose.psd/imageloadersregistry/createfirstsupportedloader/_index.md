---
title: "ImageLoadersRegistry.CreateFirstSupportedLoader"
second_title: "Aspose.PSD for .NET API 参考"
description: "ImageLoadersRegistry 方法。创建第一个适用于指定流并可选 loadOptions 的加载器"
type: docs
weight: 30
url: /zh/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
{{< psd/tize >}}
## ImageLoadersRegistry.CreateFirstSupportedLoader method

创建第一个适用于指定 *stream* 且可选的 *loadOptions* 的加载器。

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

支持指定 *stream* 和 *loadOptions* 的加载器，如果未找到此类加载器则返回 null。

## 备注

第一个加载器实际上是最后注册的。

### 另请参阅

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


