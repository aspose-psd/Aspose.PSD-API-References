---
title: IColorPalette.IsCompactPalette
second_title: Aspose.PSD for .NET API 参考
description: IColorPalette 财产. 获取指示是否使用紧凑调色板的值
type: docs
weight: 40
url: /zh/net/aspose.psd/icolorpalette/iscompactpalette/
---
## IColorPalette.IsCompactPalette property

获取指示是否使用紧凑调色板的值。

```csharp
public bool IsCompactPalette { get; }
```

### 适当的价值

`真的`如果使用紧凑型调色板；否则，`错误的`.

### 评论

紧凑的调色板意味着图像将尽可能仅包含指定的调色板条目，或者换句话说，图像将更紧凑并占用更少的空间； 否则将有 2^BitsPerPixel 条目，图像将为所有可能的调色板条目保留更多空间。 将此值设置为 true 并更改调色板条目可能会导致性能下降，因为可能会发生数据移动，因此请谨慎使用。

### 也可以看看

* interface [IColorPalette](../)
* 命名空间 [Aspose.PSD](../../icolorpalette/)
* 部件 [Aspose.PSD](../../../)


