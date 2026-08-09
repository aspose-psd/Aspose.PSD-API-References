---
title: "ImageExtensions.ToGdiImage"
second_title: "Aspose.PSD for .NET API 参考"
description: "ImageExtensions 方法。将 Image 转换为 Image"
type: docs
weight: 10
url: /zh/net/aspose.psd.extensions/imageextensions/togdiimage/
---
{{< psd/tize >}}
## ImageExtensions.ToGdiImage method

将 Image 转换为 Image。

```csharp
[Obsolete("Please do not use this method as you may get OutOfMemoryException if image is too large for GDI to fit.")]
public static Image ToGdiImage(Image image)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| image | Image | 要转换的 Image。 |

### 返回值

已转换的 Image。

## 备注

警告，GDI 图像的边界可能比 *image* 的更小。要获取图像的所有部分，请使用更安全的扩展方法 ToGdiImageFull。

### 另请参阅

* class [Image](../../../aspose.psd/image/)
* class [ImageExtensions](../)
* namespace [Aspose.PSD.Extensions](../../../aspose.psd.extensions/)
* assembly [Aspose.PSD](../../../)


