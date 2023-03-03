---
title: ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance
second_title: Aspose.PSD for .NET API 参考
description: ColorBalanceAdjustmentLayer 财产. 获取或设置阴影青色红色平衡
type: docs
weight: 80
url: /zh/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowscyanredbalance/
---
## ColorBalanceAdjustmentLayer.ShadowsCyanRedBalance property

获取或设置阴影青色红色平衡。

```csharp
public short ShadowsCyanRedBalance { get; set; }
```

### 适当的价值

阴影青色红色平衡。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentOutOfRangeException | 阴影青色红色平衡必须在 -100 到 +100 的范围内。 |

### 例子

以下代码演示了对 ColorBalanceAdjustmentLayer 的支持。

```csharp
[C#]

var filePath = "ColorBalance.psd";
var outputPath = "ColorBalance_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    foreach (var layer in im.Layers)
    {
        var cbLayer = layer as ColorBalanceAdjustmentLayer;
        if (cbLayer != null)
        {
            cbLayer.ShadowsCyanRedBalance = 30;
            cbLayer.ShadowsMagentaGreenBalance = -15;
            cbLayer.ShadowsYellowBlueBalance = 40;
            cbLayer.MidtonesCyanRedBalance = -90;
            cbLayer.MidtonesMagentaGreenBalance = -25;
            cbLayer.MidtonesYellowBlueBalance = 20;
            cbLayer.HighlightsCyanRedBalance = -30;
            cbLayer.HighlightsMagentaGreenBalance = 67;
            cbLayer.HighlightsYellowBlueBalance = -95;
            cbLayer.PreserveLuminosity = true;
        }
    }

    im.Save(outputPath);
}
```

### 也可以看看

* class [ColorBalanceAdjustmentLayer](../)
* 命名空间 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* 部件 [Aspose.PSD](../../../)


