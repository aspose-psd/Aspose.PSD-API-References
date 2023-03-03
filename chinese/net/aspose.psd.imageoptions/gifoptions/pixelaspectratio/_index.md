---
title: GifOptions.PixelAspectRatio
second_title: Aspose.PSD for .NET API 参考
description: GifOptions 财产. 获取或设置 GIF 像素纵横比
type: docs
weight: 90
url: /zh/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
## GifOptions.PixelAspectRatio property

获取或设置 GIF 像素纵横比。

```csharp
public byte PixelAspectRatio { get; set; }
```

### 适当的价值

GIF 像素宽高比。

### 评论

像素纵横比 - 用于计算原始图像中像素纵横比的近似值 的系数。如果 字段的值不为0，则根据以下公式计算纵横比 的近似值： 纵横比=（像素纵横比+ 15）/ 64 像素纵横比定义为像素的商' s 宽度超过其高度。该字段中的值范围允许 4:1 的最宽像素到 1:4 的最高像素的规格，增量为 1/64。 值： 0 - 未给出纵横比信息。 1..255 -计算中使用的值。

### 也可以看看

* class [GifOptions](../)
* 命名空间 [Aspose.PSD.ImageOptions](../../gifoptions/)
* 部件 [Aspose.PSD](../../../)


