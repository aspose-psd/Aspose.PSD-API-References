---
title: "GifOptions.PixelAspectRatio"
second_title: "Aspose.PSD for .NET API 参考"
description: "GifOptions 属性。获取或设置 GIF 像素纵横比"
type: docs
weight: 90
url: /zh/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
{{< psd/tize >}}
## GifOptions.PixelAspectRatio property

获取或设置 GIF 像素宽高比。

```csharp
public byte PixelAspectRatio { get; set; }
```

### Property Value

GIF 像素纵横比。

## 备注

Pixel Aspect Ratio - 用于计算原始图像中像素纵横比近似值的因素。如果字段值不为 0，则根据公式计算该近似纵横比：Aspect Ratio = (Pixel Aspect Ratio + 15) / 64。Pixel Aspect Ratio 被定义为像素宽度除以高度的商。此字段的取值范围允许以 1/64 为增量指定最宽像素为 4:1 到最窄像素为 1:4。取值：0 - 未提供纵横比信息。1..255 - 用于计算的值。

### 另请参阅

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


