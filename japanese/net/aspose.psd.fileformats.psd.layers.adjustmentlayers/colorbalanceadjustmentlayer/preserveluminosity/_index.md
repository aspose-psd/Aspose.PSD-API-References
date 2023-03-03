---
title: ColorBalanceAdjustmentLayer.PreserveLuminosity
second_title: Aspose.PSD for .NET API リファレンス
description: ColorBalanceAdjustmentLayer 財産. これがBlncResource光度を保持します.
type: docs
weight: 70
url: /ja/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/
---
## ColorBalanceAdjustmentLayer.PreserveLuminosity property

これが[`BlncResource`](../../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/)光度を保持します.

```csharp
public bool PreserveLuminosity { get; set; }
```

### プロパティ値

`真実`光度を維持する場合。さもないと、`間違い` .

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


