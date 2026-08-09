---
title: "PattResourceData.SetPattern"
second_title: "Aspose.PSD for .NET API 参考"
description: "PattResourceData 方法。设置图案像素缓冲区和目标尺寸，更新 Width / Height，并使用默认压缩模式 0 存储用于保存的数据"
type: docs
weight: 110
url: /zh/net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/setpattern/
---
{{< psd/tize >}}
## PattResourceData.SetPattern method

设置图案像素缓冲区和目标尺寸，更新 [`Width`](../width/) / [`Height`](../height/)，并使用默认压缩模式 (0) 存储用于保存的数据。

```csharp
public void SetPattern(int[] pixels, Rectangle bounds)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Int32[] | 32 位像素，采用 `0xAARRGGBB` 格式。 |
| bounds | Rectangle | 图案的像素边界。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [PsdImageArgumentException](../../../aspose.psd.coreexceptions.imageformats/psdimageargumentexception/) | 像素数组长度必须等于边界面积。 |

### 另请参阅

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [PattResourceData](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


