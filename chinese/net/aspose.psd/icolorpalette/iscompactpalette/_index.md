---
title: "IColorPalette.IsCompactPalette"
second_title: "Aspose.PSD for .NET API 参考"
description: "IColorPalette 属性。获取一个值，指示是否使用紧凑调色板"
type: docs
weight: 40
url: /zh/net/aspose.psd/icolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## IColorPalette.IsCompactPalette property

获取一个值，指示是否使用紧凑调色板。

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true` 如果使用紧凑调色板；否则为 `false`。

## 备注

紧凑调色板表示图像将在可能的情况下仅包含指定的调色板条目，换句话说，图像将更紧凑并占用更少的空间；否则将有 2^BitsPerPixel 条目，图像将为所有可能的调色板条目预留更多空间。将此值设为 `true` 并更改调色板条目可能会导致性能下降，因为可能会发生数据移动，请谨慎使用。

### 另请参阅

* interface [IColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


