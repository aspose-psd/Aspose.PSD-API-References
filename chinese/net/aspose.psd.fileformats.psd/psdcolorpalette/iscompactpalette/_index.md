---
title: PsdColorPalette.IsCompactPalette
second_title: Aspose.PSD for .NET API 参考
description: PsdColorPalette 财产. 获取一个值指示它是否紧凑调色板
type: docs
weight: 70
url: /zh/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
## PsdColorPalette.IsCompactPalette property

获取一个值，指示它是否紧凑调色板。

```csharp
public bool IsCompactPalette { get; }
```

### 适当的价值

`真的`如果紧凑它调色板;否则，`错误的`.

### 评论

Compact palette 意味着图像将尽可能仅包含指定的调色板条目，或者换句话说图像将更紧凑并占用更少的空间； 否则将有 2^BitsPerPixel 条目并且图像将为所有可能的调色板条目保留更多空间. 将此值设置为 true 并更改调色板条目可能会导致性能下降，因为可能会发生数据移动，因此请谨慎使用。

### 也可以看看

* class [PsdColorPalette](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd](../../psdcolorpalette/)
* 部件 [Aspose.PSD](../../../)


