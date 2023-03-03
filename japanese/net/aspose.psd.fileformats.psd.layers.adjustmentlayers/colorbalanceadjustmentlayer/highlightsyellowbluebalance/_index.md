---
title: ColorBalanceAdjustmentLayer.HighlightsYellowBlueBalance
second_title: Aspose.PSD for .NET API リファレンス
description: ColorBalanceAdjustmentLayer 財産. ハイライト イエロー ブルー バランスを取得または設定します
type: docs
weight: 30
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightsyellowbluebalance/
---
## ColorBalanceAdjustmentLayer.HighlightsYellowBlueBalance property

ハイライト イエロー ブルー バランスを取得または設定します。

```csharp
public short HighlightsYellowBlueBalance { get; set; }
```

### プロパティ値

ハイライト イエロー ブルー バランス.

### 例外

| 例外 | 調子 |
| --- | --- |
| ArgumentOutOfRangeException | ハイライト 黄 青 残高は -100 から +100 の範囲内でなければなりません. |

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


