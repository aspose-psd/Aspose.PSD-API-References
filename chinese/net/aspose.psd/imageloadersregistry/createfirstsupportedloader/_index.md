---
title: ImageLoadersRegistry.CreateFirstSupportedLoader
second_title: Aspose.PSD for .NET API 参考
description: ImageLoadersRegistry 方法. 创建第一个找到的适合指定的加载器stream和可选的loadOptions .
type: docs
weight: 30
url: /zh/net/aspose.psd/imageloadersregistry/createfirstsupportedloader/
---
## ImageLoadersRegistry.CreateFirstSupportedLoader method

创建第一个找到的适合指定的加载器*stream*和可选的*loadOptions* .

```csharp
public static IImageLoader CreateFirstSupportedLoader(Stream stream, LoadOptions loadOptions)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 流。 |
| loadOptions | LoadOptions | 加载选项。 |

### 返回值

支持指定的loader*stream*和*loadOptions*如果没有找到这样的加载器，则为 null.

### 评论

第一个加载器实际上是最后一个注册的。

### 也可以看看

* interface [IImageLoader](../../iimageloader/)
* class [LoadOptions](../../loadoptions/)
* class [ImageLoadersRegistry](../)
* 命名空间 [Aspose.PSD](../../imageloadersregistry/)
* 部件 [Aspose.PSD](../../../)


