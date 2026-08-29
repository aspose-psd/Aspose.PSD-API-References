---
title: "ColorPalette.IsCompactPalette"
second_title: "Aspose.PSD for .NET API 参考"
description: "ColorPalette 属性。获取或设置指示是否使用紧凑调色板的值"
type: docs
weight: 60
url: /zh/net/aspose.psd/colorpalette/iscompactpalette/
---
{{< psd/tize >}}
## ColorPalette.IsCompactPalette property

获取或设置指示是否使用紧凑调色板的值。

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` 如果使用紧凑调色板；否则为 `false`。

## 备注

紧凑调色板表示图像将在可能的情况下仅包含指定的调色板条目，换句话说，图像将更紧凑并占用更少的空间；否则将有 2^BitsPerPixel 条目，图像将为所有可能的调色板条目预留更多空间。将此值设为 `true` 并更改调色板条目可能会导致性能下降，因为可能会发生数据移动，请谨慎使用。

### 另请参阅

* class [ColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


