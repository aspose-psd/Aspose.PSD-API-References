---
title: "GifOptions.ColorResolution"
second_title: "Aspose.PSD for .NET API 参考"
description: "GifOptions 属性。获取或设置 GIF 颜色分辨率"
type: docs
weight: 30
url: /zh/net/aspose.psd.imageoptions/gifoptions/colorresolution/
---
{{< psd/tize >}}
## GifOptions.ColorResolution property

获取或设置 GIF 颜色分辨率。

```csharp
public byte ColorResolution { get; set; }
```

### Property Value

颜色分辨率。

## 备注

Color Resolution - 原始图像每个原色可用的位数减 1。该值表示用于从中选择图形颜色的完整调色板的大小，而不是图形实际使用的颜色数量。例如，如果此字段的值为 3，则原始图像的调色板每个原色有 4 位可用于创建图像。即使源机器并未提供完整调色板中的每一种颜色，也应设置此值以指示原始调色板的丰富程度。

### 另请参阅

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


