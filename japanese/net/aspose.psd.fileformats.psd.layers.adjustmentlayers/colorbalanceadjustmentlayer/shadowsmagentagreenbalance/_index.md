---
title: ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance
second_title: Aspose.PSD for .NET API リファレンス
description: ColorBalanceAdjustmentLayer 財産. シャドウ マゼンタ グリーン バランスを取得または設定します
type: docs
weight: 90
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsmagentagreenbalance/
---
## ColorBalanceAdjustmentLayer.ShadowsMagentaGreenBalance property

シャドウ マゼンタ グリーン バランスを取得または設定します。

```csharp
public short ShadowsMagentaGreenBalance { get; set; }
```

### プロパティ値

The Shadows Magenta Green Balance.

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | シャドウ マゼンタ グリーン バランスは -100 から +100 の範囲である必要があります。 |

### 例

次のコードは、ColorBalanceAdjustmentLayer のサポートを示しています。

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

### 関連項目

* class [ColorBalanceAdjustmentLayer](../)
* 名前空間 [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../colorbalanceadjustmentlayer/)
* 組み立て [Aspose.PSD](../../../)


